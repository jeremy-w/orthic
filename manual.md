---
layout: page
title: "A Manual of Orthographic Shorthand"
subtitle: "The Cambridge System"
author: "Hugh L. Callendar"
toc: true
toc_hmax: 6
---
# A Manual of Orthographic Shorthand: The Cambridge System

by Hugh L. Callendar, M.A., Fellow of Trinity College, Cambridge. 1891.

Rendered into Markdown by Jeremy W. Sherman based on [the version made available by Google Books](https://books.google.com/books/about/A_Manual_of_Orthographic_Cursive_Shortha.html?id=kQ5SAAAAYAAJ).

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This version of <span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Hugh L. Callendar's <em>A Manual of Orthographic Cursive Shorthand</em></span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://jeremy-w.github.io/orthic" property="cc:attributionName" rel="cc:attributionURL">Jeremy W. Sherman</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://books.google.com/books/about/A_Manual_of_Orthographic_Cursive_Shortha.html?id=kQ5SAAAAYAAJ" rel="dct:source">https://books.google.com/&#8203;books/&#8203;about/&#8203;A_Manual_of_&#8203;Orthographic_Cursive_&#8203;Shortha.html&#8203;?id=kQ5SAAAAYAAJ</a>.<br />Permissions beyond the scope of this license may be available at <a xmlns:cc="http://creativecommons.org/ns#" href="https://jeremywsherman.com/" rel="cc:morePermissions">https://jeremywsherman.com/</a>.

<style>
p img, li img, td img {
  max-height: 3ex
}
</style>

## Introductory Remarks
The present system is an adaptation of the alphabet and principles of Cursive Shorthand to the common orthography.

Two and a half years' experience in teaching Cursive has convinced me that the difficulties which beginners find in learning to spell correctly _by sound_ are much greater than I had previously imagined; and that it is unadvisable to attempt to introduce a _phonetic_ system of shorthand at an early stage in education.

I have every reason to believe that the present adaptation of Cursive to the common spelling will be found much more simple and easy to learn than any of the phonetic systems at present in vogue. There is very little to learn beyond an alphabet of 26 characters, and the method of joining them. In fact many students have succeeded in reading and writing the present system with nothing but the bare alphabet to guide them.

With the exception that the method of spelling adopted is orthographic instead of phonetic, no changes has been made in the fundamental principles of the system. These have been already discussed and explained in the introduction to the _[Manual of Cursive Shorthand](https://archive.org/details/manualofcursives00calliala)._ It is needless therefore to repeat them here.

The characters of the alphabet are for the most part the same as in Phonetic Cursive; but the change of spelling has made it necessary to rearrange some of them.

Advantage has been taken of this rearrangement to introduce several improvements in matters of detail, which have been suggested by the experience of teachers. The general style of the writing has been made even more flowing and lineal than before. The awkward backslope \ has been eliminated from the alphabet, and restricted to use in terminations, where it is comparatively harmless. [Jeremy: It's used for -ing.]

The writing requires no great niceties of penmanship. No distinction is made, as in other systems, between thin strokes and thick. Only two sizes of character are employed, instead of three or four. The vowel characters are connecting strokes joined in their natural order together with the consonants. The great majority of the signs are written on the ordinary slope of longhand, and the forms and distinctions between the characters are such as are already familiar to every one who has learnt to write in the ordinary style.

The system is strictly alphabetic. A letter is always represented by its alphabetic character. There are no alternative hooks and loops, or halving and doubling principles, to puzzle and distract the student. A word can be written in one way only. The rules are consequently very few, definite, and easy to apply.

In learning the system the student should work straight through the alphabet and following pages, writing and analysing every example as he comes to it. By the time he reaches [the end of the joining rules] he will thus have become thoroughly familiar with the alphabet. He will then be able to read through the specimen [of the fully-written style], every word of which is spelt in full.

## The Cursive Alphabet
{% capture assets -%}
{{ site.baseurl }}/assets/manual
{%- endcapture %}

<table>
<thead>
    <tr>
        <th>Letter</th>
        <th>Example</th>
    </tr>
</thead>
<tbody>
{% for row in site.data.manual.alphabet %}
<tr>
    <td>{{ row.letter }}<img src="{{ assets }}/{{ row.letter }}.png" /></td>
    <td>{% for word in row.examples -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;{{ word }}{% unless forloop.last %}, {% endunless %}
    {%- endfor %}</td>
</tr>
{% endfor %}
</tbody>
<tfoot>
<tr>
    <td colspan="2">
    The arrows show the directions in which the characters are written.
    </td>
</tr>
</tfoot>
</table>

### Doubled Letters
Doubled letters are shown, **not** by repeating the character, but by putting a dot below; thus, ![]({{ assets }}/odd.png)&nbsp;**odd**, ![]({{ assets }}/too.png)&nbsp;**too.**

**Exception:** ![]({{ assets }}/EE_arrow.png)&nbsp;**ee**; thus, ![]({{ assets }}/sleep.png)&nbsp;**sleep**, cp. ![]({{ assets }}/sup.png)&nbsp;**sup**.

## General Rules
### Orthographic Spelling
All words, when written in full, are spelt according to the common orthography. The characters are to be joined together smoothly, without lifting the pen, or making any unnecessary angles or breaks. All the more common and important joinings are fully explained and illustrated in ['How to Write and Join the Characters'](#how-to-write-and-join-the-characters).

### Diphthongs
When two vowels come together forming a 'diphthong', the angle between them is slurred or rounded off into a continuous curve; thus, ![]({{ assets }}/ai_angled.png)&nbsp;**ai** = ![]({{ assets }}/ai.png), ![]({{ assets }}/oy_angled.png)&nbsp;**oy** = ![]({{ assets }}/oy.png), ![]({{ assets }}/ou_angled.png)&nbsp;**ou** = ![]({{ assets }}/ou.png), ![]({{ assets }}/eau_angled.png)&nbsp;**eau** = ![]({{ assets }}/eau.png).

When, however, the vowels are separately sounded, either the characters are separated, or the angle between them is marked, as in the words {% assign words = 're-enter Oölite Deä create Leo fiasco serious fuel poem' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor -%}.

### The Two Sizes of Character
The two sizes of character must be carefully distinguished, just as [lowercase] 'c' and [uppercase] 'C', ![longhand lowercase E]({{ assets }}/longhand_E.png "longhand lowercase E") and ![longhand lowercase L]({{ assets }}/longhand_L.png "longhand lowercase L"), are distinguished in longhand. [Jeremy: Note that cursive lowercase L is basically a vertically stretched cursive lowercase E.] The first letter of a word is generally written so as to end on the line. The beginner should write between double-ruled lines at first, as in the following examples:

<figure>
<img src="{{ assets }}/TheTwoSizesOfCharacter.png" />
<figcaption>Characters written against both base and midline rules, first in alphabetical order, then in small/large groupings. Example words are provided at the end.</figcaption>
</figure>

[Jeremy: Here's a ready-to-print [double-ruled paper template for US letter paper]({{ site.baseurl }}/assets/paper/beginner's ruled paper (US letter).pdf).]

### Dividing a Word
A word may always be divided if it happens to be convenient. The necessity for this, however, very seldom arises except in the case of compound words. {% assign words = 'lawsuit Woolwich virgin' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor -%}.

### Punctuation
Punctuation is effected in the usual way, except the Hyphen&nbsp;<img src="{{ assets }}/Hyphen.png" />, and the Dash&nbsp;<img src="{{ assets }}/Dash.png" />. [Jeremy: They are the normal hyphen and dash, except a vertical stroke intersects each in the middle, like a plus sign. This distinguishes them from raised A ("and") and raised O ("though").]

### Initial Capitals
Initial capitals are marked thus <img src="{{ assets }}/InitialCapitalsMark.png" alt="using a long stroke falling from midline to baseline at 30 degrees from horizontal" title="initial capital stroke" />. {% assign words = 'Jack Clay S.E. L.S.W.R.' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor %}

## How to Write and Join the Characters
In the following alphabetic list are given examples and explanations of all the joinings which are likely to cause the beginner any difficulty.

> You can jump to a specific letter or significant joining:
>
{%- comment %}
Having a map with a single key per entry is kinda silly.
But YAML maps aren't necessarily ordered, so let's roll with it.
{% endcomment %}
{%- for map in site.data.manual.joins %}
{%- for letter in map %}
> - [{{ letter[0] }}](#{{letter[0]}}-join)
{%- for join in letter[1] %}
>   - [{{ join }}](#{{join | slugify}}-join)
{%- endfor %}
{%- endfor %}
{%- endfor %}

- <a id="A-join" />**A**&nbsp;![]({{ assets }}/A.png) is a short horizontal connecting stroke. It forms the diphthongs {% assign words = 'ai au ay_both' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word | slice: 0,2 }}**{% unless forloop.last %}, {% endunless %}
{%- endfor %}.
  - <a id="ay-join" />**Ay** may be curved either way. The form ![under-ay]({{ assets }}/ay_under.png "under-ay") is used whenever it joins more clearly or easily than the form ![over-ay]({{ assets }}/ay_over.png "over-ay"), as after {% assign words = 'D T J Qu M N V' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" alt="{{ word }}" title="{{ word }}" />
{%- endfor %} thus, {% assign words = 'days quay' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor %}; cp. {% assign words = 'says hay' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor %}.

- <a id="B-join" />**B**&nbsp;![]({{ assets }}/B.png) is written like the letter ![lowercase cursive b]({{ assets }}/longhand_b.png "lowercase cursive b"), but with a more open loop and without the hook upwards at the end. It forms the compounds:
{% for it in site.data.manual.compounds.b %}
  - <a id="{{it[0]}}-join" />{{ it[0] }}&nbsp;![]({{ assets }}/{{ it[0] }}.png) ![]({{ assets }}/{{ it[1] }}.png)&nbsp;{{ it[1] }}
{% endfor %}

- <a id="C-join" />**C**&nbsp;![]({{ assets }}/C.png) is written like the letter _c,_ but it is not turned up at the end, unless followed by _e._
  - <a id="ch-join" />**Ch**&nbsp;![]({{ assets }}/Ch.png) is written and joined exactly like the longhand letter _o_; thus, {% assign words = 'chair Christ ache' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor %}, cp. {% assign word = "ahead" %}<img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**.
  - Other compounds are:
{% for it in site.data.manual.compounds.c %}
    - <a id="{{it[0]}}-join" />{{ it[0] }}&nbsp;![]({{ assets }}/{{ it[0] }}.png) ![]({{ assets }}/{{ it[1] }}.png)&nbsp;{{ it[1] }}
{% endfor %}

- <a id="D-join" />**D**&nbsp;![]({{ assets }}/D.png) and ![]({{ assets }}/T.png)&nbsp;**t** have similar characters, but that for _d_ is made much flatter, and about three times as long. It forms the compounds:
{% for it in site.data.manual.compounds.d %}
  - <a id="{{it[0]}}-join" />{{ it[0] }}&nbsp;![]({{ assets }}/{{ it[0] }}.png)
  {%- for example in it offset: 1 %} ![]({{ assets }}/{{ example }}.png)&nbsp;{{ example }}
  {%- endfor -%}
{% endfor %}

  [Jeremy: The _Supplement_ published a year later suggests in ordinary style always omitting the D from the prefix ADJ-, which is probably why no example is given.]

- <a id="E-join" />**E**&nbsp;![]({{ assets }}/E.png) is a short upstroke; it must not be confused with ![]({{ assets }}/s_straight.png)&nbsp;**s**, which is written downwards.
  - <a id="ea-join" />**Ea**&nbsp;![ea, both over and under]({{ assets }}/ea_both.png) may be curved either way like _ay._ The form ![under-ea]({{ assets }}/ea_under.png "under-ea") is used except after {% assign words = 'M N P_noarrow S_noarrow Y B' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" alt="{{ word | slice: 0,1 }}" title="{{ word | slice: 0,1 }}" />
{%- endfor %}. An angle must always be made after ![over-ea]({{ assets }}/ea_over.png) before ![t]({{ assets }}/T.png "t")![d]({{ assets }}/D.png "d") or ![s]({{ assets }}/S_noarrow.png "s"); thus {% assign words = 'seat seas eat real pearl years' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor %}.
  - <a id="ee-join" />The diphthongs {% assign words = 'ee ei ie' | split: ' ' %}{% for word in words -%}
    **{{ word }}**&nbsp;<img src="{{ assets }}/{{ word }}.png" />{% unless forloop.last %}, {% endunless %}
{%- endfor %} are all written upwards much more steeply than _u._ ![]({{ assets }}/steep.png)&nbsp;**steep**, cp. ![]({{ assets }}/stupid.png)&nbsp;**stupid**. **eu**&nbsp;![]({{ assets }}/eu.png), **ew**&nbsp;![]({{ assets }}/ew.png) ![]({{ assets }}/new.png)&nbsp;**new**.

- <a id="F-join" />**F**&nbsp;![]({{ assets }}/F.png)
  - F is joined without an angle after vowels; thus, ![with i rounded out to flow straight into f]({{ assets }}/if.png)&nbsp;**if** (not ![stiff i, awkward corner, f]({{ assets }}/if_angled.png)).
  - It is joined to following characters like the longhand letter _s_; thus,
{% for it in site.data.manual.compounds.f %}
    - <a id="{{it[0]}}-join" />{{ it[0] }}&nbsp;![]({{ assets }}/{{ it[0] }}.png)
  {%- for example in it offset: 1 %} ![]({{ assets }}/{{ example }}.png)&nbsp;{{ example }}
  {%- endfor -%}
{% endfor %}

- <a id="G-join" />**G**&nbsp;![]({{ assets }}/G.png) is like the left-hand half of a capital _G._ It forms the compounds: <a id="gh-join" />
{% for it in site.data.manual.compounds.g %}
  - <a id="{{it[0]}}-join" />{{ it[0] }}&nbsp;![]({{ assets }}/{{ it[0] }}.png)
  {%- for example in it offset: 1 %} ![]({{ assets }}/{{ example }}.png)&nbsp;{{ example }}
  {%- endfor -%}
{% endfor %}

- <a id="H-join" />**H**&nbsp;![]({{ assets }}/H.png) is a large circle or backward loop beginning at the bottom. It is distinguished from ch&nbsp;![]({{ assets }}/Ch.png) by the way it is joined; thus,
{% assign words = "hat chat what which" | split: " " %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor %}

- <a id="I-join" />**I**&nbsp;![]({{ assets }}/I.png) is a short upstroke, like _e,_ but dotted.
  - <a id="ia-join" />**ia**&nbsp;![]({{ assets }}/ia_both.png) may be curved either way like _ea_; thus, ![]({{ assets }}/social.png)**social**, ![]({{ assets }}/optician.png)**optician**; ![]({{ assets }}/chief.png)**chief**.

- <a id="J-join" />**J**&nbsp;![]({{ assets }}/J.png) is like the letter _j,_ but is not dotted.

- <a id="K-join" />**K**&nbsp;![]({{ assets }}/K.png) is like ![]({{ assets }}/G.png)_g,_ but is turned the other way. It is joined in the same way as ![]({{ assets }}/F.png)**f.**

- <a id="L-join" />**L**&nbsp;![]({{ assets }}/L_initial_arrow.png) is a small circle or loop like ![]({{ assets }}/R.png)&nbsp;**r,** but is turned the opposite way, clockwise. [Jeremy: L leaps clockwise and hangs below, R runs in reverse and stands above.]
  - <a id="standalone-l-versus-r-join" />When standing by itself as an initial, ![]({{ assets }}/L_initial.png)&nbsp;**L** is distinguished from ![]({{ assets }}/R.png)&nbsp;**R** by prefixing a short hair-stroke showing the way it is turned.
  - <a id="joining-L-examples" />In other cases the distinction is obvious; cp.

    {% assign pairs = 'black bread,clay_lowercase crow,addle dry,flow fro,glad grade,play pray,little litre,slay Israël,held herd,world already' | split: ','-%}
    {%-for pair in pairs-%}
    {%-assign row = pair | split: ' '-%}
    ![]({{ assets }}/{{ row.first }}.png) | {{ row.first | split: "_" | first }} | ![]({{ assets }}/{{ row.last }}.png) | {{ row.last }}
    {% endfor %}
  - Other compounds are:
{% for it in site.data.manual.compounds.l %}
    - <a id="{{it[0]}}-join" />{{ it[0] }}&nbsp;![]({{ assets }}/{{ it[0] }}.png)
  {%- for example in it offset: 1 %} ![]({{ assets }}/{{ example }}.png)&nbsp;{{ example }}
  {%- endfor -%}
{% endfor %}

- <a id="M-join" />**M**&nbsp;![]({{ assets }}/M.png) is like ![]({{ assets }}/N.png)&nbsp;**n,** but much longer and flatter.
{% for it in site.data.manual.compounds.m %}
  - <a id="{{it[0]}}-join" />{{ it[0] }}&nbsp;![]({{ assets }}/{{ it[0] }}.png)
  {%- for example in it offset: 1 %} ![]({{ assets }}/{{ example }}.png)&nbsp;{{ example }}
  {%- endfor -%}
{% endfor %}

- <a id="N-join" />**N**&nbsp;![]({{ assets }}/N.png) is like the first hook of the letter _n._
  - No angle need be made in the compounds:
{% for it in site.data.manual.compounds.n_unangled %}
    - <a id="{{it[0]}}-join" />{{ it[0] }}&nbsp;![]({{ assets }}/{{ it[0] }}.png)
  {%- for example in it offset: 1 %} ![]({{ assets }}/{{ example }}.png)&nbsp;{{ example }}
  {%- endfor -%}
{% endfor %}
  - Other compounds are:
{% for it in site.data.manual.compounds.n %}
    - <a id="{{it[0]}}-join" />{{ it[0] }}&nbsp;![]({{ assets }}/{{ it[0] }}.png)
  {%- for example in it offset: 1 %} ![]({{ assets }}/{{ example }}.png)&nbsp;{{ example }}
  {%- endfor -%}
{% endfor %}

- <a id="O-join" />**O**&nbsp;![]({{ assets }}/O.png) is made about three times as long as ![]({{ assets }}/A.png)&nbsp;**a**.
  - <a id="oa-join" />**Oa** is distinguished from **o** by writing the ![]({{ assets }}/A.png)&nbsp;**a** above; thus, ![]({{ assets }}/oar.png)&nbsp;**oar**, cp. ![]({{ assets }}/or.png)&nbsp;**or**; ![]({{ assets }}/oak.png)&nbsp;**oak**.
  - Other compounds are:
{% for it in site.data.manual.compounds.o %}
    - <a id="{{it[0] | replace:"2",""}}-join" />{{ it[0] | replace:"2","" }}&nbsp;![]({{ assets }}/{{ it[0] }}.png)
  {%- for example in it offset: 1 %} ![]({{ assets }}/{{ example }}.png)&nbsp;{{ example }}
  {%- endfor -%}
{% endfor %}

- <a id="P-join" />**P**&nbsp;![]({{ assets }}/P.png) is a long downstroke, like the upper half of the stroke of the letter ![lowercase p in cursive longhand]({{ assets }}/p_longhand.png). It is made about three times as long as ![]({{ assets }}/S.png)&nbsp;**s**.
  - In joining ![]({{ assets }}/S.png)&nbsp;**s** before and after ![]({{ assets }}/P.png)&nbsp;**p**, the _s_-tick is sloped backwards; thus
{% for it in site.data.manual.compounds.p limit:2 %}
    - <a id="{{it[0]}}-join" />{{ it[0] }}&nbsp;![]({{ assets }}/{{ it[0] }}.png)
  {%- for example in it offset: 1 %} ![]({{ assets }}/{{ example }}.png)&nbsp;{{ example }}
  {%- endfor -%}
{% endfor %}
  - Other compounds are:
{% for it in site.data.manual.compounds.p offset:2 %}
    - <a id="{{it[0]}}-join" />{{ it[0] }}&nbsp;![]({{ assets }}/{{ it[0] }}.png)
  {%- for example in it offset: 1 %} ![]({{ assets }}/{{ example }}.png)&nbsp;{{ example }}
  {%- endfor -%}
{% endfor %}

- <a id="Q-join" />**Qu**&nbsp;![]({{ assets }}/Qu.png) is like the lower loop of the letter ![lowercase f in cursive longhand]({{ assets }}/f_longhand.png); it is turned the opposite way to ![]({{ assets }}/J.png)&nbsp;**j**. ![]({{ assets }}/esquire.png)&nbsp;**esquire**.

- <a id="R-join" />**R**&nbsp;![]({{ assets }}/R.png) is a small circle like ![]({{ assets }}/L.png)&nbsp;**L**, but is always turned the opposite way, like the loop of the longhand letter ![lowercase e in cursive longhand]({{ assets }}/e_longhand.png). [For examples, see L.](#joining-L-examples)
  - <a id="rce-join" />The compound ![]({{ assets }}/rce.png)&nbsp;**rce** is written like the ![initial lowercase e in cursive longhand]({{ assets }}/e_initial_longhand.png) form of the longhand letter _e_; thus, ![]({{ assets }}/fierce.png)&nbsp;**fierce**. [Jeremy: I've never seen this style of cursive _e_ used outside Callendar's own writing. It is like the uppercase cursive _E_ made like a mirrored, round 3, only it is written the height of a lowercase letter, and has an added leading hairstroke crossing above the midline to make the top circle of the _e._ The result is basically the counter-clockwise Orthic _r_ sitting atop a half-height Orthic _c_ with a rise at the end for the _e._]
  - Other compounds are:
{% for it in site.data.manual.compounds.r %}
    - <a id="{{it[0]}}-join" />{{ it[0] }}&nbsp;![]({{ assets }}/{{ it[0] }}.png)
  {%- for example in it offset: 1 %} ![]({{ assets }}/{{ example }}.png)&nbsp;{{ example }}
  {%- endfor -%}
{% endfor %}

- <a id="S-join" />**S**&nbsp;![]({{ assets }}/S.png) is a short downstroke like the tick at the beginning or end of a capital ![S]({{ assets }}/S_longhand.png).
  - <a id="standalone-s-versus-e-join" />When standing alone, as an initial, it is written straight down, thus ![a short, vertical stroke]({{ assets }}/s_straight.png), to distinguish it clearly from ![the short, forward-slanted stroke]({{ assets }}/E.png)&nbsp;**e**; cp. ![]({{ assets }}/S.E..png)&nbsp;**S.E.**
  - <a id="sh-sr-and-shr-join" />In the compound **Sh**&nbsp;![]({{ assets }}/sh.png) the _h_ circle is made smaller for neatness; **sh**&nbsp;![as in sha, where she a leaves from the middle of the s - "touch and reverse" - ]({{ assets }}/sha.png) is distinguished from **sr**&nbsp;![as in sra, where the a leaves from the bottom of the s - "spin around and continue" -]({{ assets }}/sra.png) by the way it is joined; thus; cp.
  {% assign words = "shed Tisri shred school" | split: " " %}{% for word in words -%}
    - ![]({{ assets }}/{{ word }}.png)&nbsp;**{{ word }}**
{%- endfor %}
  - Other compounds are:
{% for it in site.data.manual.compounds.s %}
    - <a id="{{it[0]}}-join" />{{ it[0] | replace:"2","" }}&nbsp;![]({{ assets }}/{{ it[0] }}.png)
  {%- for example in it offset: 1 %} ![]({{ assets }}/{{ example }}.png)&nbsp;{{ example }}
  {%- endfor -%}
{% endfor %}

- <a id="T-join" />**T**&nbsp;![]({{ assets }}/T.png) is like the hook at the end of the letter ![t]({{ assets }}/t_longhand.png).
  - <a id="th-join" />**Th**&nbsp;![]({{ assets }}/th.png) is written like the letter ![d]({{ assets }}/d_longhand.png). [Jeremy: That's a looped-through version of the _d_ Callendar often writes at the end of a word, as seen for example in "end"&nbsp;![]({{ assets }}/end_longhand.png). That word also shows the funky _e_ Callendar uses to explain how to write the compound _rce._]
  - <a id="word-final-th-join" />At the end of a word, the circle of the _h_ need not be completed; thus,
{% assign words = "with both" | split: " " %}{% for word in words %}
    - ![]({{ assets }}/{{ word }}.png)&nbsp;**{{ word }}**
{% endfor %}
  - Other compounds are:
{% for it in site.data.manual.compounds.t %}
    - <a id="{{it[0]}}-join" />{{ it[0] | replace:"2","" }}&nbsp;![]({{ assets }}/{{ it[0] }}.png)
  {%- for example in it offset: 1 %} ![]({{ assets }}/{{ example }}.png)&nbsp;{{ example }}
  {%- endfor -%}
{% endfor %}

- <a id="U-join" />**U**&nbsp;![]({{ assets }}/U.png) is a long up-stroke on a flat slope, making an angle of about ![]({{ assets }}/30_degrees.png) 30° with the line.
  - <a id="u-versus-ee-join" />**U**&nbsp;![]({{ assets }}/U.png) is distinguished from **ee**&nbsp;![]({{ assets }}/ee.png) by being written much less steeply; cp. ![]({{ assets }}/seen.png)&nbsp;**seen**, ![]({{ assets }}/sun.png)&nbsp;**sun**.
  - **Dipththongs**
{% for it in site.data.manual.compounds.u %}
    - <a id="{{it[0]}}-join" />{{ it[0] | replace:"2","" }}&nbsp;![]({{ assets }}/{{ it[0] }}.png)
  {%- for example in it offset: 1 %} ![]({{ assets }}/{{ example }}.png)&nbsp;{{ example }}
  {%- endfor -%}
{% endfor %}

- <a id="V-join" />**V**&nbsp;![]({{ assets }}/V.png) is distinguished from ![]({{ assets }}/ste.png)&nbsp;**ste** by its size; cp.
{% assign words = "minster Minver stew view" | split: " " %}{% for word in words %}
  - ![]({{ assets }}/{{ word }}.png)&nbsp;**{{ word }}**
{% endfor %}

- <a id="W-join" />**W**&nbsp;![]({{ assets }}/W.png) is an upward hook, which may be turned either way.
  - The first [clockwise] form is always used at the beginning of a word, except before **r**. Thus
{% assign words = "way woe wet" | split: " " %}{% for word in words %}
    - ![]({{ assets }}/{{ word }}.png)&nbsp;**{{ word }}**
{% endfor %}
    - cp. ![]({{ assets }}/write.png)&nbsp;**write**
  - <a id="wr-join" />**wr**&nbsp;![]({{ assets }}/wr.png) is distinguished from ![]({{ assets }}/th.png)&nbsp;**th** by its size.
  - <a id="wh-join" />**wh**&nbsp;![]({{ assets }}/wh.png) is made by enlarging the _w_ hook so as to look like the _h_- circle; cp. ![]({{ assets }}/who.png)&nbsp;**who**, ![]({{ assets }}/ha.png)&nbsp;**ha**.
  - <a id="word-final-ws-join" />**ws**&nbsp;![]({{ assets }}/ws.png); at the end of a word the addition of the _s_ tick to the _w_ hook forms a loop; thus
{% assign words = "sews cows laws" | split: " " %}{% for word in words %}
    - ![]({{ assets }}/{{ word }}.png)&nbsp;**{{ word }}**
{% endfor %}
  - Other compounds are:
{% for it in site.data.manual.compounds.w %}
    - <a id="{{it[0]}}-join" />{{ it[0] }}&nbsp;![]({{ assets }}/{{ it[0] }}.png)
  {%- for example in it offset: 1 %} ![]({{ assets }}/{{ example }}.png)&nbsp;{{ example }}
  {%- endfor -%}
{% endfor %}

- <a id="X-join" />**X**&nbsp;![]({{ assets }}/X.png)
  - No angle need be made in:
{% for it in site.data.manual.compounds.x %}
    - <a id="{{it[0]}}-join" />{{ it[0] | replace:"2","" }}&nbsp;![]({{ assets }}/{{ it[0] }}.png)
  {%- for example in it offset: 1 %} ![]({{ assets }}/{{ example }}.png)&nbsp;{{ example }}
  {%- endfor -%}
{% endfor %}

- <a id="Y-join" />**Y**&nbsp;![]({{ assets }}/Y.png)
{% assign words = "yacht yet yore yule" | split: " " %}{% for word in words %}
  - ![]({{ assets }}/{{ word }}.png)&nbsp;**{{ word }}**
{% endfor %}

- <a id="Z-join" />**Z**&nbsp;![]({{ assets }}/Z.png)
{% assign words = "daze Fitz puzzle" | split: " " %}{% for word in words %}
  - ![]({{ assets }}/{{ word }}.png)&nbsp;**{{ word }}**
{% endfor %}

## Specimen of Fully-Written Style
The preceding rules and examples will enable the student to read the (1) specimen of writing given on the opposite page, of which this page is a (2) key. Every word of this specimen is written in full letter for letter (3) just as it is here spelt. Nothing is left out. The small figures in (4) brackets show where each line of the shorthand ends, so that the stu-(5)dent may have no difficulty finding his place in the key, if (6) he happens to be at a loss to make out a word. (7)

The ability to write any word in full just as it is spelt, is (8) of the greatest value, especially for the correct spelling of proper (9) names and foreign words, which is often a serious matter, (10) and is quite impossible in any phonetic system. (11)

Even when thus written in full the system is very brief as contrasted (12) with ordinary writing. For practical purposes a still further increase (13) of brevity may be effected without any sacrifice of clearness, by (14) the use of shorter out-lines for such words as _and, the,_ (15) _for, to,_ etc., which occur so often in every page of English (16), and by the employment of a few other simple methods of (17) abbreviation, which are illustrated in the sections that follow, (18) and which constitute the ordinary style of Cursive.

[Jeremy: The specimen ends here.]

In the reporting style two new methods are introduced, namely 'expression by mode' and 'phraseography.'
These, together with the extension of the methods used in the ordinary style, combine to render the reporting style of Cursive as short, consistently with clearness, as any system of writing can possibly be made.
It is intended to treat this subject more fully in a future publication, but the methods are so simple that it has been thought worth while to include a short sketch of them in the present manual.
It is probable that the hints given in ["Hints for the Reporting Style"](#hints-for-the-reporting-style) will be sufficient to enable any intelligent student to apply them successfully for himself without further assistance.

<figure>
 <img src="{{ assets }}/FullyWrittenStyleSpecimen.png" />
 <figcaption>Specimen of fully-written style. See preceding text for key.</figcaption>
</figure>

## Ordinary Style
### Abbreviations
The following methods of abbreviation are used in correspondence and in ordinary writing.

#### Omit A and O before M and N
The vowels **a** and **o** are omitted before **m** and **n**, except initially and in rare words; thus, {% assign words = 'can or con,al(o)ne,w(o)m(a)n' | split: ',' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor -%}. An omission of this kind can always be corrected, if desired, by writing the omitted character above; thus, {% assign words = 'band bond' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor -%}.

#### Drop the dots
**Dots** are generally omitted in common words such as it, in, is, if, him, his, will. [Jeremy: Sic, without examples of the outlines in Orthic. Note this method includes omitting both dots above the letter i and dots below doubled letters. Both omissions are used in writing "will."]

#### Replace TH- with writing higher
Initial **Th** is omitted in all common words. The omission is shown by writing the rest of the word above the line; thus, {% assign words = 'the they this them tho’ that' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor -%}.
  - **Exception:** The character **a** <img src="{{ assets }}/a_raised.png" /> written above the line stands for the word **and.**

#### Let -Y stand unaltered
In adding inflections to words ending in **y,** the **y** is not changed to **i** or **ie**; thus, {% assign words = 'applyd trys easyst happyr' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor -%}.

#### Abbreviate common endings
Some common terminations are abbreviated as shown in the following list:

  - <a id="ed-ending" href="#ed-ending">**Ed.**</a> The _e_ may generally be omitted; thus,
{% assign words = "us’d kiss’d stirr’d" | split: " " %}{% for word in words %}
    - ![]({{ assets }}/{{ word }}.png)&nbsp;**{{ word }}**
{% endfor %}
  - <a id="ful-ending" href="#ful-ending">**Ful**</a> ![]({{ assets }}/ending_fl.png)&nbsp;**fl**
{% assign words = "useful beautyfully" | split: " " %}{% for word in words %}
    - ![]({{ assets }}/{{ word }}.png)&nbsp;**{{ word }}**
{% endfor %}
  - <a id="hood-ending" href="#hood-ending">**Hood**</a> ![]({{ assets }}/ending_hd.png)&nbsp;**hd**
{% assign words = "manhood" | split: " " %}{% for word in words %}
    - ![]({{ assets }}/{{ word }}.png)&nbsp;**{{ word }}**
{% endfor %}
  - <a id="ing-ending" href="#ing-ending">**Ing**</a> ![]({{ assets }}/ing_both.png)&nbsp;**ing**
{% assign words = "using saying seeming" | split: " " %}{% for word in words %}
    - ![]({{ assets }}/{{ word }}.png)&nbsp;**{{ word }}**
{% endfor %}
    - This form is used only for the inflection _-ing_ and not in such words as ![]({{ assets }}/king.png)&nbsp;**king**; cp. ![]({{ assets }}/sing.png)&nbsp;**sing**, ![]({{ assets }}/singing.png)&nbsp;**singing.**
    - It is better to curve the stroke, thus ![]({{ assets }}/ing_curved.png), after
{%- assign words = "d m n t v" | split: " " %}{% for word in words %}
      *{{word}},*{%comment%}![]({{ assets }}/{{ word }}ing.png){%endcomment%}
{%- endfor %} and vowels [here including *y* as in “scrying”].
{% for it in site.data.manual.endings %}
  - <a id="{{it.ending|slugify}}-ending" href="#{{it.ending|slugify}}-ending">**{{ it.ending }}**</a>&nbsp;![]({{ assets }}/ending_{{ it.orthic }}.png) **{{ it.orthic }}**
  {{- it.note | default:"" }}
  {% for word in it.examples %}
    - ![]({{ assets }}/{{ word }}.png)&nbsp;**{{ word }}**
  {%- endfor -%}
{% endfor %}

[J: Note that each links to itself, to aid in teaching fellow writers.]

### The General Method
The general method of abbreviating long words is to write only the first syllable, and, if necessary, to indicate the termination by writing the last letter or two, separated by a small interval from the first part; thus,

{% assign words = 'DIF.feren.T DIF.feren.CE ACK.nowledge ESP.eciall.Y CIR.cumstan.CE EXTR.aordinar.Y REP.resentati.VE' | split: ' ' %}{% for word in words -%}
{% assign image = word | remove:"." -%}
{% assign bit = word | downcase | split:"." %}
- <img src="{{ assets }}/{{ image }}.png" />&nbsp;**<u>{{ bit[0] }}</u>({{ bit[1] }})<u>{{ bit[2] }}</u>**
{% endfor %}

In many cases the termination may be joined, as in the last three examples.

### Phrases
Words may often be joined together provided that they are closely connected in sense. This applies especially to common words, auxiliaries, and particles, such as those contained in the list [of common words in the next section]: ex.&nbsp;gr.
{% assign words = 'able to do,as it is,I am not,I have had,I shall be very,to be,ought to have been,with a view to' | split: ',' %}{% for word in words -%}
- <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**
{% endfor %}

### Abbreviations for Common Words
The following is a list of the abbreviations for common words used in the corresponding style. Many of them are such as are commonly used in longhand. [J: Note that each links to itself, to aid in teaching fellow writers.]

{% for b in site.data.manual.briefs %}
{% assign word = b | remove:"(" | remove:")" | truncatewords:1,"" %}
  - <a id="{{word|slugify}}-brief" href="#{{word|slugify}}-brief">**{{ b }}**</a>&nbsp;![]({{ assets }}/b_{{ word }}.png)
{% endfor %}

## Specimens of the Ordinary Style
### The Introductory Remarks
<figure>
 <img src="{{ assets }}/OrdinaryStyleIntroPage1.png" />
 <img src="{{ assets }}/OrdinaryStyleIntroPage2.png" />
 <figcaption>Specimen of ordinary style. See introduction for key.</figcaption>
</figure>

#### Key
See the first section. :)

### From Macaulay's History
<figure>
 <img src="{{ assets }}/OrdinaryStyleMacaulayPage1.png" />
 <img src="{{ assets }}/OrdinaryStyleMacaulayPage2.png" />
 <figcaption>Specimen of ordinary style. See next section for key.</figcaption>
</figure>

#### Key
**The State of England in the Reign of Charles II.**

It is time that this description of the England which Charles the Second governed should draw to a close. Yet one subject of the highest moment still remains untouched. Nothing has yet been said of the great body of the people, of those who held the ploughs, who tended the oxen, who toiled at the looms of Norwich, and squared the Portland stone for St Paul's. Nor can very much be said. The most numerous class is precisely the class respecting which we have the most meagre information. In those times philanthropists did not yet regard it a sacred duty, not had demagogues yet found it a lucrative trade, to talk and write about the distress of the labourer. History was too much occupied with the Courts and camps to spare a line for the hut of the peasant, or the garret of the mechanic. The press now often sends forth in a day a greater quantity of discussion and declamation about the condition of the working man than was published during the twenty-eight years which elapsed between the Restoration and the Revolution. But it would be a great error to infer from the increase of complaint that there has been any increase of misery.

The great criterion of the state of the common people is the amount of their wages; and as four-fifths of the common people were, in the seventeenth century, employed in agriculture, it is especially important to ascertain what were then the wages of the agricultural **[Page 2]** industry. On this subject we have the means of arriving at conclusions sufficiently exact for our purpose.

It seems clear that the wages of labour, estimated in money, were, in 1685, not more than half of what they now are; and there were few articles important to the working man of which the price was not, in 1685, more than half of what it now is. Beer was undoubtedly much cheaper in that age than at present. Meat was also cheaper, but was still so dear that hundreds of thousands of families scarcely knew the taste of it. In the cost of wheat there has been very little change. The average price of the quarter, during the last 12 years of Charles the Second, was fifty shillings. Bread, therefore, such as is now given to the inmates of a workhouse, was then seldom seen, even on the trencher of a yeoman or of a shopkeeper. The great majority of the nation lived entirely on rye, barley, and oats.

The produce of tropical countries, of mines, and of machinery, was positively dearer than at present. Among the commodities for which the labourer would have had to pay higher in 1685 than his posterity now pay, were sugar, salt, coals, candles, soap, shoes, stockings, and generally all articles of clothing and all articles of bedding. It may be added, that the old coats and blankets would have been, not only more costly, but less serviceable, than the modern fabrics.

### St John II
<figure>
 <img src="{{ assets }}/OrdinaryStyleStJohnPage1.png" />
 <figcaption>John 2:1–13, KJV.</figcaption>
</figure>

<figure>
 <img src="{{ assets }}/OrdinaryStyleStJohnPage2.png" />
 <figcaption>John 2:14–25, 3:1–2, KJV.</figcaption>
</figure>

[For the [Key to the John II passage](https://holybible.com/jhn.2.1), see any copy of the King James Version of the Bible.]

## Application to Foreign Languages
Owing to the peculiar character of the vowel system and the facility with which the characters can be joined, the alphabet of Orthographic Cursive is immediately applicable with very slight modifications to almost all foreign languages. It is impossible here to work out the subject fully, but the following specimens will be of interest as shewing the capabilities of the system. They are written almost in full, containing only one or two trifling abbreviations, such as _-mt_ for _-ment,_ analogous to those used in the ordinary style of English.

### French
#### Adaptations
- English **y** is used to write French **é**&nbsp;![]({{ assets }}/Y.png).
- Both forms of English **-ing** are used instead to write French **ée**&nbsp;![]({{ assets }}/ing_both.png).

#### Specimen
<figure>
 <img src="{{ assets }}/FrenchSpecimen.png" />
 <figcaption>Specimen of French. The blue highlight marks an example of how the grave accent is written by crossing the outline.</figcaption>
</figure>

#### Key
<p lang="fr">De tous les systèmes de gouvernement et de garanties politiques, à coup sûr le plus difficile à établir, à faire prévaloir, c’est le système fédératif&#8239;; ce système qui consiste à laisser dans chaque localité, dans chaque société particulière, toute la portion de gouvernement qui peut y rester, et à ne lui enlever que la portion indispensable au maintien de la société générale, pour la porter au centre de cette même société, et l’y constituer sous la forme de gouvernement centrale.</p>
### Spanish
_This Spanish adaptation is [thanks to Medape](https://www.reddit.com/r/orthic/comments/15zcl1l/orthic_adaptation_to_spanish/). It is new as of 2023 and was not included in the original 1891 text._

#### Adaptations
- **ñ**: English **straight -ing** is used to write Spanish **ñ**&nbsp;![]({{assets}}/ing_straight.png). The curved -ing is unused.
  - **Straight -ing** may also be used to replace any inconvenient symbols, such as a currency symbol in a price list or the commercial at sign **@** in a word such as _<span lang="es">bienvenid@s</span>_.
- **ll**: The **L** used in initials, with an entering hairline stroke, is used for word-initial **LL**&nbsp;![]({{assets}}/L_initial.png) to avoid having to dot a plain **L**.
- **silent U**: Omit silent **U**s, as in _<span lang="es">gue, gui, que, qui</span>_.
- **accents**:
  - The acute accent can be written as an apostrophe over the affected letter.
  - An optional stroke through a letter represents any diacritic or modification other than an acute accent: _Ü, Ç, À, È, Ò, Ł,_ etc.
- **de**: A raised dot, used in English to notate _be_, instead represents _<span lang="es">de</span>_. In collocations like _<span lang="es">de la</span>_, only the second word is written, above the line.
- **a/o omission**: The [**a**/**o**-omission rule](#omit-a-and-o-before-m-and-n) before **m**/**n** is extended to include **ñ**, but restricted to **a**/**o** following a letter other than **a e i o u**.

#### Longhand Abbreviations
- As usual, longhand abbreviations can be brought over, but replace dots or superscripting with mode 2. If you must, you may write a mid-dot before the superscripted portion.
  - Dots: <code><span lang="es">q.e.p.d</span></code> _<span lang="es">q. e. p. d. (que en paz descanse)</span>_
  - Superscripting: <code><span lang="es">1.a</span></code> _<span lang="es">1.<sup>a</sup> (primera)</span>_,
      <code><span lang="es">v.os</span></code> _<span lang="es">V.<sup>os</sup></span>_.
- Slashed longhand abbreviations can be written with a horizontal line through the Orthic,
  or treated like dots: <code><span lang="es">c.u</span></code> _<span lang="es">c/u (cada unidad)</span>_

#### Specimen
<figure>
  <img src="{{ assets }}/spanish-full-style-specimen.png" />
  <figcaption>Specimen of Spanish, in the fully-written style.</figcaption>
</figure>

Most accent marks and a few dots over the letter I were omitted, even in this
fully-written style. Note that the proper name Gaudí is written as `gaudi'`
(stacking the accent mark and the dotted I), and that a strike through the
vowel is used for for Ü, Î and À.

#### Key
<p lang="es">Güell y Gaudí tenían en mente un proyecto al estilo de las ciudades-jardín inglesas —lo que queda manifiesto en la ortografía inicial Park Güell—, conforme a las teorías de Ebenezer Howard, que habían sido introducidas a principios del siglo xx por Cebrià de Montoliu a través de la revista Civitas (1911-1919).
El conde Güell tenía experiencia con la organización laboral inglesa, como se vio reflejado en su proyecto de ciudad obrera de la Colonia Güell, en Santa Coloma de Cervelló. Sin embargo, en esta ocasión el objetivo era el de una urbanización destinada a la burguesía. Asimismo, Güell se inspiró para las zonas ajardinadas en el jardín de la Fontaine de la ciudad de Nîmes, donde vivió en su juventud.</p>

_This is paragraph 6 of section <span lang="es">"Historia"</span>
of the Wikipedia article on
[<span lang="es">Parque Güell</span>](https://es.m.wikipedia.org/w/index.php?title=Parque_Güell&oldid=152524644#Historia),
specifically, the version saved on 18:53 17 July 2023 by Wikimedia user Canaan._


### German
#### Adaptations
- English **g** and **c** are swapped, giving German **g**&nbsp;![]({{ assets }}/C.png) and **c**&nbsp;![]({{ assets }}/G.png).
- English **sh** becomes German **sch**&nbsp;![]({{ assets }}/sh.png).
- English **under-ea** becomes German **ei**&nbsp;![]({{ assets }}/ea_under.png).
- English **-ing** becomes German **-ung**&nbsp;![]({{ assets }}/ing_both.png).
- German omits **h**&nbsp;![]({{ assets }}/H.png) both after vowels and after **t**.

#### Specimen
<figure>
 <img src="{{ assets }}/GermanSpecimen.png" />
 <figcaption>Specimen of German</figcaption>
</figure>

#### Key
<p lang="de">Die anziehende Kraft des geriebenen Bernsteins war bereits im Alterthume bekannt, jedoch ohne dass derselben weiter nachgeforscht wurde. Sie wurde gewöhnlich in Gemeinschaft mit der Anziehung des Magnetsteins gekannt, und von dieser nicht unterschieden. Die gleiche Eigenschaft wie beim Bernstein war später noch an einer bituminösen Steinkohle (Gagat) wahrgenommen worden.</p>

<p lang="de">Der Erste, welcher die Anziehung des geriebenen Bernsteins von der des Magnetsteins mit Bestimmtheit unterschied, und sie mit dem von der griechischen Benennung des Bernsteins (<em lang="grc">ἤλεκτρον</em>) entlehnten Namen bezeichnete, war W. Gilbert (um 1600). Er fand, dass Edelsteine, Glas, Harz, Schwefel, u.&#8239;s.&#8239;w., nach dem Reiben…</p>

### Danish
_This Danish adaptation is [thanks to Jacob Moen](https://www.reddit.com/r/orthic/comments/f3fl34/danish_orthic/fhienrf). It is new as of 2020 and was not included in the original 1891 text._

#### Adaptations
- _å_ is an _a_ with a floating apostrophe over the middle.
- _ø_ is a crossed _o._
- _æ_ is a crossed _a_.
- Raising is used for the _j_ in _jeg:_
  - `^eg` for _jeg_
- Raising is used for the _de-_ prefix, analogously to its use for _th_ in the English _the,_ thus:
  - `^n` for _den_
  - `^r` for _der_
  - `^t` for _det_

#### Specimen
<figure>
 <img src="{{ assets }}/DanishSpecimen.jpg" />
 <figcaption>Specimen of Danish</figcaption>
</figure>

#### Key
<p lang="dk">Allerede i min barndom, omkring 8-9 års alderen, kunne jeg tegne nogenlunde hæderligt. Jeg tror, jeg hørte til den lille gruppe af børn, som helt tilfældigt lærer at se på den måde, der sætter en i stand til at tegne. Jeg kan stadigvæk huske, at jeg sagde til mig selv, også som ganske lille, at hvis jeg ville tegne noget, måtte jeg først gøre "det".</p>

From the Danish translation of Betty Edwards' _Drawing on the Right Side of the Brain._
Note that _a_ and _o_ could have been omitted before _n_ and _m_ much more often than they were in this specimen.

### Italian
#### Adaptations
- Final _o_ is omitted after consonants.

#### Specimen
<figure>
 <img src="{{ assets }}/ItalianSpecimen.png" />
 <figcaption>Specimen of Italian</figcaption>
</figure>

#### Key
<p lang="it">L’historia si puo veramente deffinire una guerra illustre contro il Tempo, perchè togliendoli di mano gl’anni suoi prigioneri, anzi già fatti cadaveri, li richiama in vita, li passa in rassegna, e li schiera di nuovo in battaglia. Ma gl’illustri Campioni che in tal Arringo fanno messe di Palme e d’Allori, rapiscono solo che le sole spoglie più sfarzose e brillanti, imbalsamando co’ loro inchiostri le Imprese de’ Principi e Potentati, e qualificati Personaggi, e trapontando coll’ ago finissimo dell’ ingegno i fili d’oro e di seta, che formano un perpetuo ricamo di Attioni gloriose. —<em>I Promessi Sposi,</em> <span lang="en">Introduction</span>.</p>

### Latin
#### Adaptations
- Final **um**&nbsp;![]({{ assets }}/Y.png) is written with English **y.**

#### Specimen
<figure>
 <img src="{{ assets }}/LatinSpecimen.png" />
 <figcaption>Specimen of Latin. Note the end-of-line hyphens in _tribu-norum_ and _dom-inatio_ used to mark that the word continues on the next line.</figcaption>
</figure>

#### Key
<p lang="la">Urbem Romam a principio reges habuere. Libertarem et consulatum L. Brutus instituit. Dictaturae ad tempus sumebantur. Neque decemviralis potestas ultra biennium, neque tribunorum militum consulare jus diu valuit. Non Cinnae, non Sullae longa dominatio; et Pompeii Crassique potentia cito in Caesarem, Lepidi atque Antonii arma in Augustum cessere, qui cuncta, discordiis civilibus fessa, nomine Principis sub imperium accepit. —Tacitus, <em lang="en">Annals,</em> I.1.</p>

### Greek
#### Adaptations
- English **y** becomes Greek **η**&nbsp;![]({{ assets }}/Y.png).
- English straight **ing** becomes Greek **ω**&nbsp;![]({{ assets }}/ing_straight.png)

[Jeremy: That covers adapting Orthic to Greek. As for adapting Greek to Orthic, it appears that Callendar decided:

- _Spiritus lenis_ is unmarked.
- _Spiritus asper_ is marked by writing an English **h**&nbsp;![]({{ assets }}/H.png).
- All tone marks are omitted.

I guess that makes this an atonic Greek orthography. I expect diaeresis would be indicated by an angle joining, as discussed in ["Diphthongs."](#diphthongs)]

#### Specimen
<figure>
 <img src="{{ assets }}/GreekSpecimen.png" />
 <figcaption>Specimen of Greek</figcaption>
</figure>

#### Key
<p lang="grc">Ἐπειδήπερ πολλοὶ ἐπεχείρησαν ἀνατάξασθαι διήγεσιν περὶ τῶν πεληροφορημένων ἐν ἡμῖν πραγμάτων, καθὼς παρέδοσαν ἡμῖν οἱ ἀπ’ ἀρχῆς αὐτόπται καὶ ὑμηρέται γενόμενοι τοῦ λόγου, ἔδοξε κἀμοὶ παρηκολουθηκότι ἄνωθεν πᾶσιν ἀκριβῶς καθεξῆς σοὶ γράψαι, κράτιστε θεόφιλε. <span lang="en">—St Luke I.1–3.</span></p>
<!-- thanks http://www.typegreek.com/ -->

## Hints for the Reporting Style

<figure>
 <img src="{{ assets }}/ReportingHintsPage1.png" />
 <img src="{{ assets }}/ReportingHintsPage2.png" />
 <figcaption>Hints for the reporting style. See next section for key.</figcaption>
</figure>

### Key to Hints
_Jeremy: This section is an original addition of this work. The images have a dot at the start of every fifth line to help you jump back and forth between the shorthand and this key._

_The original text provided no key for these hints. If you wanted to learn the reporting style from the manual, you needed to learn to read ordinary style first._

The reporting style differs from the ordinary style only in the more extensive use of (2) abbreviation and phrasing.

Words are abbreviated as in longhand by the application (3) of the general principle given in §10.
This method is so simple that with a little (4) practice any reporter can easily extemporise suitable abbreviations for himself, according to the (5) context of the subject upon which he is engaged. In order however to secure the greatest possible (6) uniformity of style among writers of-the system, it’s intended shortly to publish (7) a standard list of abbreviations for common words in the form of a vocabulary.

(8) It’s impossible to treat the subject of reporting
adequately in the present publication, (9) but we will proceed to give a few hints which will be of use to students. (10)

1. In abbreviating a common word it’s generally sufficient to write the first 2 (11) or 3 letters of the termination, but terminations and inflexions which are evidently required (12) by the context may be omitted.
   Mere initials may be largely used for repeated names (13) and titles.
   Examples

   - s = sir,
   - l = lord,
   - p = page,
   - q = question,
   - pr = principle,
   - rep = (14) represent,
   - imp = important,
   - fou = found,
   - ea = each,
   - mu = much.

   (15) In the case of short words it’s often better to join the last letter;

   - pt = part,
   - (16) sht = short,
   - tn = town,
   - ler = letter,
   - ld = world,
   - ming = morning.

   (17) Letters which are weakly sounded, such as GH in STRAIT = straight, may often be left (18) out in abbreviating; initial H in such words as HIM HAS HAD especially in (19) phrases and compounds;

   - chas = which has,
   - shtnd = shorthand,
   - chil = which will.

2. (1) <a id="slurring" />SLURRING. This method of abbreviation is largely used in Gurney’s and in the (2) script systems which are universally employed in Germany.
   In hurried writing it is not (3) always possible to preserve the exact forms of-the characters, but it’s important to keep as far as (4) possible THE GENERAL OUTLINE of a word.
   Examples of common slurs are:

   - (5) double-width D = DD or TD,
   - deep double-width D = DV,
   - UUN = USION or UTION. (6)

   The larger and more characteristic signs should be retained, but the smaller signs such as L R (7) may be slurred; examples

   - expeec = experience,
   - beev = believe,
   - aso = also,
   - gt (8) = grt,
   - mter = matter,
   - eduun = education,
   - nstuun = institution. (9)

3. <a id="modes" />MODES. If the larger signs are omitted in abbreviating, their omission should (10) be indicated by mode, that is by bringing the outline and writing the termination close (11) to the first part of-the word.

   - The omission of B P or V is indicated by (12) mode I, that is by writing the termination above; thus

     - which<sup>r</sup> = whichever,
     - g<sup>n</sup> = given.

   - (13) The omission of G K J or QU is shown by writing the termination below, called (14) mode III; thus

     - s<sub>n</sub> = sign,
     - s<sub>t</sub> = sight,
     - t<sub>n</sub> = taken,
     - wa<sub>.</sub> = wage,
     - wa<sub>s</sub> = wages

   - (15) The omission of other characters and syllables may be shown by mode II, that is by (16) writing the termination on the same level; thus

     - dif-ce = difference,
     - a-plish = accomplish.

     (17) Some common words and prefixes, especially _b_ and _con_ or _com,_ may (18) also be expressed by modes, but this method must be applied with caution; --

     - (19) un-n = uncommon,
     - i-c<sup>.</sup> = i-c(o)nceive,
     - isha<sup>.</sup> = ishabe (i shall be),
     - chas<sup>n</sup> = (whi)ch has b(ee)n,
     - (20) <sup>yd</sup> = bey(on)d,
     - <sup>f</sup> = before,
     - <sup>ter</sup> = better,
     - <sup>n<sup>lnt</sup></sup> = benevolent,
     - f<sup>ry</sup> = for every.

#### [Modal vs position writing]
[Jeremy: 'Benevolent' demonstrates how indication by mode differs from the fixed positions used in Pitman's shorthand. While Pitman's positions are relative to the _line,_ Orthic's modes are relative to the _preceding character._ Thus a raised _n_ implies the prefix _be-,_ and then an _lnt_ raised relative to that _n_ implies the _v._]

### Specimen (Moderately Abbreviated)

<figure>
 <img src="{{ assets }}/ReportingSpecimen.png" />
 <figcaption>Specimen of a moderately abbreviated reporting style. See next section for key.</figcaption>
</figure>

#### Key
**Local Government.**

I agree with Sir Charles Dilke in attributing the utmost importance to the question of local government in the future.
I agree with him in the estimate which he has formed of the high place that question will occupy in the programme of the Liberal party.
Experience justifies us in the hope that the Reformed Parliament will do much in the direction of completing the work which previous Reformed Parliaments have commenced.
What was the main and the material advantage which resulted from the Reform Bill of 1832?
It was the concession of municipal government to our country towns — a concession which has been highly appreciated, and which has been wisely used, and which has added most materially to the comfort and the happiness of the populations concerned.
And what was the greatest result of the Reform of 1867?
It was the extension of the functions of local governments by the creation of a system of education national in its scope, but locally administered.
And it remains for the Reformed Parliament which will meet in 1886 to complete this work and to carry it further.
I can conceive of no nobler and no more congenial task for those who represent the whole people than that of extending to the counties and to the metropolis and to the sister kingdom the liberties and the institutions which have conferred so great a benefit upon us the provinces.
Gentlemen, local government is important altogether beyond its usefulness.
It is the best political education, and I am convinced that the welfare and the contentment of the whole population can only be secured in proportion as the whole population are called in to take a part and a share in the obligations and the responsibilities of government.
But, the extension of municipal institutions is not all that we have to do in the way of local government.
We have in the future to elevate our conception of the meaning of the word.
It is not merely a parochial and municipal, it is not even merely a provincial question, it is a national question also.
What are the great problems of the future?
We have to deal with obstruction in the House of Commons.
We have to deal with the system under which the greatest legislative assemblage in the world has begun to lose its usefulness, and in consequence lose its influence.
And that result can never be accomplished as long as the Imperial Parliament is burdened with an ever increasing amount of petty detail with which it is incompetent to deal, and which ought to be referred to other bodies.

What are the two greatest and most pressing needs of our time?
I think most men would say the provision of healthy decent dwellings in our large towns at fair rents, and in the country facilities for the labourer to obtain a small plot of land which he may be able to work.
