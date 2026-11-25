# Correlation vs Causation

> **The Big Idea:** Just because two things happen at the same time (**Correlation**) does not mean one caused the other (**Causation**). Confusing the two is one of the most common statistical errors in media, health, and politics.

---

## 📉 The Golden Rule of Statistics

```
┌──────────────────────────────────────┐       ┌──────────────────────────────────────┐
│             CORRELATION              │       │              CAUSATION               │
├──────────────────────────────────────┤       ├──────────────────────────────────────┤
│ Variable A and Variable B move       │  ≠    │ Variable A directly produces or      │
│ together (both rise or both fall).   │       │ triggers Variable B.                 │
└──────────────────────────────────────┘       └──────────────────────────────────────┘
```

---

## 🍦 The Classic Example: Ice Cream and Drowning

* **The Data:** In cities across the world, ice cream sales and accidental drownings correlate almost perfectly: when ice cream sales rise, drownings spike; when ice cream sales plummet, drownings drop.
* **The False Conclusion:** *"Eating ice cream causes cramps that make people drown!"* or *"Drownings make people grieve by buying ice cream!"*
* **The Real Truth (The Confounding Variable):** Both are caused by a third factor: **Hot Summer Weather**.
  * Hot weather causes people to buy ice cream.
  * Hot weather causes people to swim in pools and rivers.

```
                    [ HOT SUMMER WEATHER ]  ◄── (Confounding Variable)
                            /      \
                           /        \
                          ▼          ▼
             [ High Ice Cream ]   [ High Drownings ]
```

---

## ⚠️ 4 Reasons Two Variables Correlate Without Causation

1. **A Third Confounding Variable:** As in the ice cream example, a hidden third factor drives both.
2. **Reverse Causality:** Variable B actually caused Variable A.
   * *Example:* Depressed people exercise less. Does lack of exercise cause depression, or does depression make people lethargic? (Often it's a two-way loop).
3. **Pure Coincidence (Spurious Correlation):** In massive datasets, random things will line up by pure chance (e.g., US spending on science correlates with suicides by hanging).
4. **Bidirectional Feedback:** Both cause each other in a reinforcing loop (e.g., poverty and poor health).

---

## 🛠️ How to Test for Real Causation

* **Randomized Controlled Trials (RCTs):** The gold standard of science. Randomly split subjects into two groups: give one group the treatment and the other a placebo, holding all other variables constant.
* **Ask the mechanism question:** *"Through what physical or biological mechanism does A turn into B?"* If no plausible chain of events exists, suspect correlation.

---

**Related Notes:**
- [[Top 7 Logical Fallacies]]
- [[Survivorship Bias]]
- [[Deductive vs Inductive Arguments]]

**Back to Index:** [[_Knowledge Base Index]]

