# 📘 Hypothesis Testing and Mechanism

## 🔹 Introduction
- **Hypothesis Testing** → A key part of **inferential statistics**.  
- Goal: Use **sample data** to make conclusions about **unknown population parameters** (mean, variance, standard deviation, etc.).  
- Since testing the entire population is impractical, we rely on **samples**.

---

## 🎯 What is Hypothesis Testing?
- **Definition:** A statistical process to decide whether there is enough evidence to reject a default assumption about the population.  
- Helps answer: *Does sample evidence support a claim about the population?*

---

## 🔹 Steps in Hypothesis Testing

### 1. **Formulate the Null Hypothesis ($H_0$)**
- $H_0$ represents the **default assumption** (status quo).
- Example: A person is **not guilty** in a court trial.

### 2. **Formulate the Alternate Hypothesis ($H_1$)**
- $H_1$ is the **opposite** of $H_0$.
- Example: A person **is guilty** in a court trial.

---

### ⚖️ Court Case Analogy
- **$H_0$ (Null):** Person is innocent.  
- **$H_1$ (Alternate):** Person is guilty.  
- Evidence (data) is presented to decide whether to reject $H_0$.

---

### 3. **Perform Statistical Analysis**
- Collect data (sample evidence).
- Use statistical tests to evaluate evidence:
  - **Z-test**
  - **T-test**
  - **Chi-square test**
  - **ANOVA**
  - **F-test**

---

### 4. **Decision Making**
- Based on test results, either:
  - **Fail to reject $H_0$** (insufficient evidence against null).  
  - **Reject $H_0$ in favor of $H_1$** (sufficient evidence against null).  

---

## 🔹 Example Problem: College Pass Percentage
- Claim: Average pass percentage = **85%**
- Sample: $n = 100$ students from a new college
  - Sample mean: $\bar{x} = 90\%$
  - Standard deviation: $s = 4\%$

### Formulating Hypotheses:
- **Null hypothesis ($H_0$):**
  $$
  \mu = 85
  $$
- **Alternate hypothesis ($H_1$):**
  - If asking *different*: 
    $$
    \mu \neq 85
    $$
  - If asking *greater*: 
    $$
    \mu > 85
    $$

Next steps involve calculating the **test statistic**, **p-value**, and comparing with the **significance level ($\alpha$)** to decide on $H_0$.  

---

## 📌 Key Takeaways
- **Hypothesis testing** → Core method in inferential statistics.  
- **$H_0$ (Null):** Default assumption.  
- **$H_1$ (Alternate):** Opposite claim.  
- Use statistical tests (z, t, chi-square, ANOVA, F) to evaluate.  
- Decision: Accept or reject $H_0$ based on evidence.  
- Real-world analogy: Court trials (innocent until proven guilty).  

---

