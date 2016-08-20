---
layout: page
title: Chapter 2 - Probability
permalink: /pages/chapter2/
---


## Learning Outcomes

* Define trial, outcome, and sample space.
* Define and describe the law of large numbers.
* Distinguish disjoint (also called mutually exclusive) and independent events.
* Use Venn diagrams to represent events and their probabilities.
* Describe probability distributions.
* Distinguish between marginal and conditional probabilities.
* Use tree diagrams and/or Bayes Theorem to calculate conditional probabilities and probabilities of intersection of non-independent events.
* The expected value of a discrete random variable is computed by adding each outcome weighted by its probability.  
$$ E(X)=\mu =\sum _{ i=1 }^{ k }{ { x }_{ i }P\left( X={ x }_{ i } \right)  }  $$
* The variance of a discrete random variable is computed by adding each squared deviation of an outcome from the expected value weighted by its probability. The standard deviation is the square root of the variance.  
$$ Var(X)={ \sigma  }^{ 2 }=\sum _{ i=1 }^{ k }{ { \left( { x }_{ i }-\mu  \right)  }P\left( X={ x }_{ i } \right)  }  $$
* The average of a linear combination of discrete random variables is computed as the sum of their averages, weighted by the constant multipliers.
* The variance of a linear combination of independent discrete random variables is computed as the sum of their variances, weighted by the square of the constant multipliers.
* The distribution of a continuous random variable is described by the probability density function.
* The total area under the density curve is 1.
* Probabilities under the density curve can be calculated as the area under the curve.
* The probability of a continuous random variable being exactly equal to a value is 0, since there is no area under the curve at a given location.

## Assignments

### Homework

*OpenIntro Statistics*

* Practice: 2.5, 2.7, 2.19, 2.29, 2.43
* Graded: 2.6, 2.8, 2.20, 2.30, 2.38, 2.44

### Lab

The labs are available in the `IS606` R package. To start the first lab, use the `startLab` function. This will copy the lab to your current working directory and rename the file according to your computer username (as returend by `Sys.info()['user']`). If this is incorrect, then either provide the `file-prefix` parameter to `startLab`, or rename the file after it has been copied.


```r
IS606::viewLab('Lab2')
IS606::startLab('Lab2')
```

## Readings

* [OpenIntro Statistics slides](https://github.com/jbryer/IS606Fall2015/raw/master/Slides/OpenIntro/os2_slides_02.pdf)

* Matloff, N. (2009). [*From Algorithms to Z-Scores: Probabilistic and Statistical Modeling in Computer Science*](https://github.com/jbryer/IS606Fall2015/blob/master/Textbook/ProbStatBook.pdf?raw=true). Available from [http://heather.cs.ucdavis.edu/probstatbook](http://heather.cs.ucdavis.edu/probstatbook).


## Videos

[Would You Take This Bet?](https://www.youtube.com/watch?v=vBX-KulgJ1o)

<iframe width="560" height="315" src="https://www.youtube.com/embed/vBX-KulgJ1o" frameborder="0" allowfullscreen></iframe>

[The Monty Hall Problem](https://www.youtube.com/watch?v=mhlc7peGlGg)

<iframe width="420" height="315" src="https://www.youtube.com/embed/mhlc7peGlGg" frameborder="0" allowfullscreen></iframe>

