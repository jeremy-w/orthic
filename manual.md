---
layout: page
title: "A Manual of Orthographic Shorthand"
subtitle: "The Cambridge System"
author: "Hugh L. Callendar"
toc: true
---
# A Manual of Orthographic Shorthand
_The Cambridge System_
by Hugh L. Callendar, M.A., Fellow of Trinity College, Cambridge. 1891.

Rendered into Markdown by Jeremy W. Sherman based on [the version made available by Google Books](https://books.google.com/books/about/A_Manual_of_Orthographic_Cursive_Shortha.html?id=kQ5SAAAAYAAJ).

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This version of <span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Hugh L. Callendar's <em>A Manual of Orthographic Cursive Shorthand</em></span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://jeremy-w.github.io/orthic" property="cc:attributionName" rel="cc:attributionURL">Jeremy W. Sherman</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://books.google.com/books/about/A_Manual_of_Orthographic_Cursive_Shortha.html?id=kQ5SAAAAYAAJ" rel="dct:source">https://books.google.com/books/about/A_Manual_of_Orthographic_Cursive_Shortha.html?id=kQ5SAAAAYAAJ</a>.<br />Permissions beyond the scope of this license may be available at <a xmlns:cc="http://creativecommons.org/ns#" href="https://jeremywsherman.com/" rel="cc:morePermissions">https://jeremywsherman.com/</a>.

## Introductory Remarks
The present system is an adaptation of the alphabet and principles of Cursive Shorthand to the common orthography.

Two and a half years' experience in teaching Cursive has convinced me that the difficulties which beginners find in learning to spell correctly _by sound_ are much greater than I had previously imagined; and that it is unadvisable to attempt to introduce a _phonetic_ system of shorthand at an early stage in education.

I have every reason to believe that the present adaptation of Cursive to the common spelling will be found much more simple and easy to learn than any of the phonetic systems at present in vogue. There is very little to learn beyond an alphabet of 26 characters, and the method of joining them. In fact many students have succeeded in reading and writing the present system with nothing but the bare alphabet to guide them.

With the exception that the method of spelling adopted is orthographic instead of phonetic, no changes has been made in the fundamental principles of the system. These have been already discussed and explained in the introduction to the _[Manual of Cursive Shorthand](https://archive.org/details/manualofcursives00calliala)._ It is needless therefore to repeat them here.

The characters of the alphabet are for the most part the same as in Phonetic Cursive; but the change of spelling has made it necessary to rearrange some of them.

Advantage has been taken of this rearrangement to introduce several improvements in matters of detail, which have been suggested by the experience of teachers. The general style of the writing has been made even more flowing and lineal than before. The awkward backslope \ has been eliminated from the alphabet, and restricted to use in terminations, where it is comparatively harmless. [Jeremy: It's used for -ing.]

The writing requires no great niceties of penmanship. No distinction is made, as in other systems, between thin strokes and thick. Only two sizes of character are employed, instead of three or four. The vowel characters are connecting strokes joined in their natural order together with the consonants. The great majority of the signs are written on the ordinary slope of longhand, and the forms and distinctions between the characters are such as are already familiar to every one who has learnt to write in the ordinary style.

The system is strictly alphabetic. A letter is always represented by its alphabetic character. There are no alternative hooks and loops, or halving and doubling principles, to puzzle and distract the student. A word can be written in one way only. The rules are consequently very few, definite, and easy to apply.

In learning the system the student should work straight through the alphabet and following pages, writing and analysing every example as he comes to it. By the time he reaches [the end of the joining rules] he will thus have become thoroughly familiar with the alphabet. He will the be able to read through the specimen [of the fully-written style], in which every word is spelt in full.

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
    <img src="{{ assets }}/{{ word }}.png" /> {{ word }}{% unless forloop.last %}, {% endunless %}
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
Doubled letters are shown, **not** by repeating the character, but by putting a dot below; thus, ![]({{ assets }}/odd.png) **odd**, ![]({{ assets }}/too.png) **too.**

**Exception:** ![]({{ assets }}/EE.png) **ee**; thus, ![]({{ assets }}/sleep.png) **sleep**, cp. ![]({{ assets }}/sup.png) **sup**.

## General Rules
### Orthographic Spelling
All words, when written in full, are spelt according to the common orthography. The characters are to be joined together smoothly, without lifting the pen, or making any unnecessary angles or breaks. All the more common and important joinings are fully explained and illustrated in ["How to Write and Join the Characters"].

### Diphthongs
When two vowels come together forming a 'diphthong', the angle between them is slurred or rounded off into a continuous curve; thus, ![]({{ assets }}/ai_angled.png) **ai** = ![]({{ assets }}/ai.png), ![]({{ assets }}/oy_angled.png) **oy** = ![]({{ assets }}/oy.png), ![]({{ assets }}/ou_angled.png) **ou** = ![]({{ assets }}/ou.png), ![]({{ assets }}/eau_angled.png) **eau** = ![]({{ assets }}/eau.png).

When, however, the vowels are separately sounded, either the characters are separated, or the angle between them is marked, as in the words {% assign words = 're-enter Oölite Deä create Leo fiasco serious fuel poem' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" /> **{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor -%}.

### The Two Sizes of Character
The two sizes of character must be carefully distinguished, just as 'C' and 'c', 'e' and 'l', are distinguished in longhand. [FIXME: Need a script-like font to make the e vs l hit home. But note that cursive l is basically a vertically stretched cursive e.] The first letter of a word is generally written so as to end on the line. The beginner should write between double-ruled lines at first, as in the following examples:

<figure>
<img src="{{ assets }}/TheTwoSizesOfCharacter.png" />
<figcaption>Characters written against both base and midline rules, first in alphabetical order, then in small/large groupings. Example words are provided at the end.</figcaption>
</figure>

### Dividing a Word
A word may always be divided if it happens to be convenient. The necessity for this, however, very seldom arises except in the case of compound words. {% assign words = 'lawsuit Woolwich virgin' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" /> **{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor -%}.

### Punctuation
Punctuation is effected in the usual way, except the Hyphen <img src="{{ assets }}/Hyphen.png" />, and the Dash <img src="{{ assets }}/Dash.png" />. [Jeremy: They are the normal hyphen and dash, except a vertical stroke intersects each in the middle, like a plus sign. This distinguishes them from raised A ("and") and raised O ("though").]

### Initial Capitals
Initial capitals are marked thus <img src="{{ assets }}/InitialCapitalMark.png" />. {% assign words = 'Jack Clay S.E. L.S.W.R.' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" /> **{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor %}

## How to Write and Join the Characters
In the following alphabetic list are given examples and explanations of all the joinings which are likely to cause the beginner any difficulty.

[TODO: Lots of text. Unclear how best to render it.]

## Specimen of Fully-Written Style
The preceding rules and examples will enable the student to read the (1) specimen of writing given on the opposite page, of which this page is a (2) key. Every word of this specimen is written in full letter for letter (3) just ad it is here spelt. Nothing is left out. The small figures in (4) brackets show where each line of the shorthand ends, so that the stu-(5)dent may have no difficulty finding his place in the key, if (6) he happens to be at a loss to make out a word. (7)

The ability to write any word in full just as it is spelt, is (8) of the greatest value, especially for the correct spelling of proper (9) names and foreign words, which is often a serious matter, (10) and is quite impossible in any phonetic system. (11)

Even when thus written in full the system is very brief as contrasted (12) with ordinary writing. For practical purposes a still further increase (13) of brevity may be effected without any sacrifice of clearness, by (14) the use of shorter out-lines for such words as _and, the,_ (15) _for, to,_ etc., which occur so often in every page of English (16), and by the employment of a few other simple methods of (17) abbreviation, which are illustrated in the sections that follow, (18) and which constitute the ordinary style of Cursive.

[Jeremy: The specimen ends here.]

In the reporting style two new methods are introduced, namely 'expression by mode' and 'phraseography.' These, together with the extension of the methods used in the ordinary style, combine to render the reporting style of Cursive as short, consistently with clearness, as any system of writing can possibly be made. It is intended to treat this subject more fully in a future publication, but the methods are so simple that it has been thought worth while to include a short sketch of them in the present manual. It is probable that the hints given in ["Hints for the Ordinary Style"] will be sufficient to enable any intelligent student to apply them successfully for himself without further assistance.

<figure>
 <img src="{{ assets }}/FullyWrittenStyleSpecimen.png" />
 <figcaption>Specimen of fully-written style. See preceding text for key.</figcaption>
</figure>

## Ordinary Style
### Abbreviations
The following methods of abbreviation are used in correspondence and in ordinary writing.

a. The vowels **a** and **o** are omitted before **m** and **n**, except initially and in rare words; thus, {% assign words = 'can or con,al(o)ne,w(o)m(a)n' | split: ',' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" /> **{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor -%}. An omission of this kind can always be corrected, if desired, by writing the omitted character above; thus, {% assign words = 'band bond' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" /> **{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor -%}.
b. **Dots** are generally omitted in common words such as it, in, is, if, him, his, will. [Jeremy: Sic, without examples of the outlines in Orthic. Note this method includes omitting both dots above the letter i and dots below doubled letters. Both omissions are used in writing "will."]
c. Initial **Th** is omitted in all common words. The omission is shown by writing the rest of the word above the line; thus, {% assign words = 'the they this them tho’ that' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" /> **{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor -%}. **Exception:** The character **a** <img src="{{ assets }}/a_raised.png" /> written above the line stands for the word **and.**
d. In adding inflections to words ending in **y,** the **y** is not changed to **i** or **ie**; thus, {% assign words = 'applyd trys easyst happyr' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" /> **{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor -%}.
e. Some common terminations are abbreviated as shown in the following list: [TODO: List. Same issue as with all the joining rules, but in miniature.]

### The General Method
The general method of abbreviating long words is to write only the first syllable, and, if necessary, to indicate the termination by writing the last letter or two, separated by a small interval from the first part; thus, {% assign words = 'DIFferenT DIFferenCE acknowledge ESPeciallY CIRcumstanCE EXTRaordinarY REPresentatiVE' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" /> **{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor -%}. In many cases the termination may be joined, as in the last three examples.

### Phrases
Words may often be joined together provided that they are closely connected in sense. This applies especially to common words, auxiliaries, and particles, such as those contained in the list [following]: ex.&nbsp;gr. {% assign words = 'able to do,as it is,I am not,I have had,I shall be very,to be,ought to have been,with a view to' | split: ',' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" /> **{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor -%}.

### Abbreviations for Common Words
The following is a list of the abbreviations for common words used in the corresponding style. Many of them are such as are commonly used in longhand.

[TODO: Add table of abbreviations.]

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

[TODO: Continue.]

### St John 11

## Application to Foreign Languages
### French
#### Specimen
#### Key

### German
#### Specimen
#### Key

### Italian
#### Specimen
#### Key

### Latin
#### Specimen
#### Key

### Greek
#### Specimen
#### Key

## Hints for the Reporting Style
### Written in Ordinary Style
#### Key

### Specimen (Moderately Abbreviated)
#### Key