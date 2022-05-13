---
title: Linear Regression T-Test
---
*Linear regression $t$ tests* are used to quantify the relationship between a
predictor variable and a response variable.

Whenever we perform a linear regression, we want to know if there is a
statistically significant relationship between the predictor variable
and the response variable.

We test for significance by performing a $t$-test for the regression
slope. We use the following null and alternative hypothesis for this
$t$-test:
- $H_0$: $\beta_1=0$ (the slope is equal to zero)
- $H_A$: $\beta_1\ne0$ (the slope is not equal to zero)

We then calculate the test statistic as follows:
$$t=\frac{b}{SE_b}$$
where:

-   $b$: coefficient estimate
-   $SE_b$: standard error of the coefficient estimate

If the $p$-value that corresponds to $t$ is less than some threshold (e.g.
$\alpha=0.05$) then we reject the null hypothesis and conclude that there is a statistically significant relationship between the predictor variable
and the response variable.