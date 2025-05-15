# Predictive Maintenance: Failure Prediction Using Feature Engineering

## Overview

This project explores predictive maintenance by applying advanced feature engineering and machine learning to sensor data for early failure detection.

## Research Motivation

Accurate failure prediction reduces downtime and maintenance costs. This work evaluates how time-domain, frequency-domain, and domain-specific features improve model performance.

## Methodology

- Baseline model: Gradient Boosting on raw features.
- Feature engineering: rolling stats, lag features, domain interactions, FFT, and automated tsfresh extraction.
- Evaluation: accuracy, ROC AUC, confusion matrix, classification report.

## Key Findings

Feature engineering significantly improves prediction accuracy and model robustness, especially with FFT and tsfresh features.

## Future Work

- Investigate deep learning (LSTM, Transformers).
- Develop real-time prediction pipelines.
- Enhance feature interpretability with domain knowledge.

## Usage

1. Clone the repo
2. Install dependencies (`pip install -r requirements.txt`)
3. Run scripts/notebooks to reproduce results

## Dependencies

- pandas, numpy, scikit-learn, imbalanced-learn, scipy, matplotlib, tsfresh

---

**Author:** Mandadhi Bharath Simha Reddy  
**Date:** May 2025
