# Credit Default Prediction 

This project builds a high-performance machine learning model for credit default prediction, using a large loan dataset loaded directly from kaggle. The notebook includes full preprocessing, feature engineering, model training, evaluation, and threshold analysis — ultimately achieving ~99% accuracy

---

**Project Description**

Financial institutions rely on accurate default prediction to minimize losses and improve lending decisions.
This project uses a large, real-world–style dataset (LendingClub-like) and trains an XGBoost classifier capable of identifying defaulted vs non-defaulted loans with extremely strong performance.

**The notebook:**

- Loads a large dataset -> 2694776 Rows X 142 Columns

Performs deep preprocessing

Builds key credit-risk features

Feature engineering using correlation

Feature Selection using RandomForestClassifier

Studies class imbalance and threshold tuning

Trains an XGBoost classifier for Prediction

Evaluates using multiple metrics

