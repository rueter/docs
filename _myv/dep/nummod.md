---
layout: relation
title: 'nummod'
shortdef: 'numeric modifier'
udver: '2'
---
A numeric modifier of a noun is any [number](u-pos/NUM) phrase
that serves to modify the meaning of the noun with a quantity.

~~~ sdparse
Сэм сэвсь 3 реветь
nummod(реветь, 3)
~~~

~~~ sdparse
Сэм ютавтсь ниленьгемень долларт
nummod(долларт, ниленьгемень)
~~~

~~~ sdparse
Сэм ютавтсь $ 40
nummod($, 40)
~~~

Note that indefinite quantifiers such as _зярыя, ламо_ are tagged
[u-pos/DET]() rather than [u-pos/NUM](). 
Therefore their relation to the quantified noun is not `nummod` but
[det]():

~~~ sdparse
Сэм сэвсь ламо реветь
det(реветь, ламо)
~~~
