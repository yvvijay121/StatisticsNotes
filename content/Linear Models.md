# Linear Models
*Linear models*, also called a line of best fit are used to predict response values from explanatory values in a bivariate distribution. Use these if there appears to be a linear relationship between the two variables (obviously).
> *Note*: For linear models, unlike [[Correlation#Correlation Coefficient|correlation coefficients]], it matters which variable you define to be the [[Unit 2 - Two-Variable Data Analysis|explanatory variable or the response variable]].
## Least-Squares Regression Line
The *least-squares regression line* (LSLR) is the line that minimizes the sum of squared [[Residuals|residuals]]. If $\hat{y}=a+bx$ is the LSLR, then $\hat{y}$ (the predicted response variable) minimizes $\sum{(y-\hat{y})^2}$ (the summation of the squares of the [[Residuals|residuals]]).
### Formula
If we have $n$ ordered pairs of bivariate, quantitative data in pairs $(x,y)$, calculate the one-variable statistics for each to get the mean and [[Standard Deviation|standard deviation]]. You also need to calculate the [[Correlation#Correlation Coefficient|correlation coefficient]] ($r$).

If $\hat{y}=a+bx$ is the LSRL, then:
- $b=r\frac{s_y}{s_x}$
	- $b$ is the slope of the regression line.
	- ALWAYS the standard deviation of the explanatory variable over the standard deviation of the response variable.
- $a=\bar{y}-b\bar{x}$
	- Note that the value $(\bar{x},\bar{y})$ will ALWAYS be on the LSRL due to this formula.