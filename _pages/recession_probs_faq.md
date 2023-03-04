---
title:  "U.S. Recession Probabilities FAQ"
layout: single
classes: wide
permalink: /recession_probs_faq/
author_profile: true
comments: true
---

<HR>

<b>1) When are the recession probabilities updated?</b>

Recession probabilities are updated each time a full month of additional data for all four series is obtained. This is generally on or just before the first of each month.

<b> 2) How are these probabilities calculated? </b>

Monthly smoothed recession probabilities are calculated from a dynamic-factor Markov-switching (DFMS) model applied to four monthly coincident variables: non-farm payroll employment, the index of industrial production, real personal income excluding transfer payments, and real manufacturing and trade sales. This DFMS model was originally developed in Chauvet, M. “An Econometric Characterization of Business Cycle Dynamics with Factor Structure and Regime Switches,” International Economic Review, 1998. 

The smoothed recession probabilities reported above are calculated from the DFMS model using Bayesian estimation techniques developed in Kim and Nelson (1998, Review of Economics and Statistics). Smoothed recession probabilities calculated from the same DFMS model, but using maximum likelihood estimation techniques are produced by [Marcelle Chauvet](https://sites.google.com/site/crefcus/probabilities-of-recession)

The differences between the two sets of probabilities are primarily due to the priors used in Bayesian estimation of the model, which tend to make the probabilities calculated using Bayesian techniques less sensitive to incoming data.

<b> 3) How should I interpret these probabilities as a recession signal? </b> 

Historically, three consecutive months of smoothed probabilities above 80% has been a reliable signal of the start of a new recession, while three consecutive months of smoothed probabilities below 20% has been a reliable signal of the start of a new expansion. For an analysis of the performance of the model for identifying new turning points in real time, see:

[Chauvet, M. and J. Piger, “A Comparison of the Real-Time Performance of Business Cycle Dating Methods,” *Journal of Business and Economic Statistics*, 2008]({%link /assets/files/Chauvet_Piger_2008_JBES.pdf%}).

Other studies that have analyzed real-time turning point identification using alternative models and / or rules for converting probabilities into recession signals include:

Chauvet, M. and J. D. Hamilton, “Dating Business Cycle Turning Points in Real Time,”Nonlinear Time Series Analysis of Business Cycles, C. Milas, P. Rothman, and D. van Dijk (eds.), Elsevier Science, Amsterdam, 2006.

[Chauvet, M. and J. Piger, “Identifying Business Cycle Turning Points in Real Time,” *Federal Reserve Bank of St. Louis Review*, 2003]({%link /assets/files/Chauvet_Piger_2003_FRBSTLReview.pdf%}).

<b> 4) What is a smoothed recession probability? </b> 

A smoothed recession probability is based on the most recent data available, and is thus potentially influenced by data that wasn’t available the first time a recession probability for a particular month was calculated. Smoothed recession probabilities will be revised over time as additional data becomes available, and as initially released data is revised. The effect of these revisions is to “smooth” away some of the spikes in the recession probabilities that occur in real time. 

By contrast, a “real-time” recession probability is the first probability of recession that one could obtain for a given month. Note that the most recent smoothed probability is also a real-time probability. 

<b> 5) Can I access earlier releases of the recession probabilities? </b> 

Yes, the smoothed recession probability series produced for each release back to the August 1, 2006 release is available in [Excel format here]({%link /assets/files/History_of_Real_Time_Recession_Probabilities.xlsx%}).

<b> 6) Were there changes to calculation of smoothed recession probabilities associated with the COVID-19 Recession? </b> 

Yes, beginning with the December 23, 2020 release, smoothed recession probabilties are computed allowing a change in model parameters associated with the period from March 2020 through July 2020.
