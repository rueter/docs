---
layout: base
title:  'UD_German'
udver: '2'
---

<!-- This page is automatically generated from the README file and from
     the data files in the latest release.

     Please do not edit this page directly. -->

# UD German

Language: [German](../de/overview/de-hub.html) (code: `de`)<br/>
Family: Indo-European, Germanic

This treebank has been part of Universal Dependencies since the UD v1.0 release.

The following people have contributed to making this treebank part of UD: Slav Petrov, Wolfgang Seeker, Ryan McDonald, Joakim Nivre, Daniel Zeman.

Repository: [UD_German](https://github.com/UniversalDependencies/UD_German)<br />
Search this treebank on-line: [PML-TQ](https://lindat.mff.cuni.cz/services/pmltq/#!/treebank/udde)

License: CC BY-NC-SA 3.0 US

Genre: news, reviews, wiki

Questions, comments?
General annotation questions (either German-specific or cross-linguistic) can be raised in the [main UD issue tracker](https://github.com/UniversalDependencies/docs/issues).
You can report bugs in this treebank in the [treebank-specific issue tracker on Github](https://github.com/UniversalDependencies/UD_German/issues).
If you want to collaborate, please contact [zeman&nbsp;(æt)&nbsp;ufal&nbsp;•&nbsp;mff&nbsp;•&nbsp;cuni&nbsp;•&nbsp;cz].
Development of the treebank happens directly in the UD repository, so you may submit bug fixes as pull requests against the dev branch.

| Annotation | Source |
|------------|--------|
| Lemmas | assigned by a program, not checked manually |
| UPOS | annotated manually in non-UD style, automatically converted to UD |
| XPOS | assigned by a program, not checked manually |
| Features | assigned by a program, not checked manually |
| Relations | annotated manually in non-UD style, automatically converted to UD |

## Description

The German UD is converted from the content head version of the [universal
dependency treebank v2.0 (legacy)](https://github.com/ryanmcd/uni-dep-tb).




The German UD conforms to the UD guidelines, but there are some exceptions.

Universal POS tags were assigned manually, while LEMMA and XPOSTAG were
predicted by TreeTagger (first for release 1.4; see Changelog below).
Morphological features were assigned using rules based on the values of the
other columns (UPOSTAG, XPOSTAG, LEMMA, FORM, DEPREL). Gender, number and
case of nouns and their det/amod children are based on the (manual) syntactic
annotation, e.g. nsubj => nominative. They should have high precision but
lower recall because we did not add them where the context did not provide
enough clues (morphological analyzer / lexicon was not used at this stage).

## Acknowledgments

# Statistics of UD German

## POS Tags

[ADJ](de-pos-ADJ.html) – [ADP](de-pos-ADP.html) – [ADV](de-pos-ADV.html) – [AUX](de-pos-AUX.html) – [CCONJ](de-pos-CCONJ.html) – [DET](de-pos-DET.html) – [NOUN](de-pos-NOUN.html) – [NUM](de-pos-NUM.html) – [PART](de-pos-PART.html) – [PRON](de-pos-PRON.html) – [PROPN](de-pos-PROPN.html) – [PUNCT](de-pos-PUNCT.html) – [SCONJ](de-pos-SCONJ.html) – [VERB](de-pos-VERB.html) – [X](de-pos-X.html)

## Features

[Case](de-feat-Case.html) – [Definite](de-feat-Definite.html) – [Degree](de-feat-Degree.html) – [Foreign](de-feat-Foreign.html) – [Gender](de-feat-Gender.html) – [Gender[psor]](de-feat-Gender-psor.html) – [Mood](de-feat-Mood.html) – [Number](de-feat-Number.html) – [Number[psor]](de-feat-Number-psor.html) – [NumType](de-feat-NumType.html) – [Person](de-feat-Person.html) – [Polarity](de-feat-Polarity.html) – [Polite](de-feat-Polite.html) – [Poss](de-feat-Poss.html) – [PronType](de-feat-PronType.html) – [Reflex](de-feat-Reflex.html) – [Tense](de-feat-Tense.html) – [Typo](de-feat-Typo.html) – [VerbForm](de-feat-VerbForm.html)

## Relations

[acl](de-dep-acl.html) – [advcl](de-dep-advcl.html) – [advmod](de-dep-advmod.html) – [amod](de-dep-amod.html) – [appos](de-dep-appos.html) – [aux](de-dep-aux.html) – [aux:pass](de-dep-aux-pass.html) – [case](de-dep-case.html) – [cc](de-dep-cc.html) – [ccomp](de-dep-ccomp.html) – [compound](de-dep-compound.html) – [compound:prt](de-dep-compound-prt.html) – [conj](de-dep-conj.html) – [cop](de-dep-cop.html) – [csubj](de-dep-csubj.html) – [csubj:pass](de-dep-csubj-pass.html) – [dep](de-dep-dep.html) – [det](de-dep-det.html) – [det:poss](de-dep-det-poss.html) – [expl](de-dep-expl.html) – [expl:pv](de-dep-expl-pv.html) – [fixed](de-dep-fixed.html) – [flat](de-dep-flat.html) – [iobj](de-dep-iobj.html) – [mark](de-dep-mark.html) – [nmod](de-dep-nmod.html) – [nmod:poss](de-dep-nmod-poss.html) – [nsubj](de-dep-nsubj.html) – [nsubj:pass](de-dep-nsubj-pass.html) – [nummod](de-dep-nummod.html) – [obj](de-dep-obj.html) – [obl](de-dep-obl.html) – [parataxis](de-dep-parataxis.html) – [punct](de-dep-punct.html) – [root](de-dep-root.html) – [xcomp](de-dep-xcomp.html)

<h2>Tokenization and Word Segmentation</h2>

<ul>
<li>This corpus contains 15590 sentences, 287110 tokens and 292152 syntactic words.</li>
<li>This corpus contains 33950 tokens (12%) that are not followed by a space.</li>
<li>This corpus does not contain words with spaces.</li>
<li>This corpus contains 192 types of words that contain both letters and punctuation. Examples: St., Dr., 's, &amp;, U.S., B., I., z.B., u.a., d', z., v., W., e.V., jap., l', etc., ca., s., F., H., M., k.k., C., D., G., Inc., J., P., Co., Prof., engl., L., d.h., E., K., O'Brien, S.S., ital., k.u.k., lat., 're, 1B.LS1, A., A.V.G., C.C., Gr., I.G., K.o., L.A.</li>
<li>This corpus contains 5042 multi-word tokens. On average, one multi-word token consists of 2.00 syntactic words.</li>
<li>There are 12 types of multi-word tokens. Examples: im, zum, am, zur, vom, beim, ins, ans, ums, aufs, übers, fürs.</li>
</ul>

<h2>Morphology</h2>

<h3>Tags</h3>

<ul>
<li>This corpus uses 15 UPOS tags out of 17 possible: <a>ADJ</a>, <a>ADP</a>, <a>ADV</a>, <a>AUX</a>, <a>CCONJ</a>, <a>DET</a>, <a>NOUN</a>, <a>NUM</a>, <a>PART</a>, <a>PRON</a>, <a>PROPN</a>, <a>PUNCT</a>, <a>SCONJ</a>, <a>VERB</a>, <a>X</a></li>
<li>This corpus does not use the following tags: INTJ, SYM</li>
<li>This corpus contains 34 word types tagged as particles (PART): 's, ;-), Bitte, Danke, Hallo, Na, Ok, ab, als, an, auf, auflief, aus, dar, einnahm, garnicht, her, hin, ja, keine, keinerlei, mit, ncht, nein, nich, nicht, preis, statt, to, vor, weg, wehe, wie, zu</li>
</ul>

<ul>
<li>This corpus contains 97 lemmas tagged as pronouns (PRON): Ihr|ihr, Sie|sie, all, alle, ander, andere, beide, bißchen, dadurch, dafür, dagegen, daher, damit, daran, darauf, daraus, darin, darum, darüber, davon, davor, dazu, dein, der, dergleichen, derjenige, derselbe, diejenige, diejenigen, dies, dieselbe, du, ebendies, eigige, ein, einige, einiges, er, er|es, er|es|sie, es, etlich, etwas, euer, genug, ich, ihr, irgendein, irgendetwas, irgendwas, irgendwelch, irgendwer, jed, jeglich, jemand, jen, kein, keinerlei, keinster, man, manch, mehr, mehrere, mein, meist, nichts, niemand, nix, paar, sein, selb, selbst, sie, solch, soviel, sowas, sämtlich, unser, viel, was, welch, welche, wenig, weniger, wer, wieviele, wir, wobei, wodurch, womit, wonach, woraus, worin, wovon, wozu, zahlreich, zuviel</li>
</ul>

<ul>
<li>This corpus contains 26 lemmas tagged as determiners (DET): Alla, Ihr|ihr, The, all, alle, beide, d, dein, der, derselbe, dessa, dies, ein, einige, etlich, euer, ihr, irgendein, jen, kein, manch, mein, sein, unser, viel, zahlreich</li>
</ul>

<ul>
<li>Out of the above, 22 lemmas occurred sometimes as PRON and sometimes as DET: Ihr|ihr, all, alle, beide, dein, der, derselbe, dies, ein, einige, etlich, euer, ihr, irgendein, jen, kein, manch, mein, sein, unser, viel, zahlreich</li>
</ul>

<ul>
<li>This corpus contains 114 lemmas tagged as auxiliaries (AUX): Hab, Saarinen, Ware, abkürzen, amtieren, anerkennen, angefühlt, ansehen, aufbauen, auftreten, be, bedeuten, befinden, befördern, bekommen, benennen, berufen, beschimpfen, bestehen, bestimmen, betiteln, betragen, bezeichnen, bilden, bleiben, brauchen, could, d, daneben, darstellen, degradieren, deuten, dienen, duften, dürfen, einstufen, empfinden, entlarven, entwickeln, entziffern, erachten, erheben, erklären, ernennen, erscheinen, erweisen, erweitern, erwähnen, eröffnen, feiern, feststellen, finden, folgen, fungieren, gehen, gelten, genannt, gestalten, glauben, gründen, haben, halten, handeln, have, heißen, identifizieren, is, kanns, kosten, können, küren, lassen, lauten, liegen, listen, machen, messen, mögen, müssen, nehmen, nennen, nominieren, prägen, scheinen, schlagen, schmecken, sehen, sein, seyn, sollen, stehen, stellen, umbauen, umbenennen, umbilden, umwandeln, verarbeiten, vereidigen, verhaften, verlegen, versterben, vorstellen, wandeln, was, werd, werden, wir, wirken, wissen, wollen, worden, wählen, zu, überzeugen</li>
</ul>

<ul>
<li>Out of the above, 93 lemmas occurred sometimes as AUX and sometimes as VERB: Hab, amtieren, anerkennen, ansehen, aufbauen, auftreten, bedeuten, befinden, befördern, bekommen, benennen, berufen, beschimpfen, bestehen, bestimmen, betragen, bezeichnen, bilden, bleiben, brauchen, darstellen, degradieren, deuten, dienen, duften, dürfen, einstufen, empfinden, entlarven, entwickeln, erheben, erklären, ernennen, erscheinen, erweisen, erweitern, erwähnen, eröffnen, feiern, feststellen, finden, folgen, fungieren, gehen, gelten, gestalten, glauben, gründen, haben, halten, handeln, heißen, identifizieren, kosten, können, küren, lassen, lauten, liegen, machen, messen, mögen, müssen, nehmen, nennen, nominieren, prägen, scheinen, schlagen, schmecken, sehen, sein, seyn, sollen, stehen, stellen, umbauen, umbenennen, umwandeln, verarbeiten, vereidigen, verhaften, verlegen, versterben, vorstellen, wandeln, was, werden, wirken, wissen, wollen, wählen, überzeugen</li>
</ul>

<ul>
<li>There are 3 <a href="../feat/VerbForm.html">(de)verbal forms:</a>
<ul>
  <li>Fin
  <ul>
    <li>AUX: ist, wurde, war, sind, wird, wurden, kann, hat, werden, waren</li>
    <li>VERB: gibt, kam, hat, liegt, hatte, gab, erhielt, war, befindet, ist</li>
  </ul>
  </li>
  <li>Inf
  <ul>
    <li>AUX: werden, sein, können, haben, müssen, lassen, wollen, dürfen, bleiben, auftreten</li>
    <li>VERB: empfehlen, lassen, machen, finden, erreichen, haben, sehen, gehen, sagen, kommen</li>
  </ul>
  </li>
  <li>Part
  <ul>
    <li>AUX: worden, gewesen, genannt, geworden, bezeichnet, ernannt, gewählt, geblieben, gemacht, umbenannt</li>
    <li>VERB: gegründet, verwendet, eingesetzt, genutzt, gebaut, aufgenommen, errichtet, erwähnt, geboren, veröffentlicht</li>
  </ul>
  </li>
</ul>
</li>
</ul>

<h3>Nominal Features</h3>

<li><a>Gender</a>
  <ul>
    <li>Fem
      <ul>
        <li>ADJ: erste, neue, große, ersten, weitere, deutschen, kleine, andere, deutsche, eigene</li>
        <li>ADP: als</li>
        <li>DET: die, der, eine, einer, den, dessen, diese, jener, dem, alle</li>
        <li>NOUN: Zeit, Stadt, Familie, Saison, Rolle, Regierung, Praxis, Firma, Gemeinde, Seite</li>
        <li>NUM: 2, 35, fünfte</li>
        <li>PRON: sie, diese, dieser, alle, meine, unsere, ihre, seine, seiner, jede</li>
        <li>PROPN: University, Universität, SPD, Schweiz, Bundesrepublik, USA, Deutsche, AG, DDR, Hochschule</li>
        <li>X: the</li>
      </ul>
    </li>
    <li>Masc
      <ul>
        <li>ADJ: erste, ersten, neuen, größten, neue, weiteren, alte, dritten, großen, deutsche</li>
        <li>DET: der, den, einen, dessen, die, Das, deinen, dieser, jener</li>
        <li>NOUN: Ort, Name, Platz, Film, Teil, Begriff, Preis, Hause, Titel, Bahnhof</li>
        <li>NUM: 18.</li>
        <li>PRON: er, ihm, ihn, dieser, diesen, ihren, jeden, meinen, deren, jeder</li>
        <li>PROPN: USA, Frankreich, FC, Heinrich, River, Österreich, Award, Cup, Ehrlich, Friedrich</li>
        <li>VERB: meinen, umgebenden</li>
        <li>VERB-Fin: meinen</li>
      </ul>
    </li>
    <li>Masc,Neut
      <ul>
        <li>ADJ: ersten, gleichen, selben, neuen, heutigen, großen, amerikanischen, französischen, nächsten, weiteren</li>
        <li>ADP: als</li>
        <li>DET: dem, des, ein, einem, eines, diesem, eins</li>
        <li>NOUN: Jahr, Jahre, Teil, Ende, Beispiel, Bereich, Rahmen, Gebiet, Sommer, Gegensatz</li>
        <li>NUM: 1, 24., 31, 6, 1., 13, 16, 17, 18, 1:1</li>
        <li>PRON: diesem, dieses, mein, meinem, ihrem, sein, seinem, jedem, jedes, ihr</li>
        <li>PROPN: Zweiten, Weltkrieg, Oktober, Mai, September, November, Ersten, März, Februar, Dezember</li>
        <li>SCONJ: dass</li>
        <li>VERB: erweiterten, großen</li>
      </ul>
    </li>
    <li>Neut
      <ul>
        <li>ADJ: erste, gesamte, neue, heutige, alte, ganze, große, dritte, ehemalige, kurzer</li>
        <li>ADV: mehr</li>
        <li>DET: das, die, den, der, dem, dessen, Dieses, einige</li>
        <li>NOUN: Zeit, Unternehmen, Album, Team, Leben, essen, Personal, Teile, Gebiet, Gebäude</li>
        <li>PRON: es, dieses, aller, das, diesen, 's, ihre, viel, andere, einige</li>
        <li>PROPN: Kreuz, München, Institut, Museum, Eiserne, Team, College, Gymnasium, Haus, Klein</li>
      </ul>
    </li>
  </ul>
</li>


<li><a>Number</a>
  <ul>
    <li>Plur
      <ul>
        <li>ADJ: weitere, ersten, anderen, viele, verschiedene, neue, andere, große, zahlreiche, meisten</li>
        <li>AUX-Fin: wurden, sind, waren, werden, haben, können, hatten, sollen, konnten, müssen</li>
        <li>DET: die, den, der, das, einen, ein, dessen, eine, dem, des</li>
        <li>NOUN: Jahren, Menschen, Kinder, Jahre, Namen, Frauen, Personen, Arten, Einwohnern, Metern</li>
        <li>NUM: 1870er, drei, sechs</li>
        <li>PRON: wir, sie, uns, diese, alle, beiden, ihnen, mehrere, einige, ihr</li>
        <li>PROPN: Olympischen, Spielen, Staaten, Vereinigten, Alpen, Studios, Serben, Bergen, Inseln, Motors</li>
        <li>VERB-Fin: haben, stehen, gehören, gibt, kamen, hatten, kommen, liegen, waren, befinden</li>
        <li>X: er</li>
      </ul>
    </li>
    <li>Sing
      <ul>
        <li>ADJ: ersten, erste, neue, neuen, große, deutschen, weitere, großen, zweiten, gleichen</li>
        <li>ADP: als</li>
        <li>ADV: mehr</li>
        <li>AUX-Fin: ist, wurde, war, wird, sind, hat, kann, hatte, konnte, habe</li>
        <li>DET: dem, der, die, das, des, den, eine, ein, einer, einem</li>
        <li>NOUN: Jahr, Zeit, Stadt, Teil, Prozent, Jahre, Ort, Familie, Ende, Platz</li>
        <li>NUM: 1, 31, 2, 24., 6, 1., 13, 16, 17, 18</li>
        <li>PRON: er, es, ich, sie, diese, ihm, dieser, was, diesem, ihn</li>
        <li>PROPN: Weltkrieg, Zweiten, Oktober, USA, Mai, von, Ersten, November, SPD, University</li>
        <li>SCONJ: dass</li>
        <li>VERB: gibt, hatte, kam, liegt, hat, erhielt, war, befindet, gab, ist</li>
        <li>VERB-Fin: gibt, hatte, kam, liegt, hat, erhielt, war, befindet, gab, ist</li>
        <li>X: What, the</li>
      </ul>
    </li>
  </ul>
</li>

<li><a>Case</a>
  <ul>
    <li>Acc
      <ul>
        <li>ADJ: neue, große, erste, ersten, weitere, eigene, verschiedene, viele, gute, andere</li>
        <li>ADV: mehr</li>
        <li>DET: die, den, das, eine, einen, ein, dessen, dem, der, eines</li>
        <li>NOUN: Platz, Zeit, Jahre, Rolle, Leben, Namen, Prozent, Kinder, Titel, Geld</li>
        <li>NUM: 31</li>
        <li>PRON: sich, ihn, diese, mich, die, es, sie, was, das, uns</li>
        <li>PROPN: USA, Deutschland, Mark, Award, Cup, Deutsche, Wiener, Dollar, Euro, Hamburger</li>
        <li>VERB: meinen, umgebenden</li>
        <li>VERB-Fin: meinen</li>
        <li>X: the</li>
      </ul>
    </li>
    <li>Acc,Dat
      <ul>
        <li>PRON: sich</li>
      </ul>
    </li>
    <li>Acc,Nom
      <ul>
        <li>PRON: es, sie, 's</li>
      </ul>
    </li>
    <li>Dat
      <ul>
        <li>ADJ: ersten, anderen, weiteren, neuen, großen, letzten, deutschen, gleichen, selben, nächsten</li>
        <li>DET: dem, der, den, einem, einer, dessen, des, diesem, einen, jenen</li>
        <li>NOUN: Jahr, Jahren, Zeit, Jahre, Saison, Ende, Stadt, Teil, Bereich, Beispiel</li>
        <li>NUM: 1, 24., 31, 6, 1., 13, 16, 17, 18, 1870er</li>
        <li>PRON: ihm, diesem, sich, dieser, mir, dem, ihnen, denen, uns, der</li>
        <li>PROPN: Weltkrieg, Oktober, Mai, November, September, Zweiten, März, University, Universität, Februar</li>
        <li>X: er</li>
      </ul>
    </li>
    <li>Gen
      <ul>
        <li>ADJ: neuen, amerikanischen, ehemaligen, ersten, französischen, gesamten, großen, deutschen, europäischen, verschiedener</li>
        <li>DET: des, eines, einer, der, dem, aller, eins, vieler</li>
        <li>NOUN: Jahres, Landes, weiteren, Königs, Ortes, Flusses, Zeit, Films, Hauses, Krieges</li>
        <li>PRON: aller, seiner, meiner, jedes, dieser, ihrer, mehrerer, seines, unseres, vieler</li>
        <li>PROPN: Ersten, Weltkrieges, Weltkriegs, Zweiten, Instituts, Internationalen, Krieges, Reiches, Alten, Berliner</li>
        <li>VERB: erweiterten, großen</li>
      </ul>
    </li>
    <li>Nom
      <ul>
        <li>ADJ: erste, weitere, neue, viele, kleine, große, deutsche, andere, zahlreiche, alte</li>
        <li>ADP: als</li>
        <li>ADV: Genau</li>
        <li>DET: die, der, das, ein, eine, dessen, den, einen, diese, Dieses</li>
        <li>NOUN: Menschen, Ort, Unternehmen, Name, Stadt, Vater, Album, Prozent, Zahl, essen</li>
        <li>NUM: 18., 2, drei, fünfte, sechs</li>
        <li>PRON: er, sie, die, es, ich, man, der, wir, diese, das</li>
        <li>PROPN: von, SPD, Kohl, Müller, Deutsche, You, AG, I, de, GmbH</li>
        <li>SCONJ: dass</li>
        <li>X: What</li>
      </ul>
    </li>
  </ul>
</li>


<li><a>Definite</a>
  <ul>
    <li>Def
      <ul>
        <li>DET: der, die, dem, den, das, des</li>
      </ul>
    </li>
    <li>Ind
      <ul>
        <li>DET: eine, ein, einer, einem, einen, eines, eins, ne</li>
      </ul>
    </li>
  </ul>
</li>

<h3>Degree and Polarity</h3>

<li><a>Degree</a>
  <ul>
    <li>Cmp
      <ul>
        <li>ADJ: weitere, weiteren, besser, früheren, späteren, weiterer, kleinere, spätere, kleineren, neuere</li>
      </ul>
    </li>
    <li>Cmp,Pos
      <ul>
        <li>ADJ: später, kleiner, großer, guter, deutscher, anderer, erster, neuer, letzter, besonderer</li>
      </ul>
    </li>
    <li>Pos
      <ul>
        <li>ADJ: ersten, anderen, erste, gut, großen, kurz, neue, neuen, deutschen, freundlich</li>
      </ul>
    </li>
    <li>Sup
      <ul>
        <li>ADJ: besten, beste, bester, wichtigsten, bedeutendsten, wichtigste, bestes, bekanntesten, äußersten, häufigsten</li>
      </ul>
    </li>
  </ul>
</li>

<li><a>Polarity</a>
  <ul>
    <li>Neg
      <ul>
        <li>ADJ: KEINSTER, keine</li>
        <li>ADV: nie, niemals, leider, nicht, auch, inte, keineswegs, mitnichten, negativ, nirgendwo</li>
        <li>NOUN: Nicht</li>
        <li>PART: nicht, nein, garnicht, keine, keinerlei, ncht, nich</li>
        <li>PROPN: not, nicht, No</li>
      </ul>
    </li>
  </ul>
</li>


<h3>Verbal Features</h3>


<li><a>Mood</a>
  <ul>
    <li>Ind
      <ul>
        <li>AUX-Fin: ist, wurde, war, sind, wird, kann, hat, werden, waren, hatte</li>
        <li>VERB-Fin: hat, hatte, war, ist, haben, sind, hatten, waren, bin, habe</li>
      </ul>
    </li>
    <li>Sub
      <ul>
        <li>AUX-Fin: würde, hätte, hätten, seien, wäre, möchte, könnte, könne, wolle, könnten</li>
        <li>VERB-Fin: hätten, hätte, wolle, möchte, seien, möge, wäre, wären</li>
      </ul>
    </li>
  </ul>
</li>

<li><a>Tense</a>
  <ul>
    <li>Past
      <ul>
        <li>AUX-Fin: wurde, war, waren, hatte, konnte, sollte, musste, hatten, konnten, wollte</li>
        <li>VERB-Fin: hatte, war, hatten, waren, wurde, wollte, wollten, hätten, hätte, möchte</li>
      </ul>
    </li>
    <li>Pres
      <ul>
        <li>AUX-Fin: ist, sind, wird, kann, hat, werden, haben, habe, können, soll</li>
        <li>VERB-Fin: hat, ist, haben, sind, bin, habe, weiß, will, wird, wolle</li>
      </ul>
    </li>
  </ul>
</li>



<h3>Pronouns, Determiners, Quantifiers</h3>

<li><a>PronType</a>
  <ul>
    <li>Art
      <ul>
        <li>DET: der, die, dem, den, das, des, eine, ein, einer, einem</li>
      </ul>
    </li>
    <li>Dem
      <ul>
        <li>DET: deren, dessen, das, die, jener, diesem, desselben, diese, dem, den</li>
        <li>PRON: dieser, diese, das, dieses, diesem, die, dies, der, diesen, dem</li>
      </ul>
    </li>
    <li>Dem,Rel
      <ul>
        <li>PRON: dazu, davon, dafür, darauf, darin, damit, daran, dadurch, darüber, daraus</li>
      </ul>
    </li>
    <li>Ind
      <ul>
        <li>DET: all, einige, einen, etliche, irgendeiner, manche, viele, vielen, vieler, zahlreiche</li>
        <li>PRON: man, anderem, einige, mehrere, einer, viele, eine, mehr, eines, andere</li>
      </ul>
    </li>
    <li>Int
      <ul>
        <li>ADV: wo, warum, Wie</li>
        <li>PRON: was, wer, welches, Wen, welche, welcher, wem, wieviele</li>
      </ul>
    </li>
    <li>Int,Rel
      <ul>
        <li>PRON: wodurch, wovon, womit, wonach, worin, wozu, wobei, woraus</li>
      </ul>
    </li>
    <li>Neg
      <ul>
        <li>DET: keine</li>
        <li>PRON: keine, kein, keinen, nichts, keinem, keiner, niemand, keinerlei, keines, nix</li>
      </ul>
    </li>
    <li>Prs
      <ul>
        <li>DET: seine, seiner, sein, ihre, seinen, seinem, ihrer, ihren, ihr, seines</li>
        <li>PRON: er, sich, sie, es, ich, wir, ihm, ihn, uns, mir</li>
      </ul>
    </li>
    <li>Rel
      <ul>
        <li>DET: die, deren, der, dem, dessen, das, den</li>
        <li>PRON: die, der, das, dem, was, denen, welche, den, welcher, welches</li>
      </ul>
    </li>
    <li>Tot
      <ul>
        <li>DET: The, alla, aller, des, dessa, alle, beiden</li>
        <li>PRON: allem, alle, beiden, alles, allen, aller, jeden, jede, beide, jeder</li>
      </ul>
    </li>
  </ul>
</li>

<li><a>NumType</a>
  <ul>
    <li>Card
      <ul>
        <li>DET: beiden</li>
        <li>NUM: zwei, drei, vier, 2007, 2006, fünf, 2009, 2010, 1, sechs</li>
        <li>PRON: beiden, beide, beider, beides</li>
      </ul>
    </li>
    <li>Ord
      <ul>
        <li>ADJ: ersten, erste, zweiten, zweite, dritten, erster, dritte, erstes, fünften, siebten</li>
      </ul>
    </li>
  </ul>
</li>

<li><a>Poss</a>
  <ul>
    <li>Yes
      <ul>
        <li>DET: seine, seiner, sein, ihre, seinen, seinem, ihrer, ihren, ihr, seines</li>
        <li>PRON: meine, seine, unsere, ihre, mein, ihr, ihren, seiner, meiner, sein</li>
      </ul>
    </li>
  </ul>
</li>

<li><a>Reflex</a>
  <ul>
    <li>Yes
      <ul>
        <li>PRON: sich, mich, uns, mir, selbst, Euch</li>
      </ul>
    </li>
  </ul>
</li>

<li><a>Person</a>
  <ul>
    <li>1
      <ul>
        <li>AUX-Fin: habe, haben, kann, bin, sind, war, werde, werden, hatte, waren</li>
        <li>DET: meine, unsere, meiner, mein, unserem, meinem, unser</li>
        <li>PRON: ich, wir, uns, mir, mich, meine, unsere, mein, meiner, meinem</li>
        <li>VERB-Fin: war, hatte, kommen, waren, bin, gehe, finde, haben, habe, hatten</li>
      </ul>
    </li>
    <li>2
      <ul>
        <li>AUX-Fin: bist, habt, hast, könnt, müsst, sollst, werden, werdet, wirst, wollt</li>
        <li>DET: deinen, eure</li>
        <li>PRON: Sie, ihr, du, Ihnen, euch, Dir, dich, euren, eurer, Deinen</li>
        <li>VERB-Fin: findet, weißt, DENKST, Hast, Wollt, bist, gebt, gehst, gelingt, hasst</li>
      </ul>
    </li>
    <li>2,3
      <ul>
        <li>DET: Ihr, Ihre</li>
        <li>PRON: Ihre, Ihr, Ihrem, Ihrer</li>
      </ul>
    </li>
    <li>3
      <ul>
        <li>AUX-Fin: ist, wurde, war, sind, wird, wurden, hat, waren, werden, kann</li>
        <li>DET: seine, seiner, sein, seinen, ihre, seinem, ihrer, ihren, seines, ihr</li>
        <li>PRON: er, sich, es, sie, ihm, ihn, ihnen, seine, ihre, ihren</li>
        <li>VERB-Fin: gibt, hat, liegt, kam, gab, hatte, befindet, erhielt, ist, war</li>
      </ul>
    </li>
  </ul>
</li>

<li><a>Polite</a>
  <ul>
    <li>Form
      <ul>
        <li>PRON: Sie, Ihnen</li>
      </ul>
    </li>
    <li>Infm
      <ul>
        <li>DET: deinen, eure</li>
        <li>PRON: ihr, du, euch, Dir, dich, euren, eurer, Deinen</li>
      </ul>
    </li>
  </ul>
</li>

<li><a>Gender[psor]</a>
  <ul>
    <li>Masc,Neut
      <ul>
        <li>DET: seine, seiner, sein, seinen, seinem, seines</li>
        <li>PRON: seine, seiner, sein, seinem, seinen, seines</li>
      </ul>
    </li>
  </ul>
</li>

<li><a>Number[psor]</a>
  <ul>
    <li>Plur
      <ul>
        <li>DET: unsere, unserem, eure, unser</li>
        <li>PRON: unsere, unser, unserer, unserem, unseren, unseres, euren, eurer</li>
      </ul>
    </li>
    <li>Sing
      <ul>
        <li>DET: seine, seiner, sein, seinen, seinem, seines, meine, meiner, mein, deinen</li>
        <li>PRON: meine, seine, mein, seiner, meiner, sein, meinem, seinem, seinen, meinen</li>
      </ul>
    </li>
  </ul>
</li>

<h3>Other Features</h3>

<li><a>Foreign</a>
  <ul>
    <li>Yes
      <ul>
        <li>X: I, All, a, it, la, we, What, the</li>
      </ul>
    </li>
  </ul>
</li>
<li><a>Typo</a>
  <ul>
    <li>Yes
      <ul>
        <li>PRON: Mit, in</li>
      </ul>
    </li>
  </ul>
</li>

<h2>Syntax</h2>

<h3>Auxiliary Verbs and Copula</h3>

<ul>
<li>This corpus uses 210 lemmas as copulas (<a>cop</a>). Examples: sein, werden, bleiben, gelten, betragen, nennen, bezeichnen, ernennen, heißen, machen, wählen, %, bedeuten, lauten, in, von, I, umbenennen, ansehen, erheben, erscheinen, alle, befördern, genannt, halten, scheinen, werdend, Bedienung, bestehen, darstellen, einstufen, is, preis, stehen, stellen, umbauen, worden, °, 're, Atmosphäre, Mutter, Raum, als, be, befinden, berufen, bestimmen, bilden, bleibend, ein.</li>
<li>This corpus uses 28 lemmas as auxiliaries (<a>aux</a>). Examples: haben, können, sein, müssen, sollen, werden, wollen, dürfen, mögen, lassen, um, zu, to, Hab, Do, bekommen, scheinen, 'm, Can, Used, bleiben, brauchen, could, daneben, have, kanns, werd, wir.</li>
<li>This corpus uses 8 lemmas as passive auxiliaries (<a>aux:pass</a>). Examples: werden, sein, Saarinen, Signal, Ware, bekommen, müssen, wer.</li>
</ul>

<h3>Core Arguments, Oblique Arguments and Adjuncts</h3>

Here we consider only relations between verbs (parent) and nouns or pronouns (child).
<ul>
  <li><a>nsubj</a>
    <ul>
      <li>VERB--NOUN-Nom (43)</li>
      <li>VERB--PRON-Nom (40)</li>
      <li>VERB-Fin--NOUN-Nom (4441)</li>
      <li>VERB-Fin--NOUN-Nom-ADP(bis) (4)</li>
      <li>VERB-Fin--NOUN-Nom-ADP(um) (1)</li>
      <li>VERB-Fin--NOUN-Nom-ADP(wie) (1)</li>
      <li>VERB-Fin--PRON-Nom (3859)</li>
      <li>VERB-Inf--NOUN-Nom (452)</li>
      <li>VERB-Inf--NOUN-Nom-ADP(bis) (1)</li>
      <li>VERB-Inf--PRON-Nom (826)</li>
      <li>VERB-Part--NOUN-Nom (468)</li>
      <li>VERB-Part--PRON-Nom (601)</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>obj</a>
    <ul>
      <li>VERB--NOUN-Acc (203)</li>
      <li>VERB--PRON-Acc (53)</li>
      <li>VERB-Fin--NOUN-Acc (3860)</li>
      <li>VERB-Fin--NOUN-Acc-ADP(bis) (2)</li>
      <li>VERB-Fin--NOUN-Acc-ADP(mit) (1)</li>
      <li>VERB-Fin--NOUN-Acc-ADP(von) (9)</li>
      <li>VERB-Fin--NOUN-Acc-ADP(wie) (1)</li>
      <li>VERB-Fin--NOUN-Acc-ADP(zwischen) (1)</li>
      <li>VERB-Fin--NOUN-Acc-ADP(über) (1)</li>
      <li>VERB-Fin--PRON-Acc (1267)</li>
      <li>VERB-Inf--NOUN-Acc (1144)</li>
      <li>VERB-Inf--NOUN-Acc-ADP(bis) (1)</li>
      <li>VERB-Inf--PRON-Acc (361)</li>
      <li>VERB-Part--NOUN-Acc (523)</li>
      <li>VERB-Part--NOUN-Acc-ADP(mit) (1)</li>
      <li>VERB-Part--PRON-Acc (270)</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>iobj</a>
    <ul>
      <li>VERB--NOUN-Dat (22)</li>
      <li>VERB--PRON-Dat (8)</li>
      <li>VERB-Fin--NOUN-Dat (339)</li>
      <li>VERB-Fin--PRON-Dat (254)</li>
      <li>VERB-Inf--NOUN-Dat (80)</li>
      <li>VERB-Inf--PRON-Dat (91)</li>
      <li>VERB-Part--NOUN-Dat (103)</li>
      <li>VERB-Part--NOUN-Dat-ADP(bis) (1)</li>
      <li>VERB-Part--PRON-Dat (113)</li>
    </ul>
  </li>
</ul>

<h3>Reflexive Verbs</h3>

<ul>
  <li>This corpus contains 12 lemmas that occur at least once with an <a>expl:pv</a> child. Examples: befinden sich, erholen sich, weigern sich, verlieben sich, begeben sich, nähern sich, bedanken mich, aneignen sich, anfreunden uns, bedanken uns, begeben mich, erholen mich</li>
</ul>


<h3>Verbs with Reflexive Core Objects</h3>

<ul>
  <li>This corpus contains 500 lemmas that occur at least once with a reflexive core object (<a>obj</a> or <a>iobj</a>). Examples: handeln sich, lassen sich, finden sich, setzen sich, beschäftigen sich, nehmen sich, fühlen mich, schließen sich, beteiligen sich, erstrecken sich, stellen sich, ergeben sich, fühlen sich, zeigen sich, bilden sich, entwickeln sich, kümmern sich, äußern sich, befassen sich, betätigen sich, engagieren sich, entscheiden sich, halten sich, ändern sich, beziehen sich, erheben sich, lohnen sich, machen sich, orientieren sich, sichern sich, treffen sich, unterscheiden sich, wenden sich, widmen sich, beschränken sich, etablieren sich, richten sich, sprechen sich, anschließen sich, bemühen sich, durchsetzen sich, leiten sich, lösen sich, zeichnen sich, zurückziehen sich, bekennen sich, belaufen sich, bewegen sich, einsetzen sich, erwerben sich</li>
    <ul>
      <li>Out of those, 26 lemmas occurred more than once, but never without a reflexive dependent. Examples: erstrecken, kümmern, befassen, betätigen, lohnen, belaufen, distanzieren, einigen, auszahlen, erfreuen, niederlassen, wundern, zusammenschließen, anschauen, auseinandersetzen, bewähren, breiten, erhoffen, erkämpfen, hauen, scheuen, trauen, verbünden, verfestigen, verjüngen, verwundern, Botschaftskanzlei, Jungkoch, Kristallisationsfigur, Montemar, Treibenlassen, abklären, abschwächen, absenken, abzeichnend, anbahnen, ansammeln, assimilieren, aufdrücken, auferlegen, aufritzt, aufschreiben, bereitfinden, bessern, besänftigen, betan, bewaffnen, bewegend, brüsten, dazugeschenkt</li>
    </ul>
</ul>

<h3>Relations Overview</h3>

<ul>
<li>This corpus uses 7 relation subtypes: <a>aux:pass</a>, <a>compound:prt</a>, <a>csubj:pass</a>, <a>det:poss</a>, <a>expl:pv</a>, <a>nmod:poss</a>, <a>nsubj:pass</a></li>
<li>The following 8 relation types are not used in this corpus at all: <a>vocative</a>, <a>dislocated</a>, <a>discourse</a>, <a>clf</a>, <a>list</a>, <a>orphan</a>, <a>goeswith</a>, <a>reparandum</a></li>
</ul>
