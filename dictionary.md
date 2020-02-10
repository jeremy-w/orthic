---
layout: page
title: "Orthic Dictionary"
toc: true
toc_hmax: 6
---

## Notation

Entries include an encoding into ASCII of the Orthic text.
Plain longhand works well enough for the full style. But with raising, lowering, and the com dot, it is convenient to have some additional conventions to enable a more faithful rendition of the more abbreviated styles.
Hopefully this enables searching by Orthic, rather than just by longhand.

Signs:

- A caret `^` signals raising, as in `^e` for "the". This is a half-step (the height of a `c`, `s`, or `e`) up from the letter just written.
- An underscore `_` signals lowering, as in `_t` for the "-ight" ending. This is a half-step down.
- A `*` signals a dot, as on `*plex` for "complex".
- An uppercase letter often signals a double-sized version of that letter, as in the `aV` "adv-" prefix. (`ee` is written as such, though, being treated as a vowel combo rather than a double-sized `e`.)
    - `B` for the "falling" vertical `b`
    - `D` for the double-wide `td`/`dt`/`dd` blend
    - `M` for the `mb` blend
    - `N` for the double-wide `nm`/`mn`/`mm` blend
    - `V` for the `dv` blend (a `v` that is as wide as a `d`)
    - `Y` for the _-ing_ stroke.
- A `:` signals a diaresis - a sharp join in vowels rather than a smooth join, as in `fi:asco`, where an `i` then an `a` is written rather than an `ai` join.

<style>
p img, li img, td img {
  max-height: 3ex;
}
p img.tall, li img.tall, td img.tall {
  max-height: 5ex;
  vertical-align: middle;
}
</style>

## Example Entry

{% assign example = site.data.dictionary | where: "plaintext", "example entry" %}
{% for entry in example  %}
- **{{entry.plaintext}}** {% if entry.notes.length > 0 %}*{{entry.notes}}*{% endif %} {% for ex in entry.orthic %}
    - {{ ex.style }} style: ![{{ex.title}}]({{ ex.imagePath | prepend: site.baseurl }}){% if ex.tall %}{: .tall }{% endif %} `{{ ex.notation }}` (source: {{ ex.source }})
{% endfor -%}
{% endfor %}


## Dictionary

{% assign headword = '' %}
{% assign entries = site.data.dictionary | sort_natural: "plaintext" %}
{% for entry in entries  %}
{% if entry.plaintext == 'example entry' %}{% continue %}{% endif %}
{% assign maybe_headword = entry.plaintext | slice: 0, 1 | upcase %}
{% if headword != maybe_headword %}
{% assign headword = maybe_headword %}
### {{headword}}
{% endif %}
    - {{ ex.style }} style: ![{{ex.title}}]({{ ex.imagePath | prepend: site.baseurl }}){% if ex.tall %}{: .tall }{% endif %} `{{ ex.notation }}` (source: {{ ex.source }})
{% endfor -%}
{% endfor %}
