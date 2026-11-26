---
title: "Fractal Geometry - Hausdorff Dimension, Iterated Function Systems, and Self-Similarity"
tags: [mathematics, fractals, geometry, dynamical-systems]
related: [[[Fractals and Chaos Theory - The Mandelbrot Set and Strange Attractors]], [[Point-Set Topology - Open Sets, Compactness, and Connectedness]]]
created: 2026-11-26
updated: 2026-11-26
---

# Fractal Geometry - Hausdorff Dimension, Iterated Function Systems, and Self-Similarity

## Overview
Fractal Geometry, pioneered by Benoit Mandelbrot (1975), investigates irregular geometric shapes displaying nested self-similarity across infinite spatial scales.

## Core Mechanics & Foundations
Hausdorff Dimension ($D_H$): Classical topological spaces have integer dimensions (points=0, lines=1, planes=2). The Hausdorff dimension generalizes metric spaces to real values: If an object is scaled down by linear factor $s$ into $N$ self-similar copies, its similarity dimension is $D = \frac{\log N}{\log(1/s)}$. The Cantor set has dimension $\frac{\log 2}{\log 3} \approx 0.631$; the Koch snowflake has dimension $\frac{\log 4}{\log 3} \approx 1.262$.

## Modern Applications & Advanced Significance
Iterated Function Systems (IFS): Michael Barnsley proved the Collage Theorem: Any compact metric subset can be generated as the unique attractor of a finite set of contractive affine mappings ($W = \bigcup w_i$), enabling procedural generation of natural foliage (Barnsley fern) and fractal image compression.

## Real-World Impact & Systems
Procedural terrain generation in video game engines, cellular antenna miniaturization (fractal antennas), pulmonary bronchial airway modeling.

## Key Terminology
- **Hausdorff Dimension**: Metric dimension that assigns a non-negative real number to a metric space, non-integer for fractals.
- **Self-Similarity**: Property where an object is exactly or approximately similar to a part of itself across different magnification scales.
- **Iterated Function System (IFS)**: Method of constructing fractals resulting in self-similar attractors of contractive mappings.


## References & Further Exploration
[[Fractals and Chaos Theory - The Mandelbrot Set and Strange Attractors]], [[Point-Set Topology - Open Sets, Compactness, and Connectedness]]
