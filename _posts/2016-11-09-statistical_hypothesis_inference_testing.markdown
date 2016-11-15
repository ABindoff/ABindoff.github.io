---
published: true
title: Key points from "Statistical tests, P values, confidence intervals, and power: a guide
to misinterpretations" (Greenland et al., 2016)
layout: post
---

As a newly minted statistician working in a busy, multi-disciplinary lab I'm quickly discovering how an undergraduate degree in statistics just scratches the surface of many problems that require deeper attention if a statistician is to add any value (other than "help desk" duties) to working scientists. Many of the issues that we are asked to address require some degree of compromise (or discomfort, or even contradiction...) We defend null-hypothesis statistical testing partly by acknowledging the epistemological issues that it inherits, or even raises - but sometimes we defend it against misperceptions about the process itself or how to interpret the results. In an effort to find better ways to communicate statistical ideas I came across an accessible and to-the-point essay by Greenland et. al (2016) which aims to address misinterpretations of statistical tests, P values, confidence intervals and power. I have summarised some key points below mostly for my own benefit. The essay is concise and worth reading, so if you wish to go straight to the source, follow this link: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4877414/pdf/10654_2016_Article_149.pdf


- statistical inference depends on assumptions about how data were collected, analysed, and presented
- these assumptions are embodied in a statistical model
- the statistical model is a mathematical representation of data variability, and an ideal model would capture and explain all sources of variability
- "the *null hypothesis* is not the only hypothesis one may test
- "The P value is [then] the probability that the chosen test statistic would have been *at least* as large as its observed value if *every* model assumption were correct, including the test hypothesis"
- The P value on its own (whether big or small) does not tell us which assumptions are incorrect or correct (i.e it does not necessarily tell us that we can reject the null), and is more correctly interpreted as a measure of the agreement between the data and the model used to compute the P value.
- The P value is computed *from* a set of assumptions, so it can never refer to the *probability of those assumptions*; thus it is incorrect to say that because you computed p = 0.01 there is a 1% probability that chance alone produced the observed association. Rather, if *chance alone* produced the discrepancy in our model (e.g an observed difference between test and treatment groups under the null hypothesis) we would expect to see this difference (or larger) no more than 1% of the time. If that seems like a subtle difference - read it again!
- Unless p = 1, there is *some* effect or association so it is incorrect to conclude that there is no effect or association just because p > 0.05. To me, this seems like a laboursome and inconvenient point, but it should not be ignored, and in fact I would deliberately include statements about the difference between two (or more) means in its scope.
- Why report confidence intervals? While a P value can be considered a measure of how well the data fits the model (and thus flag any discrepancies, for example under the null hypothesis), CIs reflect the range of effect sizes compatible with the data. There is some evidence that this helps researchers to make better interpretations, moving from "dichotomous thinking" to "estimation thinking" http://journal.frontiersin.org/article/10.3389/fpsyg.2010.00026/full
- If two studies both have 80% power to show p <= .05, the probability that one is significant and the other isn't is 0.8*(1-0.8) + (1-0.8)*0.8 = 0.32. Roughly 1/3rd of the time - can anyone say "replication crisis"?


*References*
Greenland et al., (2016) "Statistical tests, P values, confidence intervals, and power: a guide
to misinterpretations" European Journal of Epidemiology 31:337-350
