# Correlation
*Correlation* expresses the extent to which ***two*** variables are related (change proportionally).

> ##### Correlation $\neq$ Linear Relationship
> Note that correlations don't always have to be linear relationships! There are numerous statistical models that are non-linear, but aren't covered in this course.

## Important Considerations
- Correlation makes no distinction between independent and dependent variables; it doesn't matter what you call either variable when calculating the correlation.
- When doing *anything* that is related to correlations, the two variables ***must*** be quantitative.
- The correlation coefficient, $r$, uses standardized statistics of the two variables, so the units don't matter when calculating correlations. Therefore, changing the units in which one or both variables are defined does not affect the correlation.

## Association & Correlation ==(check validity)==
An *association* is the relationship between two variables; however, that relationship could mean that the variables are completely dependent on each other, or completely independent of each other. A *correlation* objectifies this relationship, and gives context to the association between two variables.

> ## **IMPORTANT**: Correlation $\neq$ Causation

## Correlation Coefficient
The *correlation coefficient*, $r$, is a measure of the *strength* of the linear relationship between two variables as well as an indication of the *direction* of the linear relationship.

If you have summary statistics of both your variables, you can calculate the correlation coefficient:

$$r=\frac{1}{n-1}\sum{\left(\frac{x_i-\bar{x}}{s_x}\right)\left(\frac{y_i-\bar{y}}{s_y}\right)}$$

Since the z-score $z_x=\frac{x_1-\bar{x}}{s_x}$, the correlation coefficient can also be calculated like this:

$$r=\frac{1}{n-1}\sum{z_xz_y}$$

### Properties of the Correlation Coefficient
- $-1 \leq r \leq 1$. If $r=1$ or $r=-1$, the data lies on a line
- Guidance
	- $0.8 \leq |r| \leq 1$: strong
	- $0.5 \leq |r| \leq 0.8$: moderate
	- $|r| \leq 0.5$: weak
- Association
	- If $r>0$, there is a positive association.
	- If $r<1$, there is a negative association.
	- If $r=0$, it indicates that there is no linear association; doesn't mean that there isn't a relationship, though.
- **Note**: $r$ is NOT resistant to extreme values, since it is reliant on the mean and standard deviation. Refer to [[Outliers and Influential Observations|outliers/influential observations]] for more information.