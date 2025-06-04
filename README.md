# Brains, Weighted Distributions, and KL-Divergence

This notebook presents an analytical and numerical second-order approximation of the KL-divergence for weighted distributions. For a full discussion, [see my post on Medium.](https://medium.com/the-quantastic-journal/the-kullback-leibler-divergence-for-weighted-density-functions-f6672874d519)

## Motivation

The goal of this notebook is to explore ways to characterize any system that collects data and attempts to create a predictive model of reality through an imperfect and potentially biased process.

For example, consider the brain:
* The data it collects may be biased and imperfect due to sensory limitations
* This applies to both biological brains and artificial systems

## Imperfect Sampling

In such systems, the data collection process may not represent the true distribution of the observable variable. For example, it may oversample some ranges of values while undersampling others.

The brain then attempts to reconstruct the real distribution and minimize the discrepancy between its internal prediction and reality.

This idea is conceptually related to the Free Energy Principle which also relies on KL-divergence

## Bottom line
This calculation will show that the statistical sampling and the bias provide decoupled contributions to the KL divergence, at least up to a second-order expansion. This knowledge can help detect and disentangle biases and possibly provide insight into how the brain attempts to reconstruct the underlying distribution.
