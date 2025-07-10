# Week-7-AI-Ethics

# Fairness in AI: COMPAS Dataset Bias Mitigation

This project explores bias mitigation in machine learning using the COMPAS dataset, which predicts the likelihood of criminal recidivism. The focus is on identifying and addressing racial bias using the **Reweighing** technique from the AIF360 fairness library.

## Objectives

- Detect potential racial bias in predictions.
- Apply fairness-aware preprocessing (Reweighing).
- Evaluate fairness metrics (e.g., False Positive Rate Difference).
- Visualize model outcomes across different race groups.

## Tools & Libraries

- Python
- Pandas, NumPy
- scikit-learn
- Matplotlib
- AIF360 (AI Fairness 360 Toolkit)

## Key Steps

1. Load and split the COMPAS dataset.
2. Apply the Reweighing algorithm to mitigate racial bias.
3. Train a logistic regression classifier.
4. Evaluate performance and fairness metrics.
5. Visualize false positive rates by race.

## Known Issues

Due to some execution errors (e.g., graph not displaying and compatibility challenges), the final visualization step may not render correctly in all environments.

## Ethical Reflection

This project aims to align with ethical AI principles by promoting fairness, transparency, and accountability when developing predictive models, especially in high-stakes areas like criminal justice.

