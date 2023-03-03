---
title: "t-test"
alias: 
type: note
subject: math
tags:
 - math
 - statistics
created: 2023.03.02 09:12
created_by: Ádám
TARGET DECK: math
summary: 
status: draft
---
>compares the mean of two datasets and determines if they are similar enough

>[!important] t-test
>$$\frac{\hat{p}_{1}-\hat{p}_{2}}{\sqrt{ \frac{p_{1}(1-p_{1})}{n_{1}} +\frac{p_{2}(1-p_{2})}{n_{2}}}}$$

![[sample proportion#with attribute]]

# null hypothesis
assumes that the mean of two populations is the same

# calculation
>[!important] from [[Z-score]]
$$\frac{\text{difference between the samples}}{\sqrt{ \text{some measure of spread} }}$$

## [[Variance]] of $(\hat{p}_{1}-\hat{p}_{2})$
$$Var(\hat{p}_{1}-\hat{p}_{2})=Var(\hat{p}_{1})+Var(\hat{p}_{2})$$
$$Var\left(\sum^{n}_{i=1}X_{i}\right)=\sum^{n}_{i=1}Var(X_{i})$$

# Sudent’s t-test

# critical t statistic
$$t=\frac{\bar{x}_{A}-\bar{x}_{B}}{\sqrt{ \frac{s^{2}_{A}}{n_{A}}+\frac{s^{2}_{B}}{n_{B}} }}$$