# Bias Audit of a Healthcare Machine Learning Model

## Overview
This project conducts a bias and fairness audit on a healthcare ML model using the Breast Cancer dataset. 
A simulated gender attribute is introduced to analyze potential demographic bias in model predictions.

## Objective
- Evaluate fairness across gender groups
- Apply multiple fairness metrics
- Implement a bias mitigation strategy
- Compare model performance before and after mitigation

## Dataset
- Breast Cancer Wisconsin dataset (scikit-learn)
- Synthetic gender attribute added for fairness analysis

## Model
- Logistic Regression
- Standardized numerical features

## Fairness Metrics
- Statistical Parity Difference (SPD)
- Disparate Impact (DI)
- Equal Opportunity Difference (EOD)

Metrics were calculated manually and using the AIF360 library.

## Bias Mitigation
- Pre-processing mitigation using **Reweighing (AIF360)**
- Model retrained using instance weights
- Fairness metrics compared before and after mitigation

## Results
- Bias was observed between gender groups prior to mitigation
- Reweighing reduced disparities across key fairness metrics
- Minor trade-off between accuracy and fairness was observed

## Ethical Considerations
Bias in healthcare ML systems can result in unequal treatment across demographic groups. 
This audit demonstrates the importance of fairness evaluation and mitigation in sensitive domains.

## My Role
I independently designed and implemented the bias audit, fairness evaluation, mitigation strategy, and documentation.

## How to Run
1. Install dependencies:
2. Open the notebook:

## Outputs
- Fairness metric visualizations  
- Accuracy comparison before and after mitigation  
- Reproducible bias audit workflow
