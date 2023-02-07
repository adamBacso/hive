---
title: "changing a variable"
alias: 
type: note
subject: math
tags:
 - math
 - statistics
created: 2023.01.23 13:05
created_by: Ádám
TARGET DECK: math
summary: 
status: draft 
---
>Used when we want to examen a **new dataset** that is based on a  previous dataset

>Can be used to easily determine the average (by subtracting a value somewhat in the middle of the datapoints)
>→ positive and negative values generally cancel out

original data:
$\bar{x}$ and variance $\sigma^2(x)$
# Mean
$$\bar{y}=\frac1n \sum_{i=1}^nax_i+\sum_{i=1}^nb=$$
$$=a\cdot \sum_{i=1}^nx_i+b=$$
>[!important] $$\bar{y}=a\cdot \bar{x} +b$$

# Variance 
$$\sigma^2=\frac{1}{n}\sum_{i=1}^{n}(y_i-\bar{y})^2=$$
$$=\frac{1}{n}\sum_{i=1}^{n}[(ax_i+b)-(a\bar{x}+b)]^2=\frac{1}{n}\sum_{i=1}^{n}[a(x_i-\bar{x})]^2$$
$$=\frac{1}{n}\sum_{i=1}^{n}a^2\cdot (x_i-\bar{x})^2=$$
>[!important] $$\sigma^2(y)=a^2\cdot \sigma^2 (x)$$

