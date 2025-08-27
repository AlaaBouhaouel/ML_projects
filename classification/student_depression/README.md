# Student Depression Prediction with Logistic Regression

##  PROJECT OVERVIEW
This project predicts whether a student is at risk of depression based on demographic, lifestyle, and stress-related features.  
The goal is to build a classification model and evaluate its performance.

##  DATASET
- Source: [Student Depression Dataset](<link-if-public>)
- Rows: XXXX
- Features: Gender, Sleep Duration, Financial Stress, Family History, etc.

## METHODOLOGY 
1. Data preprocessing:
   - Filtered only students (removed professionals).
   - Cleaned categorical features with Label Encoding.
   - Converted Sleep Duration to numeric hours.
   - Removed invalid/missing entries.
2. Models trained:
   - Logistic Regression (L1 penalty)
   - Logistic Regression (L2 penalty)
   - Logistic Regression (ElasticNet)

## RESULTS
| Model              | Accuracy | Precision | Recall | F1-score |
|--------------------|----------|-----------|--------|----------|
| Logistic Reg (L2)  | 0.85     | 0.86      | 0.89   | 0.87     |
| Logistic Reg (L1)  | 0.84     | 0.84      | 0.89   | 0.88     |
| ElasticNet         | 0.84     | 0.84      | 0.89   | 0.87     |

## ✅ CONCLUSION
- Logistic Regression with L2 penalty performed the best.
- Strong recall (0.89) → the model captures most positive depression cases, which is important in health-related prediction.
- Future improvements: try Random Forest or Gradient Boosting for comparison.
