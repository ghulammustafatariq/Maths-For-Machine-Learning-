# 📘 Probability – Multiplication Rule (Independent & Dependent Events)

## 🔹 Introduction
Previously, we studied the **Addition Rule** for mutually exclusive and non-mutually exclusive events.  
Now we focus on the **Multiplication Rule** for **Independent** and **Dependent** events.

---

## 🎲 Independent Events
- **Definition:** Two events are **independent** if the occurrence of one does **not affect** the probability of the other.
- **Examples:**
  - Tossing a coin twice → First toss does not affect the second.
  - Rolling a dice → Getting 1 first and 2 next are independent.

### Formula:
For independent events $A$ and $B$:
$$
P(A \; \text{and} \; B) = P(A) \times P(B)
$$

#### Example:
Toss a coin twice → Probability of getting **Head** then **Tail**:
$$
P(H \; \text{and} \; T) = \frac{1}{2} \times \frac{1}{2} = \frac{1}{4}
$$

---

## 🔹 Dependent Events
- **Definition:** Two events are **dependent** if the occurrence of one **affects** the probability of the other.
- **Example:** Drawing cards **without replacement**.
  - First draw: Probability of King = $\frac{4}{52}$
  - After removing King → 51 cards remain.
  - Second draw: Probability of Queen = $\frac{4}{51}$

### Formula:
For dependent events $A$ and $B$:
$$
P(A \; \text{and} \; B) = P(A) \times P(B \mid A)
$$

Where:
- $P(B \mid A)$ = Probability of $B$ given that $A$ has already occurred.

#### Example:
Drawing a **King** and then a **Queen** (without replacement):
$$
P(K \; \text{and} \; Q) = P(K) \times P(Q \mid K)
$$
$$
= \frac{4}{52} \times \frac{4}{51}
$$

---

## 🔹 Conditional Probability
- Conditional probability is used in **dependent events**:
  $$
  P(B \mid A) = \frac{P(A \; \text{and} \; B)}{P(A)}
  $$
- Forms the basis of **Bayes' Theorem**, applied in ML algorithms like **Naive Bayes**.

---

## 📌 Summary
- **Independent Events:**
  - Do not influence each other.
  - Rule: $P(A \; \text{and} \; B) = P(A) \times P(B)$
- **Dependent Events:**
  - Affect each other’s probabilities.
  - Rule: $P(A \; \text{and} \; B) = P(A) \times P(B \mid A)$
- **Conditional Probability** is key for dependent events.

---

## ✅ Key Takeaways
- Independent events → Coin tosses, dice rolls.  
- Dependent events → Drawing cards without replacement.  
- Multiplication Rule:
  - Independent: Multiply probabilities directly.  
  - Dependent: Use conditional probability.  
- Foundation for **Bayes’ theorem** and **Naive Bayes algorithm** in ML.  

---

 
