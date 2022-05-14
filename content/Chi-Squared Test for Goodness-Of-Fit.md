---
title: Chi-Squared Test for Goodness-Of-Fit
---
The $\chi^2$ test for goodness-of-fit is a test that compares the *counts* of an observed distribution of a single *categorical variable* to the expected distribution.

## Hypotheses
You **MUST** define the null and alternate hypothesis.
- $H_0$ (Null Hypothesis): The given ratios are correct (context).
- $H_A$ (Alternate Hypothesis): The given rations are not correct (context).

> ***ALWAYS PROVIDE CONTEXT.***
## Assumptions and Conditions
- **Counted Data Condition**: Check that the data are counts for the *categories* of a categorical variable.
	- No way that this isn't satisfied; simply state the condition.
- **Randomization Condition**: The data should come from a ***random sample*** from some population.
	- The problem will either state that the sample was randomly selected or part of a [[Simple Random Sample|SRS]].
	- If not, say, "There is no reason to believe that the sample is *not* representative of the population of (context)".
- **Sample Size Assumption**: We should expect to see ***at least five*** individuals in each cell. Refer to the table you will provide.
	- Much smaller sample size compared to $z$-tests and $p$-tests.

After proving these conditions, you **MUST** conclude with the following:
> Since the conditions are met, I will now conduct a $\chi^2$ goodness-of-fit test.

## Calculation
Find $\chi^2$ on your calculator, and plug in the data. Show the following:
- $\chi^2$ statistic
- degrees of freedom (usually $=n-1$)
- $p$-value
- $\alpha$-value (if not provided, assume $\alpha=0.05$)

### Formula
$$\chi^2=\sum{\frac{(O_i-E_i)^2}{E_i}}$$
> - $O_i$: observed value
> - $E_i$: expected value

## Conclusion
The conclusion depends on your calculated $p$-value and the $\alpha$-level.
- If $p<\alpha$, **reject** the $H_0$. Therefore, there is *sufficient* evidence that $H_A$ (context).
- If $p>\alpha$, **fail to reject** the $H_0$. Therefore, there is *insufficient* evidence that $H_A$ (context).
> Do **NOT** provide context for the *null hypothesis*.
> However, you **MUST** provide context for the *alternate hypothesis*.