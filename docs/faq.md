# FAQ
## What is DS's specific methodology for conducting analyses?
- We use statistical modeling, specifically [mixed modeling](https://en.wikipedia.org/wiki/Mixed_model) to estimate the marginal impact of Balto usage while simultaneously controlling for as many potential confounding factors as possible.
## Why use a statistical model instead of comparing group level averages?
- Statistical ([regression](https://en.wikipedia.org/wiki/Regression_analysis)) models can account for other sources of variation in the KPI of interest besides Balto use.
- Models can account for time explicitly.
- Balto use may be correlated with group membership or other factors. Controlling for some of these factors leads to a higher level of confidence that the Balto effect is really due to Balto and not some other source of variation.
- Regression modesl avoid unnecessary aggregations. As a general rule, statistical analyses should rely on as much relevant information as possible. Computing group-level or time-level statistics removes information about variation in performance across agents or time periods.
- Regression models can measure the magnitude of the Balto effect, formally test whether it is statistically different from zero, and compute condfidence intervals to address uncertainty.

## How much data do I need?
- As a general rule of thumb, more data is always better. When conducting an ROI or any experiment, sample size can be thought of as a 'net' to catch statistically significant effects. The larger the sample size, the smaller the holes in the net are. On the converse, when sample size is small the holes in the net are large. The implication of this is that a larger sample size is better because it enables us to catch a smaller effect. If sample size is not large enough, the holes in the metaphorical net may be too large to observe the occurrence of a small but significant effect.

## What is typically reported in the summary table?
- **Estimated Balto effect**: This is what is commonly referred to as 'lift' at Balto, and represents a percentage deviation from the average of the KPI being tested.
- **P-value**: Determines whether the estimated Balto effect is 'statistically significant'. The general rule of thumb is the lower the p-value, the better. DS considers any p-value lower than 0.15 to be a statistically significant result.
- **95% CI lower/upper bound**: The lower and upper bounds of a 95% [confidence interval](https://en.wikipedia.org/wiki/Confidence_interval) around the estimated Balto effect. The simplest way to interpret these two numbers are that they represent an upper and lower threshold in which DS has a given level of statistical certainty (specifically, 95% certainty) the true Balto effect falls within.
