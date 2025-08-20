<<<<<<< HEAD
# Measure Of Central Tendency

## Introduction to Measure of Central Tendency

In this lecture, we continue our discussion on statistics by covering the **measure of central tendency**.  
This topic includes three important subtopics: **mean, median, and mode**.

---

## Mean: Population and Sample

Previously, we discussed **population and sample**.  
Consider a population of size **N** and a sample size of **n**.  
The formula for mean (average) differs slightly between population and sample data.

- **Population Mean (\(\mu\))**

$$
\mu = \frac{\sum_{i=1}^{N} x_i}{N}
$$

Here, \(x_i\) represents the data points in the population, and \(N\) is the population size.

- **Sample Mean (\(\bar{x}\))**

$$
\bar{x} = \frac{\sum_{i=1}^{n} x_i}{n}
$$

where \(n\) is the sample size.

---

## Example: Calculation of Mean

Consider a variable called **age** with values: \(1, 3, 4, 5\).

To find the mean:

$$
\mu = \frac{1 + 3 + 4 + 5}{4} = \frac{13}{4} = 3.25
$$

This value represents the **mean age** in this dataset.

---

## Why is it Called Central Tendency?

The **mean** represents the central part of the distribution of data points.  
It provides a measure of the **center** of the data.

---

## Impact of Outliers on Mean

Now, consider adding an outlier value of \(100\) to the previous data: \(1, 3, 4, 5, 100\).

The mean becomes:

$$
\bar{x} = \frac{1 + 3 + 4 + 5 + 100}{5} = \frac{113}{5} = 22.6
$$

This large value significantly increases the mean, demonstrating that the **mean is sensitive to outliers**.

---

## Median: Definition and Calculation

To overcome the impact of outliers, we use the **median**.  
The median is the **middle value** of a **sorted dataset**.

For the dataset \(1, 3, 4, 5, 100\):  
Since there are 5 elements (**odd number**), the median is the **third element**:

$$
\text{Median} = 4
$$

This value is less affected by the outlier compared to the mean.

---

### Median with Even Number of Elements

If we add another outlier (\(200\)), the dataset becomes \(1, 3, 4, 5, 100, 200\).  
Since there are 6 elements (**even number**), the median is the **average of the third and fourth elements**:

$$
\text{Median} = \frac{4 + 5}{2} = 4.5
$$

Thus, the median remains close to the central tendency despite outliers.

---

## Mode: Definition and Application

The **mode** is the most frequently occurring value in the dataset.

Consider the dataset: \(4, 3, 2, 1, 1, 4, 4, 5, 2, 100\).

Frequencies:
- \(1 -> 2\) times  
- \(2 -> 2\) times  
- \(3 -> 1\) time  
- \(4 -> 3\) times  
- \(5 -> 1\) time  
- \(100 -> 1\) time  

Therefore,

$$
\operatorname{mode} = 4
$$

Note: The mode is useful for **categorical data** and is **resistant to outliers**.

---

## Summary

- **Mean** = Arithmetic average, **sensitive to outliers**  
- **Median** = Middle value in sorted data, **robust against outliers**  
- **Mode** = Most frequent value, useful for categorical data, **resistant to outliers**

---

## Conclusion

Understanding **mean, median, and mode** is fundamental in statistics.  
These concepts will be revisited in future topics, including the **measure of dispersion**.

---



