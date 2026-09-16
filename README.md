# Hospital-Readmission-Prediction
Hospital Readmission Prediction using Logistic Regression with L2 Regularization
# Hospital Readmission Prediction

## Case Study

This project predicts whether a patient will be readmitted to the hospital within 30 days using Logistic Regression with L2 regularization.

## Objective

To build a machine learning model that predicts 30-day hospital readmission based on patient demographic, clinical, and hospitalization-related features.

## Dataset Features

The dataset contains:

- Age
- Gender
- Primary Diagnosis
- Number of Procedures
- Days in Hospital
- Comorbidity Score
- Discharge Destination

Target variable:

- `readmitted`

## Methodology

1. Load and inspect the dataset
2. Separate features and target
3. Preprocess numerical and categorical features
4. Apply Standard Scaling and One-Hot Encoding
5. Train Logistic Regression with L2 regularization
6. Evaluate using ROC-AUC
7. Generate confusion matrix and classification report
8. Analyze False Positive and False Negative rates
9. Generate ROC curve
10. Train the final model on the complete training dataset
11. Generate predictions for the test dataset

## Model

**Algorithm:** Logistic Regression  
**Regularization:** L2  
**Evaluation Metric:** ROC-AUC

## Clinical Considerations

False negatives can be clinically important because a patient predicted as low-risk may actually be readmitted. False positives may result in additional follow-up or resource utilization.

The appropriate classification threshold should therefore consider the relative clinical costs of false positives and false negatives.

## Files

- `hospital_readmission_prediction.ipynb` — Complete Google Colab notebook
- `train_df.csv` — Training dataset
- `test_df.csv` — Test dataset
- `submission.csv` — Final model predictions

## Tools Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab
- GitHub
