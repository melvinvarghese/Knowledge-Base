---
title: "Bond Valuation - Yield to Maturity, Macaulay Duration, Convexity, and Credit Spreads"
tags:
  - finance
  - bond-markets
  - fixed-income
  - interest-rates
related:
  - "[[The Inverted Yield Curve - Bond Yields, Term Premia, and Recession Forecasting]]"
  - "[[Central Banking and Monetary Policy - Interest Rates, Reserve Ratios, and QE]]"
created: 2026-11-26
updated: 2026-11-26
---

# Bond Valuation - Yield to Maturity, Macaulay Duration, Convexity, and Credit Spreads

## Overview
Bond valuation determines the theoretical fair market price of a fixed-income debt instrument by discounting its expected future cash flows (coupons and par redemption) to the present.

## Core Mechanics & Foundations
Mathematical Principles & Metrics: (1) **Pricing Formula**: For a bond with coupon $C$, face value $M$, maturity $T$, and discount rate $y$: $P = \sum_{t=1}^T \frac{C}{(1+y)^t} + \frac{M}{(1+y)^T}$. Yield to Maturity (YTM) is the internal rate of return that equates the bond's market price with its discounted cash flows. (2) **Macaulay Duration**: The weighted average time until expected cash flows are received: $D_{mac} = \frac{\sum_{t=1}^T \frac{t \cdot CF_t}{(1+y)^t}}{P}$. **Modified Duration** measures the percentage change in bond price for a 1% change in yield: $\frac{\Delta P}{P} \approx -D_{mod} \cdot \Delta y$. (3) **Convexity**: Because bond price-yield curves are convex, duration underestimates price increases when yields fall and overestimates price drops when yields rise; convexity acts as the second derivative adjustment.

## Modern Applications & Advanced Significance
Credit Spreads & Default Risk: Corporate bonds trade at a spread over benchmark risk-free sovereign treasuries (Option-Adjusted Spread, OAS), compensating investors for credit risk, liquidity premia, and recovery probability under credit rating downgrades.

## Real-World Impact & Systems
Drives liability-driven investment (LDI) for pension funds, fixed-income immunization strategies, and commercial bank balance sheet asset-liability management (ALM).

## Key Terminology
- **Yield to Maturity (YTM)**: Total rate of return anticipated on a bond if held until it matures, assuming all payments are made and reinvested at the same rate.
- **Macaulay Duration**: Weighted average term to maturity of the cash flows from a bond, measuring sensitivity to interest rate shifts.
- **Credit Spread**: Difference in yield between a riskier corporate debt security and a risk-free benchmark government treasury of equivalent maturity.

## References & Further Exploration
- [[The Inverted Yield Curve - Bond Yields, Term Premia, and Recession Forecasting]]
- [[Central Banking and Monetary Policy - Interest Rates, Reserve Ratios, and QE]]
- Macroeconomic policy briefs and multilateral institutional documentation
- Peer-reviewed research across international economics, finance, and geopolitics
