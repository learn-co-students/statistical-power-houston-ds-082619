---
title: 
layout: post
weight: 10
hidden: true
---

===


**Course**: DS   <br/>
**Mod**: Mod 3 V2               <br/>
**Topic**:  Statistics <br/>
**Amount of time**:  60 minutes  <br/>
**Author**: Alison Peebles Madigan and Laura Colon-Melendez

Ported from the ds-lesson-starters repository [here](https://github.com/learn-co-curriculum/ds-lessons-starter/tree/master/effect-power).


***

#### Lesson Summary:

A quick recap of hypothesis testing leads the way to a discussion on Type I and Type II errors in hypothesis testing. Students solve a quick example where they have to state what Type 1 and 2 errors are in a particular scenario. Next, students write code to run simulations for computing Type I and Type II error rate. Statistical power is introduced next, which leads to a discussion of effect size and a quick example to compute Cohen's d for two samples. After finishing the example, students perform a simulation to compute the power of a statistical hypothesis test. Next, students create visualizations to observe the effect of changing sample size, effect size, and significance level on power.  Finally, statistical power analysis is presented as a tool for experimental design, and students use the `statsmodels` library to compute power, detectable effect sizes, and sample size needed to achieve desired result in a test in a case study.

#### Topic:

Statistics

#### Learn.co material:

[Effect Sizes](https://github.com/learn-co-curriculum/dsc-effect-sizes)

[Type 1 and Type 2 Errors](https://github.com/learn-co-curriculum/dsc-type-1-and-2-error)

[Type 1 and Type 2 Errors - Lab](https://github.com/learn-co-curriculum/dsc-type-1-and-2-error-lab)

[Introduction](https://github.com/learn-co-curriculum/dsc-statistical-power-anova-introduction)

[Statistical Power](https://github.com/learn-co-curriculum/dsc-statistical-power)

[Statistical Power - Lab](https://github.com/learn-co-curriculum/dsc-statistical-power-lab)

#### Prerequisite knowledge:

* Students should be able to set null and alternative hypotheses. 
* Students should be able to perform z-tests and t-tests using Python.
* Students should know how to use `scipy.stats` to generate normal random variables and how to draw samples from these instances.

#### Prerequisite Learn.co material:

[Introduction to Experimental Design](https://github.com/learn-co-curriculum/dsc-experimental-design)
[P-values and the Null Hypothesis](https://github.com/learn-co-curriculum/dsc-p-values-and-null-hypothesis)
[Conducting T-tests](https://github.com/learn-co-curriculum/dsc-t-tests)
[One Sample T-Test - Lab](https://github.com/learn-co-curriculum/dsc-one-sample-t-tests-lab)
[Two Sample T-Test - Lab](https://github.com/learn-co-curriculum/dsc-two-sample-t-tests-lab)

#### Learning goals for this lesson:

* Students can differentiate between Type I and Type II error.
* Students can create simulations to compute Type I and Type II errors, as well as power. 
* Students can compute effect size using Python.
* Students can demonstrate the relationship between power, alpha, sample size, and effect size. 
* Students will be able to conduct statistical power analysis in Python. 


#### Relevant learning goals from Airtable: 

* HYPOTHESIS_TESTS.2.recbmr3VoVj5LNLuw
* HYPOTHESIS_TESTS.3.recjrNwrmDGKr92ab
* POWER_ANOVA.2.recNqePoI8sLGdhqz
* POWER_ANOVA.2.recXjEPPnHc0LI65r
* POWER_ANOVA.3.recJIJGE3ONVeKdBS


#### Misconceptions / Notes

* Statistical power is a tricky concept to teach, but crucial to good experimental design. 
* Students may be confused by the difference between Type I and Type II error. Spend time going over the confusion matrix. 

#### Materials
- Ipython notebook 

#### Vocab / Concepts 
* Type I and Type II errors (alpha and beta)
* Statistical power
* Effect size
* Cohen's d
* Statistical power analysis

#### Lesson Outline:

* Hypothesis testing, Type 1 and Type 2 errors (15 minutes)
    * Example simulation to compute Type I error - Guided
    * Example simulation to compute Type II error - Students fill missing code. 
* Statistical Power (20 minutes)
    * Effect size: Cohen's d (5 minutes)
    * Students use the same code they used to compute Type II error to compute power (5 minutes)
    * Visualizations to show how power changes with effect size, sample size, and alpha (10 minutes) 
* Power analysis for Experimental Design (20 minutes)
    * A case study is presented. Students compute power of a poorly designed experiment, and then the sample size needed to get to a power of 80% using `statsmodels` library. 
    * An additional case study is presented. Complete it if time permits, if not, leave as an exercise to students. 
* Summary (5 minutes)
