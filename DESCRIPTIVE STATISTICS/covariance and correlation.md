# Covariance and Correlation: Summary Notes

## Covariance

- **Definition:** Measures how two random variables change together.
- **Formula:**
    $$
    \mathrm{Cov}(x, y) = \frac{\sum_{i=1}^{n} (x_i - \bar{x})(y_i - \bar{y})}{n-1}
    $$
    - $x_i$, $y_i$: Data points
    - $\bar{x}$, $\bar{y}$: Sample means
    - $n$: Sample size

- **Covariance of a variable with itself (Variance):**
    $$
    \mathrm{Cov}(x, x) = \mathrm{Var}(x) = \frac{\sum_{i=1}^{n} (x_i - \bar{x})^2}{n-1}
    $$

- **Interpretation:**
    - Positive covariance: Variables increase/decrease together.
    - Negative covariance: One increases as the other decreases.
    - Unbounded values ($-\infty$ to $+\infty$).

## Pearson Correlation Coefficient

- **Purpose:** Normalizes covariance to compare relationships.
- **Formula:**
    $$
    \rho = \frac{\mathrm{Cov}(x, y)}{\sigma_x \sigma_y}
    $$
    - $\sigma_x$, $\sigma_y$: Standard deviations of $x$ and $y$

- **Range:** $-1$ to $+1$
    - $+1$: Strong positive linear correlation
    - $-1$: Strong negative linear correlation
    - $0$: No linear correlation

## Spearman Rank Correlation

- **Purpose:** Measures monotonic relationships using ranks.
- **Formula:**
    $$
    \rho_s = \frac{\mathrm{Cov}(\mathrm{rank}(x), \mathrm{rank}(y))}{\sigma_{\mathrm{rank}(x)} \sigma_{\mathrm{rank}(y)}}
    $$

- **Advantages:**
    - Captures nonlinear monotonic relationships
    - Robust to outliers and non-normal distributions

## Application in Data Science

- **Feature Selection:** Use correlation to select relevant features for modeling.
    - High correlation: Useful features
    - Near-zero correlation: Can be discarded

## Key Takeaways

- Covariance quantifies joint variability but is unbounded.
- Pearson correlation normalizes covariance, making interpretation easier.
- Spearman rank correlation is suitable for nonlinear monotonic relationships.
- Correlation analysis is essential for understanding variable relationships and feature selection.
