---
title: "Linear Regression and Ordinary Least Squares (OLS) - Gauss-Markov Theorem"
tags: [mathematics, probability-and-statistics, machine-learning]
related: [[[Central Limit Theorem and Law of Large Numbers]], [[Singular Value Decomposition (SVD) and Dimensionality Reduction]]]
created: 2026-11-26
updated: 2026-11-26
---

# Linear Regression and Ordinary Least Squares (OLS) - Gauss-Markov Theorem

## Overview
Ordinary Least Squares (OLS) linear regression estimates linear relationships between dependent scalar outcomes and explanatory vector covariates by minimizing squared residual errors.

## Core Mechanics & Foundations
Matrix Formulation & Normal Equations: For model $Y = X \beta + \epsilon$, OLS minimizes residual sum of squares $\|Y - X \beta\|_2^2$. Taking gradients yields the closed-form normal equations: $X^T X \hat{\beta} = X^T Y \implies \hat{\beta} = (X^T X)^{-1} X^T Y$, geometrically projecting $Y$ onto the column space of design matrix $X$.

## Modern Applications & Advanced Significance
The Gauss-Markov Theorem: Under classical assumptions (linearity, full rank, exogeneity $\mathbb{E}[\epsilon \mid X] = 0$, homoscedasticity $\text{Var}(\epsilon \mid X) = \sigma^2 I$), the OLS estimator is BLUE: Best Linear Unbiased Estimator, achieving the absolute minimum variance among all possible unbiased linear estimators.

## Real-World Impact & Systems
Econometric causal inference, financial capital asset pricing models (CAPM), baseline statistical benchmarking in machine learning.

## Key Terminology
- **Ordinary Least Squares**: Statistical method estimating parameter coefficients by minimizing the sum of squared differences between observed and predicted values.
- **Gauss-Markov Theorem**: Theorem proving OLS is the Best Linear Unbiased Estimator (BLUE) under standard regression assumptions.
- **Homoscedasticity**: Property where the error term displays constant finite variance across all values of the explanatory variables.


## References & Further Exploration
[[Central Limit Theorem and Law of Large Numbers]], [[Singular Value Decomposition (SVD) and Dimensionality Reduction]]
