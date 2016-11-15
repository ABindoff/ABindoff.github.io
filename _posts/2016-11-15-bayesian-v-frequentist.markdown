---
published: true
title: Bayesian vs frequentist statistics, a maths-free attempt
layout: post
---

*Frequentist* | *Bayesian*
------|------
Probability is the long-run frequency if an experiment is repeated many times|Probability is allowed to be a subjective statement about how likely an event is to occur
Parameters are a fixed quantity that cannot change.|	Data are fixed and parameters are a probability distribution that may be updated.
Distinction between random variables and parameters|	Everything is a random variable.
Dichotomous “reject the null” or “fail to reject the null” based on pre-determined alpha.|	Summarise our confidence (or belief about) a parameter that we estimate from the data.
95% CI: if you repeat an experiment 100 times and calculate a CI each time, the true value of the parameter would be included 95 times.|	95% Credibility Interval: given the data, the parameter is estimated as a probability distribution and the uncertainty summarised within this interval*.
Effects are either fixed or random variables|	All effects are random variables
Prior knowledge is OK to use when estimating random variables (where prior distribution is well founded)|	Prior knowledge is used (good or bad depending on how this is done and the purpose of the analysis)
Inference by testing a null hypothesis [usually] against an alternative hypothesis (i.e test the observed data to see how unlikely it would be against the null hypothesis).|	Not one single approach to inference, but characterised by an emphasis on making a credible estimate that informs our belief (via the ‘posterior distribution’).
Strength in testing hypotheses about the nature of things. “Evaluative paradigm” (Casella)|	Strength in building knowledge about a parameter, particularly for making practical decisions. “Modelling paradigm” (Casella)
Requires little computational power.|	Requires a lot of computational power (relative to most frequentist methods).
Results rely on assumption that data were from a controlled experiment (often not true!)|	Assumptions are stipulated (and ideally, defensible).

***Note:** many people mistakenly believe that the Bayesian interpretation of the 95% Credibility Interval is how the 95%CI should be interpreted in frequentist statistics.

*References*
Casella, G. http://www.stat.ufl.edu/archived/casella/Talks/BayesRefresher.pdf
Goddard, M. http://jvanderw.une.edu.au/Introduction_to_Bayesian_Statistics1.pdf
Gelman, A. et al. Bayesian Data Analysis (3rd Ed)  CRC Press, Fl. USA

