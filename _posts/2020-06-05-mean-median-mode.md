---
title: "Why Mean, Median and Mode??"
date: 2020-06-03 5:00:00
---

Ever wondered why you are learning Mean, Mode and Median as a prerequisite for machine learning. Today I will explain why you need to learn and where you need to use them. First let's understand what are these.

- It is really important to learn what is Mean, Median and Mode as a prerequisite for data science.
- It gives a single value that attempts to describe a set of data by identifying the central position within that set of data.
- These 3 terms are valid measures of central tendency of the data, but under different conditions, some measures of central tendency become more appropriate to use than others.


### Mean

- The mean (or average) is the most popular and well-known measure of central tendency.
- We can calculate the mean for both discrete and continuous data, although its use is most often with continuous data.
- Formula
![\Large \overline{x} = \frac{x_1 + x_2 + x_3 + ... + x_n}{n}}](https://latex.codecogs.com/svg.latex?x%3D%5Cfrac%7B-b%5Cpm%5Csqrt%7Bb%5E2-4ac%7D%7D%7B2a%7D)
![\begin{equation} \overline{x} = \frac{x_{(1)} + x_{(2)} + x_{(3)} + ... + x_{(n)}}{n} \end{equation}](https://latex.codecogs.com/svg.latex?x%3D%5Cfrac%7B-b%5Cpm%5Csqrt%7Bb%5E2-4ac%7D%7D%7B2a%7D)

- we can also write this queation as
\begin{equation} \overline{x} = \frac{\sum_{i=1}^{n} x_{(i)}}{n} \end{equation}
    - x_bar = Mean value of data
    - x1, x2, x3, ..., xn = n different values of data
    - n = total no of samples
- The mean is equal to the sum of all the values in the data set divided by the number of values in the data set.
- one of its important properties is that it minimises error in the prediction of any one value in your data set. That is, it is the value that produces the lowest amount of error from all other values in the data set.
- Another important property of the mean is that it includes every value in your data set as part of the calculation.
- Also, the mean is the only measure of central tendency where the sum of the deviations of each value from the mean is always zero.

## Example
- Let's consider an example where we will be finding the average salary of a Hyderabad city

| worker | salary |
|--------|--------|
|   1    |   12000|
|   2    |   13000|
|   3    |   12000|
|   4    |   14000|
|   5    |   15000|
|   6    |   13000|
|   7    |   15000|
|   8    |   16000|
|   9    |   17000|
|  10    |   14000|
|  11    |   13000|
|  12    |   12000|

<img src="https://latex.codecogs.com/svg.latex?\Large&space;x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}" title="\Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}" />

![\Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}](https://latex.codecogs.com/svg.latex?x%3D%5Cfrac%7B-b%5Cpm%5Csqrt%7Bb%5E2-4ac%7D%7D%7B2a%7D)



### Code

<a href="https://github.com/udaykiranreddykondreddy/Code-for-learn-machinelearning/tree/master/hyperparameter_tuning"  class="btn btn-info" role="button" target="_blank"> <i class="fa fa-github fa-2x" aria-hidden="true"></i></a>
