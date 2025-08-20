# Standard Deviation

In this lecture, we continue reviewing the concepts learned so far. All formulas are written clearly to avoid confusion.

## Population Parameters

- **Population size:** $N$
- **Population mean:** $\mu$

$$
\mu = \frac{1}{N} \sum_{i=1}^{N} x_i
$$

Sum all data points $x_i$ in the population and divide by $N$.

- **Population variance:** $\sigma^2$

$$
\sigma^2 = \frac{1}{N} \sum_{i=1}^{N} (x_i - \mu)^2
$$

Average squared deviation from the population mean.

- **Population standard deviation:** $\sigma$

$$
\sigma = \sqrt{\sigma^2}
$$

Indicates how far data points are from the mean on average.

## Interpretation of Standard Deviation

Standard deviation tells us how far a data point is from the mean:

- If the mean is 3 and the standard deviation is 1:
    - Data point 4 is one standard deviation to the right of the mean.
    - Data point 2 is one standard deviation to the left of the mean.
    - Data point 4.5 is 1.5 standard deviations away from the mean.

Standard deviation measures the distance of data points from the mean in units of standard deviations.

## Sample Statistics

- **Sample size:** $n$
- **Sample mean:** $\bar{x}$

$$
\bar{x} = \frac{1}{n} \sum_{i=1}^{n} x_i
$$

Average of the sample data points.

- **Sample variance:** $s^2$ (using Bessel's correction)

$$
s^2 = \frac{1}{n-1} \sum_{i=1}^{n} (x_i - \bar{x})^2
$$

Denominator is $n-1$ to correct bias in the estimation.

- **Sample standard deviation:** $s$

$$
s = \sqrt{s^2}
$$

Measures the average distance of sample data points from the sample mean.

## Summary

- Population mean and variance use $N$ in the denominator.
- Sample mean and variance use $n$ and $n-1$ respectively.
- Standard deviation is the square root of variance and indicates spread or dispersion.
- These formulas are essential for understanding measures of central tendency and dispersion.

## Key Takeaways

- **Population mean ($\mu$)**: Sum of all data points divided by population size ($N$).
- **Population variance ($\sigma^2$)**: Average squared deviation from the population mean.
- **Population standard deviation ($\sigma$)**: Square root of population variance.
- **Sample variance and standard deviation**: Use $n-1$ in the denominator for an unbiased estimate, where $n$ is the sample size.

We will continue our discussion in the next video.