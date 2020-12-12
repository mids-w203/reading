# Cheat Sheet: One-Sample t-Test

This is a parametric test for a single random variable $X$.  It is used to test whether the expectation is equal to a hypothesized value, $\mu_0$.  For example, you can use a one-sample t-test to compare a sample of sleep times against the benchmark of 8 hours per night.


Assumptions:

1. Metric scale.  
    - In particular, the t-test is not valid for variables which only have an ordinal structure.
2. IID data.
3. No major deviations from normality, considering the sample size.
    - In particular, the t-test is invalid for highly skewed distributions when sample size is *less* than 30. It may also be invalid for very highly skewed distributions at higher sample sizes.
    
Null Hypothesis

The expectation of $X$ is equal to a reference mean $\mu_0$.
