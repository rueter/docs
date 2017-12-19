---
layout: relation
title: 'nmod'
shortdef: 'nominal modifier'
udver: '2'
---

The `nmod` relation is used for nominal dependents of another noun or noun phrase and functionally corresponds to an attribute, to a genitive complement and to an (non-core) argument or adjunct.

We use the following language-specific subtypes for `nmod`:

* nmod: noun modifier (usually in Nominative) functionally corresponds to an attribute,
* [nmod:poss](nmod-poss): noun modifier functionally corresponds to a genitive complement (with the option of adpositional cases),
* [nmod:npmod](nmod-npmod): noun phrase functionally corresponds to an argument or adjunct.

In Armenian `nmod` is used:

* for noun-noun modification (including ablatives and instrumentals):

~~~ sdparse
քամի եղանակ \n wind.`Nom` weather
nmod(եղանակ, քամի)
nmod(weather, wind.`Nom`)
~~~

~~~ sdparse
երկու բաժակ ջուր \n two cup.`Nom` water
nmod(ջուր, բաժակ)
nummod(բաժակ, երկու)
nmod(water, cup.`Nom`)
nummod(cup.`Nom`, two)
~~~

~~~ sdparse
ռետինից գնդակ \n rubber.`Abl` ball
nmod(գնդակ, ռետինից)
nmod(ball, rubber.`Abl`)
~~~

~~~ sdparse
տարիքով մարդ \n age.`Ins` man
nmod(մարդ, տարիքով)
nmod(age.`Ins`, man)
~~~

* for explicative attribute of a noun: a typical example is a title attached to a name of a person. The relation is similar to the [flat]() relation that links the first and the last name, but it is not labeled `flat` because the title is not part of the name:

~~~ sdparse
Արշակ թագավորը \n King Arshak 
nmod(թագավորը, Արշակ)
nmod(King, Arshak)
~~~

~~~ sdparse
առաջին նախագահ Լևոն Տեր - Պետրոսյանը \n the-first president Levon Ter - Petrosyan 
amod(նախագահ, առաջին)
nmod(Պետրոսյանը, նախագահ)
flat(Պետրոսյանը, Լևոն)
flat(Պետրոսյանը, Տեր)
amod(president, the-first)
nmod(Petrosyan, president)
flat(Petrosyan, Levon)
flat(Petrosyan, Ter)
~~~

Note that the same thing can be also expressed using an [apposition](appos).
In the case of apposition, the title follows the modified name and is separated by a punctuation symbol:

~~~ sdparse
Լևոն Տեր - Պետրոսյանը ՝ առաջին նախագահը \n Levon Ter - Petrosyan , the-first president
flat(Պետրոսյանը, Լևոն)
flat(Պետրոսյանը, Տեր)
punct(Պետրոսյանը, ՝)
amod(նախագահը, առաջին)
appos(Պետրոսյանը, նախագահը)
flat(Petrosyan, Levon)
flat(Petrosyan, Ter)
punct(Petrosyan, ,)
amod(president, the-first)
appos(Petrosyan, president)
~~~

See the definitions of [nmod:poss](nmod-poss): and [nmod:npmod](nmod-npmod) relations.