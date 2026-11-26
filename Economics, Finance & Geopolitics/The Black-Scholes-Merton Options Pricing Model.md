---
title: "The Black-Scholes-Merton Options Pricing Model"
tags: [economics, finance, derivatives, stochastic-calculus]
related: [[[Stochastic Calculus - Itô's Lemma and Geometric Brownian Motion]], [[Modern Portfolio Theory - Markowitz Efficient Frontier and CAPM]]]
created: 2026-11-26
updated: 2026-11-26
---

# The Black-Scholes-Merton Options Pricing Model

## Overview
The Black-Scholes-Merton formula (1973) revolutionized quantitative finance by providing the first mathematically closed-form pricing model for European financial options.

## Core Mechanics & Foundations
The Black-Scholes PDE: Under the assumption that the underlying stock price $S_t$ follows Geometric Brownian Motion ($dS = \mu S dt + \sigma S dW$), Fischer Black and Myron Scholes constructed a dynamically rebalanced riskless hedge portfolio combining stock shares and options. Applying Itô's Lemma eliminates stochastic noise, yielding the partial differential equation: $\frac{\partial V}{\partial t} + \frac{1}{2}\sigma^2 S^2 \frac{\partial^2 V}{\partial S^2} + r S \frac{\partial V}{\partial S} - r V = 0$.

## Modern Applications & Advanced Significance
Closed-Form Call Formula: For a European call option with strike price $K$ and expiration $T$: $C(S, t) = S N(d_1) - K e^{-r(T-t)} N(d_2)$, where $d_1 = \frac{\ln(S/K) + (r + \sigma^2/2)(T-t)}{\sigma \sqrt{T-t}}$ and $d_2 = d_1 - \sigma \sqrt{T-t}$.

## Real-World Impact & Systems
Global derivatives markets, risk management hedging, calculation of implied market volatility (VIX index).

## Key Terminology
- **European Option**: Financial derivative contract that can be exercised only on its specific expiration date.
- **Implied Volatility**: Market's forecast of a likely movement in an underlying security's price embedded in options pricing.
- **Risk-Neutral Pricing**: Pricing technique where options are valued under the assumption that investors are indifferent to risk.


## References & Further Exploration
[[Stochastic Calculus - Itô's Lemma and Geometric Brownian Motion]], [[Modern Portfolio Theory - Markowitz Efficient Frontier and CAPM]]
