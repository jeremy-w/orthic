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

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This version of <span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Hugh L. Callendar's <em>A Manual of Orthographic Cursive Shorthand</em></span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://jeremy-w.github.io/orthic" property="cc:attributionName" rel="cc:attributionURL">Jeremy W. Sherman</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://books.google.com/books/about/A_Manual_of_Orthographic_Cursive_Shortha.html?id=kQ5SAAAAYAAJ" rel="dct:source">https://books.google.com/&#8203;books/&#8203;about/&#8203;A_Manual_of_&#8203;Orthographic_Cursive_&#8203;Shortha.html&#8203;?id=kQ5SAAAAYAAJ</a>.<br />Permissions beyond the scope of this license may be available at <a xmlns:cc="http://creativecommons.org/ns#" href="https://jeremywsherman.com/" rel="cc:morePermissions">https://jeremywsherman.com/</a>.

## Introductory Remarks
The present system is an adaptation of the alphabet and principles of Cursive Shorthand to the common orthography.

Two and a half years' experience in teaching Cursive has convinced me that the difficulties which beginners find in learning to spell correctly _by sound_ are much greater than I had previously imagined; and that it is unadvisable to attempt to introduce a _phonetic_ system of shorthand at an early stage in education.

I have every reason to believe that the present adaptation of Cursive to the common spelling will be found much more simple and easy to learn than any of the phonetic systems at present in vogue. There is very little to learn beyond an alphabet of 26 characters, and the method of joining them. In fact many students have succeeded in reading and writing the present system with nothing but the bare alphabet to guide them.

