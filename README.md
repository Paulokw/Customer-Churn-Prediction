# Customer-Churn-Prediction
This is a predictive model used to predict whether or not a customer will leave or stay.
I obtained the dataset from kaggle, used XGBOOST and LGBM as the models for fitting and prediction.
For data preprocessing, since this is an imbalanced dataset I applied ADASYN to deal which is known for working best with noisy data and data which is difficult to establish a boundary line, applied one hot encoding for the categorical features and applied scaling to standardize the data.
I evaluated my model using the Precision-Recall Curve as opposed to the ROC-AUC Curve since it was an imbalanced dataset and adjusted the threshold to favour Precision over Recall as we were more focused on emphasizing on the accuracy of our true negative predictions.
