---
layout: relation
title: 'csubj:pass'
shortdef: 'clausal passive subject'
udver: '2'
---

A clausal passive subject is a clausal syntactic subject of a passive clause.

~~~ sdparse
Օրերս մամուլում գրվել էր , որ նա ևս պաշտոնանկ կարվի : \n
csubj:pass(գրվել, կարվի)
aux(գրվել, էր)
obl(գրվել, Օրերս)
obl(գրվել, մամուլում)
mark(կարվի, որ)
~~~

~~~ sdparse
Նամակում ասվում էր , որ Հայաստանը պատրաստ է զարգացնել իր հարաբերությունները ԵՄ հետ ։ \n
csubj:pass(ասվում, պատրաստ)
aux(ասվում, էր)
obl(ասվում, Նամակում)
xcomp(պատրաստ, զարգացնել)
mark(պատրաստ, որ)
~~~

~~~ sdparse
Կատարվեց , ինչ սպասվում էր : \n Happened , what was expected .
csubj(Կատարվեց, սպասվում)
aux(սպասվում, էր)
mark(սպասվում, ինչ)
csubj(Happened, expected)
aux(expected, was)
mark(expected, what)
~~~
