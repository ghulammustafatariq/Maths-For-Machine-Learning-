# Why Sample Variance Is Divided By *n*‒1

## Introduction to Sample Variance

The formula for sample variance, denoted as $s^2$, is:

$$
s^2 = \frac{\sum_{i=1}^{n} (x_i - \bar{x})^2}{n-1}
$$

- $n$ is the sample size  
- $x_i$ are the sample data points  
- $\bar{x}$ is the sample mean

## Population Variance vs. Sample Variance

Population variance, denoted as $\sigma^2$, is calculated as:

$$
\sigma^2 = \frac{\sum_{i=1}^{N} (x_i - \mu)^2}{N}
$$

- $N$ is the population size  
- $x_i$ are population data points  
- $\mu$ is the population mean

Notice the denominator is $N$ for population variance, but $n-1$ for sample variance.

## Why Divide by *n*‒1 in Sample Variance?

Dividing by $n-1$ instead of $n$ is called **Bessel's correction**.  
When estimating variance from a sample, dividing by $n$ tends to **underestimate** the true population variance.

### Sampling and Inference

- With full population data, calculating mean and variance is straightforward.
- With only a sample, we estimate population parameters.
- The sample mean $\bar{x}$ approximates $\mu$, and sample variance $s^2$ approximates $\sigma^2$.

### Illustration

If you select a random sample, $\bar{x}$ will be close to $\mu$, and $s^2$ close to $\sigma^2$.  
If the sample is biased, estimates can differ significantly.

### Consequences of Using *n* in the Denominator

Using $n$ in the denominator, especially with small or biased samples, **underestimates** the population variance.  
This is because $\bar{x}$ is itself estimated from the data, reducing the degrees of freedom.

### Bessel's Correction

Dividing by $n-1$ increases the sample variance, correcting the bias.  
This makes $s^2$ an **unbiased estimator** of $\sigma^2$.

## Degree of Freedom

- **Degrees of freedom (DOF)**: Number of independent values that can vary.
- For sample variance, DOF is $n-1$ because one parameter (the mean) is estimated from the data.

## Summary

- Population variance divides by $N$ (mean $\mu$ is known).
- Sample variance divides by $n-1$ (mean $\bar{x}$ is estimated).
- Bessel's correction ensures an unbiased estimate.
- Degrees of freedom for sample variance is $n-1$.

## Key Takeaways

- Sample variance divides by $n-1$, not $n$.
- Bessel's correction corrects bias in estimating population variance.
- Using $n$ underestimates variance, especially with non-random samples.
- Degrees of freedom for sample variance is $n-1$.
