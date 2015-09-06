---
layout: post
published: true
description: ""
headline: ""
modified: ""
categories: 
  - Stats
tags: stats
imagefeature: ""
mathjax: false
featured: false
comments: false
title: "t-test and SD vs SE (SEM)"
---

## t-test
- [t-test on Wiki](https://en.wikipedia.org/wiki/Student%27s_t-test#Independent_two-sample_t-test) for 2 samples
  - equal sample size N, equal variance
      - variance: standard deviation (SD) of population
  - equal variance, UNequal size
  - UNequal variance
- assumptions & unbalance
	- [example 1](http://stats.stackexchange.com/questions/45666/small-and-unbalanced-sample-sizes-for-two-groups-what-to-do)
    	- unequal variance may be informative itself !
    - [example 2](http://stats.stackexchange.com/questions/31326/how-should-one-interpret-the-comparison-of-means-from-different-sample-sizes)
    - [details of assumption violation](http://www.basic.northwestern.edu/statguidefiles/ttest_unpaired_ass_viol.html)

## SD vs SE(SEM) -- deviation vs error
- SD: standard **deviation**, [wiki link](https://en.wikipedia.org/wiki/Standard_deviation)
- SE: standard **error** (of **sampling distibution** of an **statistic**, e.g. mean, then is SEM - SE of Mean), [wiki link](https://en.wikipedia.org/wiki/Standard_error)
- [SD vs SEM](http://www.graphpad.com/guides/prism/6/statistics/index.htm?stat_semandsdnotsame.htm)
	- [sem = sd/sqrt(n)](http://davidmlane.com/hyperstat/A103735.html)
    - [more](https://explorable.com/standard-error-of-the-mean)
- [SEM: good explanation figures](http://www.biostathandbook.com/standarderror.html)
