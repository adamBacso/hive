---
title: "Variance"
alias: 
type: note
subject: math
tags:
 - math
 - statistics
created: 2023.02.16 09:48
created_by: Ádám
TARGET DECK: math
summary: 
status: draft
---
*szórás négyzet*
$$\sigma^2=\frac{(x_1-\bar{x})^2+(x_2-\bar{x})^2+\ldots+(x_n-\bar{x})^2}{n}$$
>[!note] Shortened form 
$$\sigma ^2=\frac{1}{n}\sum_{i=1}^{n}(x_i-\bar{x})^2=$$
$$=\frac{1}{n}\sum_{i=1}^{n}(x_i^2-2x_i\bar{x}+\bar{x}^2)=$$
$$=\frac{1}{n}\sum_{i=1}^{n}x_i^2-\frac{1}{n}\sum_{i=1}^{n}2x_i^2+\frac{1}{n}\sum_{i=1}^{n}\bar{x}^2=$$
$$=\frac{1}{n}\sum_{i=1}^{n}x_i^2-2\bar{x}\frac{1}{n}\sum_{i=1}^{n}x_i+\bar{x}^2=$$
$$=\overline{x^2}-2\bar{x}\bar{x}+\bar{x}^2=$$
> >[!important] $$\sigma^2=\overline{x^2}-\bar{x}^2$$

>var(x)