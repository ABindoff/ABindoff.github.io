---
published: true
title: Kalman Filter tutorial
layout: post
---

One of the projects I'm working on involves estimating how likely it is that someone is experiencing cognitive impairment (or decline). Any individual neuropsychological test carries a whole lot of uncertainty (noise) and so several tests are used at multiple time points. This allows us to quantify some of the measurement error but, because patients are human beings, and humans get better at taking tests with practise, it is likely that people improve on test scores simply by taking the test. It's a complicated business, and accounting for this uncertainty when estimating cognitive states is something our research group would like to improve upon.

One approach might be to make use of a Kalman Filter (or some variant thereof). Kalman Filters account for state uncertainty to give an optimised estimate in dynamic systems. Think about getting a rocket to the moon. Each estimate of the rocket's position and current trajectory comes with uncertainty. Combining information about current position and trajectory at multiple time points enables the Kalman Filter to "smooth" estimates, optimising the estimated position and trajectory.

Most of the articles and tutorials on Kalman Filtering that I've seen have been a bit dense, but this one hits the sweet spot for me -

[A first look at the Kalman Filter](http://lectures.quantecon.org/jl/kalman.html "A first look at the Kalman Filter")

...and conveniently someone has put some R code up on gitub

[Kalman Filter visualised with R](https://gist.github.com/mages/52cf15bf8c9563c3518f "Kalman Filter visualised with R")
