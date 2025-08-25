# Five Number Summary - Descriptive Statistics

## Introduction

The **five number summary** is a set of descriptive statistics that provides a concise overview of a dataset. It is widely used in statistics and machine learning for feature selection and outlier detection.

The five components are:
- **Minimum value**
- **First quartile ($Q_1$) — 25th percentile**
- **Median — 50th percentile**
- **Third quartile ($Q_3$) — 75th percentile**
- **Maximum value**

These values summarize the distribution and spread of the data.

---

## Example Dataset

Consider the dataset:

```
1, 2, 2, 3, 3, 4, 5, 5, 5, 6, 6, 6, 6, 7, 8, 8, 9, 27
```

Here, **27** is an outlier as it is much larger than the other values.

---

## Outlier Detection: Lower and Upper Fences

Outliers are identified using **lower** and **upper fences**:

- **Lower fence:** Values below this are outliers.
- **Upper fence:** Values above this are outliers.

### Formulas

- **Interquartile Range (IQR):**
    $$
    IQR = Q_3 - Q_1
    $$

- **Lower fence:**
    $$
    \text{Lower fence} = Q_1 - 1.5 \times IQR
    $$

- **Upper fence:**
    $$
    \text{Upper fence} = Q_3 + 1.5 \times IQR
    $$

Values outside these fences are considered outliers.

---

## Calculating Quartiles

Given $n$ data points, the position of the quartiles is:

- **First quartile ($Q_1$):**
    $$
    \text{Position of } Q_1 = \frac{25}{100} \times (n + 1)
    $$
- **Third quartile ($Q_3$):**
    $$
    \text{Position of } Q_3 = \frac{75}{100} \times (n + 1)
    $$

For $n = 18$ (after removing the outlier):

- $Q_1$ position: $0.25 \times 19 = 4.75$ (5th value, which is 3)
- $Q_3$ position: $0.75 \times 19 = 14.25$ (15th value, which is 7)

---

## Calculating IQR and Fences

- $Q_1 = 3$
- $Q_3 = 7$
- $IQR = 7 - 3 = 4$

- **Lower fence:**
    $$
    3 - 1.5 \times 4 = 3 - 6 = -3
    $$
- **Upper fence:**
    $$
    7 + 1.5 \times 4 = 7 + 6 = 13
    $$

Any value $< -3$ or $> 13$ is an outlier.

---

## Five Number Summary (After Removing Outlier)

Dataset:  
`1, 2, 2, 3, 3, 4, 5, 5, 5, 6, 6, 6, 6, 7, 8, 8, 9`

- **Minimum:** 1
- **First quartile ($Q_1$):** 3
- **Median:** 5
- **Third quartile ($Q_3$):** 7
- **Maximum:** 9

---

## Visualization: Box Plot

A **box plot** visualizes the five number summary and highlights outliers. It shows the spread, skewness, and potential outliers in the data.

---

## Key Takeaways

- The five number summary: **minimum, $Q_1$, median, $Q_3$, maximum**
- Outliers are detected using:
    $$
    \text{Lower fence} = Q_1 - 1.5 \times IQR
    $$
    $$
    \text{Upper fence} = Q_3 + 1.5 \times IQR
    $$
- Values outside these fences are outliers and can be removed for better data analysis.

---