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
- An uppercase letter signals a double-sized version of that letter, as in the `aD` "adv-" prefix. (`ee` is written as such, though, being treated as a vowel combo rather than a double-sized `e`.)
    - A `Y` is used for the -ing stroke.
- A `:` signals a diaresis - a sharp join in vowels rather than a smooth join, as in `fi:asco`, where an `i` then an `a` is written rather than an `ai` join.

## Dictionary

{% for entry in site.data.dictionary %}
- **{{entry.plaintext}}** {% if entry.notes.length > 0 %}*{{entry.notes}}*{% endif %} {% for ex in entry.orthic %}
    - {{ ex.style }} style: ![{{ex.title}}]({{ ex.imagePath | prepend: site.baseurl }}) `{{ ex.notation }}` (source: {{ ex.source }})
{% endfor -%}
{% endfor %}
