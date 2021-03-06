# Feature Engineering - Introduction

[Back to Index](../README.md)

## Objective

Learn feature engineering

## Reference

### Essential Reading

* [Why data prep is important](https://machinelearningmastery.com/data-preparation-is-important/)
* [Feature Engineering, how and why](https://machinelearningmastery.com/discover-feature-engineering-how-to-engineer-features-and-how-to-get-good-at-it/)
* [Chapter 5. Basic feature engineering](https://learning.oreilly.com/library/view/real-world-machine-learning/9781617291920/kindle_split_015.html)  of the book [Real World Machine Learning](https://learning.oreilly.com/library/view/real-world-machine-learning/9781617291920/)

### Extra Reading

* [Fundamental Techniques of Feature Engineering for Machine Learning](https://towardsdatascience.com/feature-engineering-for-machine-learning-3a5e293a5114)
* [Feature Engineering exercises @ Kaggle](https://www.kaggle.com/learn/feature-engineering)

## Checklist

After completing the exercises below, you should be comfortable with

- understand why feature engineering is very important in machine learning
- have a good overview of feature engineering tasks
- picking features that are relevant

## Exercises

### Difficulty Level

★☆☆  - Easy  
★★☆  - Medium  
★★★  - Challenging  
★★★★ - Bonus

### A - Outlier Detection

### A-1 : House Sales Data (★★☆)

Read the [house-sales-simplified.csv](https://elephantscale-public.s3.amazonaws.com/data/house-prices/house-sales-simplified.csv).  
We are going to find outliers in sale price.

First, describe and visualize `saleprice` attribute.  How can we know there are outliers?  
Hint: You can look at `standard deviation`

We can eliminate top 10% and bottom 10% to find middle prices.

As next step, we segment house prices per bedrooms.

We also need to take `zipcode` into account when determining prices.

So our final assesment, we need to calculate prices  per-bedroom, per-zipcode.  
Come up with your assesment of outier detection.

### More Exercices

* [Pandas cleanup](https://www.w3resource.com/python-exercises/pandas/missing-values/index.php)

---

## [Index](../README.md)
