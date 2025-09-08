# 📘 Probability – Addition Rule (Mutual & Non-Mutual Exclusive Events)

## 🔹 Introduction
Probability helps us determine the **likelihood of an event**.  
It is widely used in **statistics and machine learning**, such as classification algorithms, where outputs depend on probability thresholds.

---

## 🎲 What is Probability?
- **Definition:** Probability = Likelihood of an event occurring.
- Formula:
  $$
  P(E) = \frac{\text{Favorable Outcomes}}{\text{Total Outcomes}}
  $$

### Examples:
- Tossing a coin:
  $$
  P(\text{Head}) = \frac{1}{2}, \quad P(\text{Tail}) = \frac{1}{2}
  $$
- Rolling a die:
  $$
  P(x) = \frac{1}{6} \quad \text{for any specific number (1–6)}
  $$

---

## 🔹 Mutually Exclusive Events
- **Definition:** Events that **cannot occur at the same time**.  
  Example: Tossing a coin → Head and Tail cannot occur simultaneously.

- **Venn Diagram:** No overlap between events.

- **Addition Rule:**
  $$
  P(A \; \text{or} \; B) = P(A) + P(B)
  $$

### Examples:
1. Coin Toss:  
   $$
   P(H \; \text{or} \; T) = \frac{1}{2} + \frac{1}{2} = 1
   $$

2. Dice Roll (1 or 5):  
   $$
   P(1 \; \text{or} \; 5) = \frac{1}{6} + \frac{1}{6} = \frac{2}{6} = \frac{1}{3}
   $$

---

## 🔹 Non-Mutually Exclusive Events
- **Definition:** Events that **can occur at the same time**.  
  Example: Drawing a card → King **or** Heart (King of Hearts belongs to both).

- **Venn Diagram:** Overlap exists between events.

- **Addition Rule:**
  $$
  P(A \; \text{or} \; B) = P(A) + P(B) - P(A \; \text{and} \; B)
  $$

### Example (Deck of Cards):
- $P(K) = \frac{4}{52}$  
- $P(H) = \frac{13}{52}$  
- $P(K \; \text{and} \; H) = \frac{1}{52}$  

Therefore:
$$
P(K \; \text{or} \; H) = \frac{4}{52} + \frac{13}{52} - \frac{1}{52} = \frac{16}{52} = \frac{4}{13}
$$

---

## 📌 Summary
- **Probability** = likelihood of an event.
- **Mutually Exclusive Events:**
  - Cannot occur together.
  - Rule: $P(A \; \text{or} \; B) = P(A) + P(B)$
- **Non-Mutually Exclusive Events:**
  - Can occur together.
  - Rule: $P(A \; \text{or} \; B) = P(A) + P(B) - P(A \; \text{and} \; B)$

---

## ✅ Key Takeaways
- Mutually Exclusive → No overlap → Just add probabilities.  
- Non-Mutually Exclusive → Overlap exists → Subtract intersection.  
- Addition rule changes depending on the event type.  
- Next Topic → **Multiplication Rule for Independent & Dependent Events**.
