---
title: "High-Frequency Trading (HFT) - Algorithmic Market Making, Latency Arbitrage, and Flash Crashes"
tags:
  - finance
  - algorithmic-trading
  - market-microstructure
  - fintech
related:
  - "[[The Efficient Market Hypothesis (EMH) and Market Anomalies]]"
  - "[[The 2008 Global Financial Crisis - Subprime Mortgages, CDOs, and Systemic Meltdown]]"
created: 2026-11-26
updated: 2026-11-26
---

# High-Frequency Trading (HFT) - Algorithmic Market Making, Latency Arbitrage, and Flash Crashes

## Overview
High-Frequency Trading (HFT) is an automated trading paradigm characterized by ultra-low-latency execution, high turnover rates, and computer algorithmic order routing operating at microsecond and nanosecond intervals.

## Core Mechanics & Foundations
Strategies & Latency Competition: HFT firms operate primarily as automated, non-discretionary market makers, capturing bid-ask spreads across fragmented electronic exchanges (e.g., NYSE, NASDAQ, BATS) while ending trading days with virtually zero net overnight inventory. Dominant strategies include: (1) **Market Making**: Continuously quoting buy and sell orders, earning fractional tick spreads; (2) **Latency Arbitrage**: Exploiting price discrepancies for the same asset across geographically separated exchanges before slower market feeds can update, driving massive infrastructure investments in fiber-optic cables, microwave networks, and exchange server co-location; (3) **Order Flow Prediction**: Identifying large institutional block orders across lit markets to trade ahead of market impact.

## Modern Applications & Advanced Significance
Systemic Risks & The Flash Crash: On May 6, 2010, the US stock market suffered the **Flash Crash**, where the Dow Jones plummeted nearly 1,000 points (9%) in minutes before rapidly rebounding. Algorithmic feedback loops caused HFT market makers to simultaneously withdraw liquidity across electronic order books, creating a temporary liquidity vacuum.

## Real-World Impact & Systems
Prompted regulatory interventions including circuit breakers, Limit-Up/Limit-Down (LULD) bands, and the SEC Consolidated Audit Trail (CAT).

## Key Terminology
- **Latency Arbitrage**: Exploiting microscopic time differences to trade on market price information before other participants receive it.
- **Co-Location**: Placing algorithmic trading servers in the exact same physical datacenter as exchange matching engines to minimize speed-of-light transit delays.
- **Flash Crash**: A rapid, deep, and volatile drop in asset prices occurring within an extremely compressed timeframe due to algorithmic feedback loops.

## References & Further Exploration
- [[The Efficient Market Hypothesis (EMH) and Market Anomalies]]
- [[The 2008 Global Financial Crisis - Subprime Mortgages, CDOs, and Systemic Meltdown]]
- Macroeconomic policy briefs and multilateral institutional documentation
- Peer-reviewed research across international economics, finance, and geopolitics
