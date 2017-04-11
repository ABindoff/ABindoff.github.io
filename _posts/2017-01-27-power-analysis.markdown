---
published: true
title: Consulting a statistician for an a-priori power analysis
layout: post
---

These are some short, general guidelines for information that it is helpful to provide your helpful statistician when you are asking for an a-priori power analysis:

1. *be very specific about your aims and hypotheses:* assume that the statistician doesn't know anything about your work or your planned experiment. If they have to work too hard to understand it, (a) so will the funding body or ethics committee so this is a good opportunity to hone your pitch, (b) they will have to invest too much time trying to figure out what you're trying to do and this isn't a good use of their time, (c) they might misunderstand what you are trying to achieve and unintentionally give you bad advice.

2. *your statistician needs to be able to estimate an effect size:*  don't get too hung up on how they will do this (that's their job), and you don't need to calculate *d*, or *f^2*, or other statistics for them - but you will need to provide supporting literature or data from pilot studies that are somewhat comparable to the study that you are proposing. 

3. *be prepared to be told that your experiment is under-powered:*  this isn't necessarily a bad thing but it's a good reason to consult your friendly statistician early in case you need to reconsider your measures or the design of your experiment.


A useful hypothesis should be **operationalised**, clearly identifying the dependent and independent variables (DVs and IVs). What are you measuring and how are you measuring it? What are the units or scales that the variables are measured on? For example, "We will investigate the effect of extreme cold on decision making ability" doesn't tell the reader how the cold will be applied or measured, doesn't tell the reader how "decision making ability" will be measured, and in fact it doesn't even tell the reader what species the study subject will be. Even though some of these things may be explained in the Background or Aims, the statement of hypothesis is the place to be highly specific. A clear hypothesis will make it easier for you to find supporting literature, and for the statistician to compute the power of the experiment.

A better statement of hypothesis would be something like "We anticipate that error-rate and time to complete a simulated rescue planning task will be significantly negatively correlated with air temperature inside the simulator environment for trained personnel". Even though this statement still leaves some room for discussion (e.g how do we define "trained personnel"?), it gives the statistician a clearer idea of what the measures will be and how to analyse the resultant data. If previous studies have identified the strength of an "error rate" and "air temperature" relationship, or a "time to complete" and "air temperature" relationship, or *both* - then it is relatively easy to estimate how many observations will be required for a sufficiently powered experiment. There is one independent variable and two dependent variables in the stated hypothesis (can you identify them?), and the direction of the relationship is clearly identified. It is a useful exercise to plot these relationships, because the IVs and DVs become obvious pretty quickly (if it is possible to plot the expected relationship).

### How is the power of an experiment calculated?

Briefly, what we really want to know is how many times (as a percentage) we would expect to reject the null hypothesis (e.g no difference between the means of groups) if we repeated the experiment many times (for a given effect size). For many experimental designs, this can be calculated from parametric distributions, but as the complexity of the proposed analysis (the model) increases it is more likely that the power of an experiment will need to be calculated by simulation. It is NOT good enough to say "for a sample size of n we expect power to reject the null hypothesis of 0.8 at alpha = 0.05 with an effect size of d" (as ubiquitous as this "not-a-power-analysis" is in some fields of science). Why?  Indeed the statement is usually true, but there needs to be evidence to support the claimed effect size. Every proposed experiment ever could be approved and funded if we got to choose our effect size in advance.



