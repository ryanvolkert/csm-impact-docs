# Other FAQ
## What is DS's specific methodology for conducting impact analyses?
- We use statistical modeling, specifically [mixed modeling](https://en.wikipedia.org/wiki/Mixed_model) to estimate the marginal impact of Balto usage while simultaneously controlling for as many potential confounding factors as possible.

## What is typically reported in the summary table?
- **Estimated Balto effect**: The marginal effect of a single standard deviation change in Balto usage, expressed as a percentage deviation from the average of the KPI being analyzed.
- **P-value**: Determines whether the estimated Balto effect is 'statistically significant'. The general rule of thumb is the lower the p-value, the better. DS considers any p-value lower than 0.15 to be a statistically significant result.
- **95% CI lower/upper bound**: The lower and upper bounds of a 95% [confidence interval](https://en.wikipedia.org/wiki/Confidence_interval) around the estimated Balto impact. The simplest way to interpret these two numbers are that they represent an upper and lower threshold in which DS has a given level of statistical certainty (specifically, 95% certainty) that the true Balto effect falls within.
