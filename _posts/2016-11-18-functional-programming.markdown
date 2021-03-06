---
published: true
title: Negate(%in%)
layout: post
---

R is a *functional* language, and it is useful to think of functions in R like you would think about mathematical functions, rather than subroutines (as you might in an imperative language). It also means you can do some potentially malicious things...

> \`+\` <- \`-\`

> 2 + 3

-1

...and some potentially useful things...

We want to find any elements of a not also in b. Finding elements of a that are in b is easy:

> a <- c(1,2,3)

> b <- c(2,3,4)

> a %in% b

[1] FALSE  TRUE  TRUE

> a[a %in% b]

[1] 2 3


A concise solution to find elements of a not in b is:

> !(a %in% b)

[1]  TRUE FALSE FALSE

which is essentially 1-(a %in% b) returned as a vector of logicals. More artfully we might do this 

> \`%notin%\` <- Negate(\`%in%\`)

> a %notin% b

[1]  TRUE FALSE FALSE

> a[a %notin% b]

[1] 1



