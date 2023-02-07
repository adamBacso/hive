---
title: "spread"
alias: "measures of spread"
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
# Range
>the difference between its extreme values

# Percentiles
>divide the range into 100 equal parts

# First and third quartiles
>the points below lies 25% and 75% of the data respectively

>[!info] Inter-quartile range 
>distance between the first and third quartile

# Mean absolute deviation
$$\frac{\vert{x_1-\bar{x}}\vert+\vert{x_2-\bar{x}}\vert+...+\vert{x_n-\bar{x}}\vert}{n}$$
## Variance 
*szórás négyzet*
$$\sigma^2=\frac{(x_1-\bar{x})^2+(x_2-\bar{x})^2+\ldots+(x_n-\bar{x})^2}{n}$$
>[!note] Shortened form 
$$\sigma ^2=\frac{1}{n}\sum_{i=1}^{n}(x_i-\bar{x})^2=$$
$$=\frac{1}{n}\sum_{i=1}^{n}(x_i^2-2x_i\bar{x}+\bar{x}^2)=$$
$$=\frac{1}{n}\sum_{i=1}^{n}x_i^2-\frac{1}{n}\sum_{i=1}^{n}2x_i^2+\frac{1}{n}\sum_{i=1}^{n}\bar{x}^2=$$
$$=\frac{1}{n}\sum_{i=1}^{n}x_i^2-2\bar{x}\frac{1}{n}\sum_{i=1}^{n}x_i+\bar{x}^2=$$
$$=\overline{x^2}-2\bar{x}\bar{x}+\bar{x}^2=$$
> >[!important] $$\sigma^2=\overline{x^2}-\bar{x}^2$$

var(x)

# Standard deviation 
*szórás*
$$\sigma=\sqrt{\frac{(x_1-\bar{x})^2+(x_2-\bar{x})^2+\ldots+(x_n-\bar{x})^2}{n}}$$
