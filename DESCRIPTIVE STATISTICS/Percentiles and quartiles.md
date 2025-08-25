# Percentiles and Quartiles - Descriptive Statistics

## Introduction

Percentiles and quartiles are key concepts in statistics, frequently used in data analysis and examinations. They help us understand the relative standing and distribution of values within a dataset.

---

## Percentage vs. Percentile

- **Percentage**: The proportion of items in a group, calculated as:
    $$
    \text{Percentage} = \frac{\text{Number of items of interest}}{\text{Total number of items}} \times 100
    $$
    *Example*: In the list `1, 2, 3, 4, 5, 6`, the percentage of odd numbers is:
    $$
    \frac{3}{6} \times 100 = 50\%
    $$

- **Percentile**: A value below which a given percentage of observations fall.

---

## Understanding Percentiles

- **Definition**: The P percentile is the value below which $P\%$ of the data lies.

- **Percentile Rank Formula**:
    $$
    \text{Percentile of } x = \frac{\text{Number of values below } x}{n} \times 100
    $$
    where $n$ is the total number of values.

    *Example*: For the value 9 in the list `2, 2, 3, 4, 5, 5, 6, 7, 8, 8, 9, 9, 10`:
    - Number of values below 9: $11$
    - Total values: $14$
    $$
    \frac{11}{14} \times 100 = 78.57\%
    $$
    So, 78.57% of the distribution lies below 9.

---

## Calculating Percentile Values

- **Percentile Position Formula**:
    $$
    \text{Position} = \frac{P}{100} \times (n + 1)
    $$
    where $P$ is the desired percentile and $n$ is the number of values.

    *Example*: For the 25th percentile in a list of 14 values:
    $$
    \frac{25}{100} \times (14 + 1) = 3.75
    $$
    - If the position is not an integer, interpolate between the adjacent values:
        $$
        \text{Percentile Value} = \text{Lower Value} + (\text{Fraction}) \times (\text{Upper Value} - \text{Lower Value})
        $$
        For position 3.75 (between 3rd value = 3 and 4th value = 4):
        $$
        3 + 0.75 \times (4 - 3) = 3.75
        $$

---

## Quartiles

- **Quartiles** divide the data into four equal parts:
    - **First Quartile (Q1)**: 25th percentile
    - **Second Quartile (Q2)**: 50th percentile (Median)
    - **Third Quartile (Q3)**: 75th percentile

---

## Key Takeaways

- **Percentile**: Value below which a certain percentage of observations lie.
- **Percentile Calculation**:
    $$
    \text{Percentile of } x = \frac{\text{Number of values below } x}{n} \times 100
    $$
- **Quartiles**: Divide data into four equal parts (Q1, Q2, Q3).
- **Interpolation**: Used when percentile position is fractional.

---

*Review these concepts thoroughly—they are foundational for advanced statistical analysis.*