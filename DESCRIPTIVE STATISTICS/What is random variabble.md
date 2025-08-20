# What are Random Variables

## Introduction to Random Variables

In this discussion, we continue exploring statistics by focusing on random variables. Random variables are quite important, especially if you are learning machine learning, deep learning, or working with data.

Random variables are denoted by capital letters such as **X**. Before understanding exactly what a random variable is, let's consider an equation example.

Suppose we have the equation **y = 5x + 2**. In this scenario, if we want to find **y**, we can use different values for **x**. For example, if **x = 1**, then **y = 7**. Similarly, if **x = 2** or **x = 3**, we get different **y** values. This means **x** can be considered a random variable that can take different values.

A random variable is a function whose values are derived from different processes or experiments.

---

### Example: Tossing a Coin

Consider **X** as a random variable representing the experiment of tossing a coin. The possible outcomes are heads or tails. This is a random process where each toss results in either heads or tails. We can assign values based on the outcome: if it is heads, assign 0; if tails, assign 1. This function derives values from the experiment of tossing a coin.

---

### Example: Rolling a Fair Dice

Another experiment is rolling a fair dice. The possible outcomes are 1, 2, 3, 4, 5, or 6. These are the different values **X** can take in this random process. Both tossing a coin and rolling a dice are examples of categorical variables where the outcomes are discrete values.

---

## Types of Random Variables

There are two main types of random variables:

- **Discrete Random Variables**
- **Continuous Random Variables**

---

### Discrete Random Variables

Examples of discrete random variables include tossing a coin and rolling a dice. These experiments yield countable, distinct values.

---

### Continuous Random Variables

Consider an experiment measuring how many inches it will rain tomorrow. This is a continuous random variable because the rainfall amount can be any value, such as 1.1 inches, 5.5 inches, 10.75 inches, and so on. There is no specific discrete value; it can take any value within a range, including fractions and decimals. Negative values are not applicable in this context since rainfall cannot be negative.

Another example of a continuous random variable is the height of people attending an event tomorrow. Heights can vary widely, such as 150 cm, 160 cm, or 160.1 cm. Continuous random variables can take any value, including fractions and whole numbers.

In contrast, discrete random variables yield whole numbers derived from random processes. For example, the number obtained from rolling a dice is always a whole number between 1 and 6.

---

## Summary

A random variable is a function that defines its values through some process or experiment. For example, tossing a coin yields heads or tails, which can be assigned values 0 or 1. Rolling a fair dice yields values from 1 to 6, representing a discrete random variable. Continuous random variables include measurements like rainfall or height, which can take any value within a range.

We will continue this session by discussing probability density functions or probability distribution functions of discrete and continuous random variables in the next session.

---

## Key Takeaways

- Random variables are functions that assign values based on outcomes of random processes or experiments.
- There are two main types of random variables: discrete and continuous.
- Discrete random variables take on countable values, such as outcomes from tossing a coin or rolling a dice.
- Continuous random variables can take any value within a range, such as rainfall amount or height measurements.