With the exception that the method of spelling adopted is orthographic instead of phonetic, no changes has been made in the fundamental principles of the system. These have been already discussed and explained in the introduction to the _[Manual of Cursive Shorthand](https://archive.org/details/manualofcursives00calliala)._ It is needless therefore to repeat them here.

The characters of the alphabet are for the most part the same as in Phonetic Cursive; but the change of spelling has made it necessary to rearrange some of them.

Advantage has been taken of this rearrangement to introduce several improvements in matters of detail, which have been suggested by the experience of teachers. The general style of the writing has been made even more flowing and lineal than before. The awkward backslope \ has been eliminated from the alphabet, and restricted to use in terminations, where it is comparatively harmless. [Jeremy: It's used for -ing.]

The writing requires no great niceties of penmanship. No distinction is made, as in other systems, between thin strokes and thick. Only two sizes of character are employed, instead of three or four. The vowel characters are connecting strokes joined in their natural order together with the consonants. The great majority of the signs are written on the ordinary slope of longhand, and the forms and distinctions between the characters are such as are already familiar to every one who has learnt to write in the ordinary style.

The system is strictly alphabetic. A letter is always represented by its alphabetic character. There are no alternative hooks and loops, or halving and doubling principles, to puzzle and distract the student. A word can be written in one way only. The rules are consequently very few, definite, and easy to apply.

In learning the system the student should work straight through the alphabet and following pages, writing and analysing every example as he comes to it. By the time he reaches [the end of the joining rules] he will thus have become thoroughly familiar with the alphabet. He will then be able to read through the specimen [of the fully-written style], in which every word is spelt in full.

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

**Exception:** ![]({{ assets }}/EE.png)&nbsp;**ee**; thus, ![]({{ assets }}/sleep.png)&nbsp;**sleep**, cp. ![]({{ assets }}/sup.png)&nbsp;**sup**.

## General Rules
### Orthographic Spelling
All words, when written in full, are spelt according to the common orthography. The characters are to be joined together smoothly, without lifting the pen, or making any unnecessary angles or breaks. All the more common and important joinings are fully explained and illustrated in ["How to Write and Join the Characters"].

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

### Dividing a Word
A word may always be divided if it happens to be convenient. The necessity for this, however, very seldom arises except in the case of compound words. {% assign words = 'lawsuit Woolwich virgin' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor -%}.

### Punctuation
Punctuation is effected in the usual way, except the Hyphen&nbsp;<img src="{{ assets }}/Hyphen.png" />, and the Dash&nbsp;<img src="{{ assets }}/Dash.png" />. [Jeremy: They are the normal hyphen and dash, except a vertical stroke intersects each in the middle, like a plus sign. This distinguishes them from raised A ("and") and raised O ("though").]

### Initial Capitals
Initial capitals are marked thus <img src="{{ assets }}/InitialCapitalsMark.png" />. {% assign words = 'Jack Clay S.E. L.S.W.R.' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor %}

## How to Write and Join the Characters
In the following alphabetic list are given examples and explanations of all the joinings which are likely to cause the beginner any difficulty.

- **A**&nbsp;![]({{ assets }}/A.png) is a short horizontal connecting stroke. It forms the diphthongs {% assign words = 'ai au ay_both' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word | slice: 0,2 }}**{% unless forloop.last %}, {% endunless %}
{%- endfor %}.
  - **Ay** may be curved either way. The form ![under-ay]({{ assets }}/ay_under.png "under-ay") is used whenever it joins more clearly or easily than the form ![over-ay]({{ assets }}/ay_over.png "over-ay"), as after {% assign words = 'D T J Qu M N V' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" alt="{{ word }}" title="{{ word }}" />
{%- endfor %} thus, {% assign words = 'days quay' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor %}; cp. {% assign words = 'says hay' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor %}.

- **B**&nbsp;![]({{ assets }}/B.png) is written like the letter ![lowercase cursive b]({{ assets }}/longhand_b.png "lowercase cursive b"), but with a more open loop and without the hook upwards at the end. It forms the compounds:
{% for it in site.data.manual.compounds.b %}
  - {{ it[0] }}&nbsp;![]({{ assets }}/{{ it[0] }}.png) ![]({{ assets }}/{{ it[1] }}.png)&nbsp;{{ it[1] }}
{% endfor %}

- **C**&nbsp;![]({{ assets }}/C.png) is written like the letter _c,_ but it is not turned up at the end, unless followed by _e._
  - **Ch**&nbsp;![]({{ assets }}/Ch.png) is written and joined exactly like the longhand letter _o_; thus, {% assign words = 'chair Christ ache' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor %}, cp. {% assign word = "ahead" %}<img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**.
  - Other compounds are:
{% for it in site.data.manual.compounds.c %}
    - {{ it[0] }}&nbsp;![]({{ assets }}/{{ it[0] }}.png) ![]({{ assets }}/{{ it[1] }}.png)&nbsp;{{ it[1] }}
{% endfor %}

- **D**&nbsp;![]({{ assets }}/D.png) and ![]({{ assets }}/T.png)&nbsp;**t** have similar characters, but that for _d_ is made much flatter, and about three times as long. It forms the compounds:
{% for it in site.data.manual.compounds.d %}
  - {{ it[0] }}&nbsp;![]({{ assets }}/{{ it[0] }}.png)
  {%- for example in it offset: 1 %} ![]({{ assets }}/{{ example }}.png)&nbsp;{{ example }}
  {%- endfor -%}
{% endfor %}
 [Jeremy: The _Supplement_ published a year later suggests in ordinary style always omitting the D from the prefix ADJ-, which is probably why no example is given.]

- **E**&nbsp;![]({{ assets }}/E.png) is a short upstroke; it must not be confused with ![]({{ assets }}/s_straight.png)&nbsp;**s**, which is written downwards.
  - **Ea**&nbsp;![ea, both over and under]({{ assets }}/ea_both.png) may be curved either way like _ay._ The form ![under-ea]({{ assets }}/ea_under.png "under-ea") is used except after {% assign words = 'M N P_noarrow S_noarrow Y B' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" alt="{{ word | slice: 0,1 }}" title="{{ word | slice: 0,1 }}" />
{%- endfor %}. An angle must always be made after ![over-ea]({{ assets }}/ea_over.png) before ![t]({{ assets }}/T.png "t")![d]({{ assets }}/D.png "d") or ![s]({{ assets }}/S_noarrow.png "s"); thus {% assign words = 'seat seas eat real pearl years' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor %}.
  - The diphthongs {% assign words = 'ee ei ie' | split: ' ' %}{% for word in words -%}
    **{{ word }}**&nbsp;<img src="{{ assets }}/{{ word }}.png" />{% unless forloop.last %}, {% endunless %}
{%- endfor %}ee ei ie are all written upwards much more steeply than _u._ ![]({{ assets }}/steep.png)&nbsp;**steep**, cp. ![]({{ assets }}/stupid.png)&nbsp;**stupid**. **eu**&nbsp;![]({{ assets }}/eu.png), **ew**&nbsp;![]({{ assets }}/ew.png) ![]({{ assets }}/new.png)&nbsp;**new**.

- **F**&nbsp;![]({{ assets }}/F.png)

- **G**&nbsp;![]({{ assets }}/G.png)

- **H**&nbsp;![]({{ assets }}/H.png)

- **I**&nbsp;![]({{ assets }}/I.png)

- **J**&nbsp;![]({{ assets }}/J.png)

- **K**&nbsp;![]({{ assets }}/K.png)

- **L**&nbsp;![]({{ assets }}/L.png)

- **M**&nbsp;![]({{ assets }}/M.png)

- **N**&nbsp;![]({{ assets }}/N.png)

- **O**&nbsp;![]({{ assets }}/O.png)

- **P**&nbsp;![]({{ assets }}/P.png)

- **Qu**&nbsp;![]({{ assets }}/Qu.png)

- **R**&nbsp;![]({{ assets }}/R.png)

- **S**&nbsp;![]({{ assets }}/S.png)

- **T**&nbsp;![]({{ assets }}/T.png)

- **U**&nbsp;![]({{ assets }}/U.png)

- **V**&nbsp;![]({{ assets }}/V.png)

- **W**&nbsp;![]({{ assets }}/W.png)

- **X**&nbsp;![]({{ assets }}/X.png)

- **Y**&nbsp;![]({{ assets }}/Y.png)

- **Z**&nbsp;![]({{ assets }}/Z.png)


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

1. The vowels **a** and **o** are omitted before **m** and **n**, except initially and in rare words; thus, {% assign words = 'can or con,al(o)ne,w(o)m(a)n' | split: ',' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor -%}. An omission of this kind can always be corrected, if desired, by writing the omitted character above; thus, {% assign words = 'band bond' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor -%}.

2. **Dots** are generally omitted in common words such as it, in, is, if, him, his, will. [Jeremy: Sic, without examples of the outlines in Orthic. Note this method includes omitting both dots above the letter i and dots below doubled letters. Both omissions are used in writing "will."]

3. Initial **Th** is omitted in all common words. The omission is shown by writing the rest of the word above the line; thus, {% assign words = 'the they this them tho’ that' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor -%}. **Exception:** The character **a** <img src="{{ assets }}/a_raised.png" /> written above the line stands for the word **and.**

4. In adding inflections to words ending in **y,** the **y** is not changed to **i** or **ie**; thus, {% assign words = 'applyd trys easyst happyr' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor -%}.

5. Some common terminations are abbreviated as shown in the following list: [TODO: List. Same issue as with all the joining rules, but in miniature.]

### The General Method
The general method of abbreviating long words is to write only the first syllable, and, if necessary, to indicate the termination by writing the last letter or two, separated by a small interval from the first part; thus, {% assign words = 'DIFferenT DIFferenCE acknowledge ESPeciallY CIRcumstanCE EXTRaordinarY REPresentatiVE' | split: ' ' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**{% unless forloop.last %}, {% endunless %}
{%- endfor -%}. In many cases the termination may be joined, as in the last three examples.

### Phrases
Words may often be joined together provided that they are closely connected in sense. This applies especially to common words, auxiliaries, and particles, such as those contained in the list [following]: ex.&nbsp;gr. {% assign words = 'able to do,as it is,I am not,I have had,I shall be very,to be,ought to have been,with a view to' | split: ',' %}{% for word in words -%}
    <img src="{{ assets }}/{{ word }}.png" />&nbsp;**{{ word }}**{% unless forloop.last %}, {% endunless %}
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

The great criterion of the state of the common people is the amount of wages; and as four-fifths of the common people were, in the seventeenth century, employed in agriculture, it is especially important to ascertain what were then the wages of the agricultural industry. On this subject we have the means of arriving at conclusions sufficiently exact for our purpose.

It seems clear that the wages of labour, estimated in money, were, in 1685, not more than half of what they now are; and there were few articles important to the working man of which the price was not, in 1685, more than half of what it now is. Beer was undoubtedly much cheaper in that age than at present. Meat was also cheaper, but was still so dear that hundreds of thousands of families scarcely knew the taste of it. In the cost of wheat there has been very little change. The average price of the quarter, during the last 12 years of Charles the Second, was fifty shillings. Bread, therefore, such as is now given to the inmates of a workhouse, was then seldom seen, even on the trencher of a yeoman or of a shopkeeper. The great majority of the nation lived entirely on rye, barley, and oats.

The produce of tropical countries, of mines, and of machinery, was positively dearer than at present. Among the commodities for which the labourer would have had to pay dearer in 1685 than his posterity now pay, were sugar, salt, coals, candles, soap, shoes, stockings, and generally all articles of clothing and all articles of bedding. It may be added, that the old coats and blankets would have been, not only more costly, but less serviceable, than the modern fabrics.

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
#### Specimen
<figure>
 <img src="{{ assets }}/FrenchSpecimen.png" />
 <figcaption>Specimen of French</figcaption>
</figure>

#### Key
<p lang="fr">De tous les systèmes de gouvernement et de garanties politiques, à coup sûr le plus difficile à établir, à faire prévaloir, c’est le système fédératif&#8239;; ce système qui consiste à laisser dans chaque localité, dans chaque société particulière, toute la portion de gouvernement qui peut y rester, et à ne lui enlever que la portion indispensable au maintien de la société générale, pour la porter au centre de cette même société, et l’y constituer sous la forme de gouvernement centrale.</p>

### German
#### Specimen
<figure>
 <img src="{{ assets }}/GermanSpecimen.png" />
 <figcaption>Specimen of German</figcaption>
</figure>

#### Key
<p lang="de">Die anziehende Kraft des geriebenen Bernsteins war bereits im Alterthume bekannt, jedoch ohne dass derselben weiter nachgeforscht wurde. Sie wurde gewöhnlich in Gemeinschaft mit der Anziehung des Magnetsteins gekannt, und von dieser nicht unterschieden. Die gleiche Eigenschaft wie beim Bernstein war später noch an einer bituminösen Steinkohle (Gagat) wahrgenommen worden.</p>

<p lang="de">Der Erste, welcher die Anziehung des geriebenen Bernsteins von der des Magnetsteins mit Bestimmtheit unterschied, und sie mit dem von der griechischen Benennung des Bernsteins (<em lang="grc">ἤλεκτρον</em>) entlehnten Namen bezeichnete, war W. Gilbert (um 1600). Er fand, dass Edelsteine, Glas, Harz, Schwefel, u.&#8239;s.&#8239;w., nach dem Reiben…</p>

### Italian
#### Specimen
<figure>
 <img src="{{ assets }}/ItalianSpecimen.png" />
 <figcaption>Specimen of Italian</figcaption>
</figure>

#### Key
<p lang="it">L’historia si puo veramente deffinire una guerra illustre contro il Tempo, perchè togliendoli di mano gl’anni suoi prigioneri, anzi già fatti cadaveri, li richiama in vita, li passa in rassegna, e li schiera di nuovo in battaglia. Ma gl’illustri Campioni che in tal Arringo fanno messe di Palme e d’Allori, rapiscono solo che le sole spoglie più sfarzose e brillanti, imbalsamando co’ loro inchiostri le Imprese de’ Principi e Potentati, e qualificati Personaggi, e trapontando coll’ ago finissimo dell’ ingegno i fili d’oro e di seta, che formano un perpetuo ricamo di Attioni gloriose. —<em>I Promessi Sposi,</em> <span lang="en">Introduction</span>.</p>

### Latin
#### Specimen
<figure>
 <img src="{{ assets }}/LatinSpecimen.png" />
 <figcaption>Specimen of Latin</figcaption>
</figure>

#### Key
<p lang="la">Urbem Romam a principio reges habuere. Libertarem et consulatum L. Brutus instituit. Dictaturae ad tempus sumebantur. Neque decemviralis potestas ultra biennium, neque tribunorum militum consulare jus diu valuit. Non Cinnae, non Sullae longa dominatio; et Pompeii Crassique potentia cito in Caesarem, Lepidi atque Antonii arma in Augustum cessere, qui cuncta, discordiis civilibus fessa, nomine Principis sub imperium accepit. —Tacitus, <em lang="en">Annals,</em> I.1.</p>

### Greek
#### Specimen
<figure>
 <img src="{{ assets }}/GreekSpecimen.png" />
 <figcaption>Specimen of Greek</figcaption>
</figure>

#### Key
<p lang="grc">Ἐπειδήπερ πολλοὶ ἐπεχείρησαν ἀνατάξασθαι διήγεσιν περὶ τῶν πεληροφορημένων ἐν ἡμῖν πραγμάτων, καθὼς παρέδοσαν ἡμῖν οἱ ἀπ’ ἀρχῆς αὐτόπται καὶ ὑμηρέται γενόμενοι τοῦ λόγου, ἔδοξε κἀμοὶ παρηκολουθηκότι ἄνωθεν πᾶσιν ἀκριβῶς καθεξῆς σοὶ γράψαι, κράτιστε θεόφιλε. <span lang="en">—St Luke I.1–3.</span></p>
<!-- thanks http://www.typegreek.com/ -->

## Hints for the Reporting Style
### Written in Ordinary Style
#### Key

### Specimen (Moderately Abbreviated)
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
