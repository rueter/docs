---
layout: relation
title:  'nmod:poss'
shortdef : 'possessive modifier'
udver: '2'
---

This relation is a subtype of the [nmod]() relation, which covers only those possessives that are expressed using the dative [Case](Case). If a possessive [determiner](DET) is used, the relation is labeled [det]().

~~~ sdparse
տնօրենի գրասենյակը \n office of-the-director.`Dat`
nmod:poss(գրասենյակը, տնօրենի)
nmod:poss(office, of-the-director.`Dat`)
~~~

~~~ sdparse
նրա գրասենյակը \n his office
det(գրասենյակը, նրա)
det(office, his)
~~~

In conjunction with the [case]() relation, `nmod:poss` provides a uniform analysis for the possessive alternation:

~~~ sdparse
թշնամու դեմ պատերազմը \n the-war against the-enemy
nmod:poss(պատերազմը, թշնամու)
case(թշնամու, դեմ)
nmod:poss(the-war, the-enemy)
case(the-enemy, against)
~~~