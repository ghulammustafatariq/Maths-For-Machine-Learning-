Measure Of Dispersion
=====================

Introduction to Measure of Dispersion
-------------------------------------

In this lecture, we continue our discussion on statistics by focusing on the measure of dispersion. Specifically, we will cover two important concepts: **variance** and **standard deviation**. Our primary focus will be on variance, including calculations for both population and sample data. Understanding variance is crucial because its formula slightly changes depending on whether we are dealing with population or sample data.

Understanding Measure of Dispersion
-----------------------------------

Let's consider a simple distribution of ages. Suppose we have the following data points: 2, 2, 3, 3. This represents our sample data or dataset. Alternatively, consider another set of ages: 1, 1, 5, 5. We will calculate the mean (denoted as $\\mu$) for these datasets to understand their central tendency.

For the first dataset, the mean is calculated by summing all values and dividing by the total number of elements:

$$ \mu = \frac{2 + 2 + 3 + 3}{4} = 2.5 $$

For the second dataset, the mean is:

$$ \mu = \frac{1 + 1 + 5 + 5}{4} = 3 $$

Comparing Two Distributions with the Same Mean
----------------------------------------------

Notice that these two different distributions have different data points but can have the same mean. For example, both datasets can have a mean of 3. However, the spread or dispersion of the data points around the mean differs. In the second dataset, values like 1 and 5 are farther from the mean compared to the first dataset where values are closer to the mean.

This difference in spread is what the measure of dispersion captures. **Variance** and **standard deviation** help us quantify how spread out the data points are from the mean.

Variance
========

Variance is a measure of how much the data points in a distribution deviate from the mean. It is denoted by $\sigma^2$ for population data. The formula for variance in the case of population data is:

$$ \sigma^2 = \frac{1}{N} \sum\_{i=1}^{N} (x_i - \mu)^2 $$

Where:

*   $N$ is the population size
    
*   $x_i$ represents each data point
    
*   $\mu$ is the population mean
    

This formula calculates the average of the squared differences between each data point and the mean.

Example Calculation of Population Variance
------------------------------------------

Consider the dataset: 2, 2, 4, 4. Let's calculate the variance step-by-step.

1.  $$ \mu = \frac{2 + 2 + 4 + 4}{4} = 3 $$
    
2.  **Calculate each squared deviation from the mean:**
    
    *   $(2 - 3)^2 = 1$
        
    *   $(2 - 3)^2 = 1$
        
    *   $(4 - 3)^2 = 1$
        
    *   $(4 - 3)^2 = 1$
        
3.  $$ 1 + 1 + 1 + 1 = 4 $$
    
4.  $$ \sigma^2 = \frac{4}{4} = 1 $$
    

Thus, the variance of this dataset is **1**.

Variance Calculation for Another Dataset
----------------------------------------

Now, consider the dataset: 1, 1, 5, 5.

1.  $$ \mu = \frac{1 + 1 + 5 + 5}{4} = 3 $$
    
2.  **Calculate each squared deviation from the mean:**
    
    *   $(1 - 3)^2 = 4$
        
    *   $(1 - 3)^2 = 4$
        
    *   $(5 - 3)^2 = 4$
        
    *   $(5 - 3)^2 = 4$
        
3.  $$ 4 + 4 + 4 + 4 = 16 $$
    
4.  $$ \sigma^2 = \frac{16}{4} = 4 $$
    

This variance of **4** indicates a greater dispersion compared to the previous dataset with variance 1.

Sample Variance
===============

When calculating variance for sample data rather than the entire population, the formula slightly changes. The sample variance is denoted by $S^2$ and is calculated as:

$$ S^2 = \frac{1}{n-1} \sum\_{i=1}^{n} (x_i - \bar{x})^2 $$

Where:

*   $n$ is the sample size
    
*   $x_i$ are the sample data points
    
*   $\bar{x}$ is the sample mean
    

Note the denominator is $(n - 1)$ instead of $n$. This adjustment corrects the bias in the estimation of the population variance from a sample. The reason for dividing by $(n - 1)$ rather than $n$ will be discussed in detail in the next topic.

Key Takeaways
=============

*   Variance and standard deviation are key measures of dispersion in statistics.
    
*   Variance for population data is calculated by averaging squared deviations from the mean using population size $N$.
    
*   Variance for sample data uses the sample mean and divides by $n-1$ instead of $n$ to correct bias.
    
*   Different distributions can have the same mean but different variances, indicating different spreads.