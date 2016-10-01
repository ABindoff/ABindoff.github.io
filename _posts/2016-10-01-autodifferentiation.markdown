---
published: true
title: Auto-differentiation in R using TMB
layout: post
---

The parameters of likelihood equations can often only be estimated using numerical methods. Statisticians employ algorithms which find minimums on the likelihood gradient surface. Auto-differentiation (AD) is a method of computing these gradients, i.e the partial derivatives of the likelihood with respect to all model variables. AD exploits the fact that computer programs execute a series of elementary operations, applying the chain rule of calculus to these operations. Other (perhaps more familiar) methods exist, but for high-dimensional models, particularly non-linear models, AD provides a neat and highly precise solution.

AD has a reasonably well developed history in some fields (e.g stock assessments in fisheries research), but has suffered from serious underutilisation in most fields. It is an emerging technology, helped in part by the development of TMB for model building using AD in R. There are not many entry-level tutorials, but I will update this list as I find them:

[Tutorial using TMB in R and some familiar applications](http://seananderson.ca/2014/10/17/tmb.html "TMB Tutorial")

[Tutorial using TMB in R with some more detail](https://github.com/kaskr/adcomp/wiki/Tutorial "TMB Tutorial on Github")

[A Hitch-hikers Guide to Auto-Differentiation (Hoffman, 2016)](https://arxiv.org/pdf/1411.0583v5.pdf "Guide to AD")