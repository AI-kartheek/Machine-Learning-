In this classification problem we create a model with ``custom pipelines`` that predicts the probability of females having diabetes. For this project we had some **Class imbalance** in the data, so we consider **recall score** rather than Accuracy Score.

### Steps I performed in this project:
1) KNN imputer for missing data
2) Feature Engineering
  a) Outliers Handling
  b) Gaussian Transformation
3) Model Selection and Hyper Parameter Tuning
4) Feature Selection and Model Evaluation
5) Model Goodness Check using ROC Curve
6) Pipeline Creation For Prediction
7) Performing Predictions.

At last we got a very good Test Data **Recall Score = 87.234 %** with Random Forest Classifier and **ROC_Auc Score = 0.882**.
