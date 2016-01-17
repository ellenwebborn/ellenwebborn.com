---
layout: post
title: Current projects
date: August 20, 2013
---

Interested in working with me? See below for descriptions of several potential projects. If you have interest and abilities that line up with one of these, feel free to contact me.

1. Review of methods for direct observation of behavior. Several different methods for recording direct observations of behavior are commonly used in single-case research and other areas of psychology; prominent methods include continuous duration recording, momentary time sampling, and partial interval recording. Textbook advice about appropriate use of different methods is conflicting and often ambiguous, and simulation studies evaluating the operating characteristics of different methods also yield mixed results. The goals of this project are to: find and organize the current guidance about direct observation procedures; understand the basis of that guidance (e.g., simulation studies, heuristic models); and relate the guidance to a unifying statistical framework, by translating claims and conclusions into the terms of a parametric model (known as an alternating renewal process). This project would be appropriate either for a quantitative methods student who is interested in learning about direct observation methods for measuring behavior or for a student from school psychology, counseling psychology, or special education who is familiar with direct observation methods and interested in learning about statistical models for the data they generate.

2. Applications of meta-analysis for single-case studies of free-operant behavior. I have recently proposed a suite of new effect size metrics for quantifying treatment effects in single-case studies of free-operant behavior. The crux of this line of work is that it is important to use effect size metrics that are comparable across different methods of recording direct observation data. This project will involve: reviewing several published systematic reviews that incorporate evidence from single-case studies, in order to determine what measurement procedures were used to collect data, then re-analyzing the data from one or more of these studies, using the newly proposed effect size metrics and methods. This project would be appropriate for a special education student who is familiar with meta-analysis.

3. Applications of design-comparable effect size measures for longitudinal studies. Co-authors and I have recently proposed a method of estimating effect sizes from single-case studies (or other types of longitudinal designs) that are in the same metric as Cohen's d-type effect sizes from conventional between-subjects experiments. The goals of this project are to: develop exemplar code that implements effect size calculations in several major statistical packages (including SPSS, SAS, Stata, and R); review the algorithms available in major statistical packages for estimating the uncertainty of variance components (i.e., information matrices); develop further applications and extensions to the proposed effect sizes. This project would be appropriate for a quantitative methods student who is familiar with estimation of hierarchical linear models in SPSS, SAS, and other major statistical software platforms.

4. Programming information matrices for hierarchical linear modeling. The Fisher information plays a pivotal role in hierarchical linear models, both as an approximate estimates of parameter uncertainty and as a key component of small-sample hypothesis tests such as those of Kenward and Roger (1997,2009). The goals of this project are to: create an R package for constructing analytic information matrices for HLM models estimated with the well-known nlme package;  also add functions for the revised Kenward & Roger hypothesis tests; and evaluate the performance of different information matrices (expected, observed, and average) for calculating degrees-of-freedom adjustments in the context of effect size estimation. This project could be appropriate for a quantitative methods student or a statistics student who has strong programming skills and wants to 1) learn more about the statistical guts of HLM estimation and 2) level-up on their R programming by designing a publishable package.

5. A discrete-time Markov chain model for partial interval recording data. Partial interval recording is a commonly used method for recording direct observations of human behavior. Data generated by this method is problematic because, as typically analyzed, it yields upwardly biased measures of prevalence (the proportion of time that a behavior occurs). This shortcoming can be addressed by modeling the data using a discrete-time Markov chain and using maximum likelihood methods to estimate parameters corresponding directly to prevalence and incidence (the frequency with which new behaviors occur). The goals of this project are to create an R package implementing maximum likelihood estimation (and possibly other methods) for partial interval recording data and evaluate this estimation approach using asymptotic theory and simulation. This project could be appropriate for an advanced quantitative methods student or statistics student who is interested in learning about Markov chain models and who has strong programming skills.