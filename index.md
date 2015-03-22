---
title       : A Simple Slidify deck
subtitle    : Cursera project assignment
author      : Kaushik Mahaldar
job         : Evaluates simple R statements 
date        : Sunday 22 March 2015 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Problem

the government want to take decision on the budget for agricultural aids to farmers. They have to analyze data of last 10 years and predict the agricultural issues of this year.

Actually I am not considering all data , we will just take the mean value of last ten years budget.

---

## Proposed Solution

- Create imaginary dataset of  budget of last 10 years
- Calculate the mean
- In future add more logic and data

define data 

```r
budgetlist <- c(459, 340, 234, 67890, 234567, 171929, 1231231, 12312312, 54132, 324242)
```
Predict the budget

```r
mean(budgetlist)
```

```
## [1] 1439734
```

calulate few more statement

```r
550 * 52 / 500000 * 100
```

```
## [1] 5.72
```

---

## Slide with more R Code and Output


```r
summary(cars)
```

```
##      speed           dist       
##  Min.   : 4.0   Min.   :  2.00  
##  1st Qu.:12.0   1st Qu.: 26.00  
##  Median :15.0   Median : 36.00  
##  Mean   :15.4   Mean   : 42.98  
##  3rd Qu.:19.0   3rd Qu.: 56.00  
##  Max.   :25.0   Max.   :120.00
```


![plot of chunk unnamed-chunk-5](assets/fig/unnamed-chunk-5-1.png) 

---

## Thanks 

I hope you enjoyed my slides

Thanks you for your time .


---
