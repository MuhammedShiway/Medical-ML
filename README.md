# 🩺 Medical Machine Learning Repository

Welcome to our Medical ML Repository, where we harness the power of machine learning to tackle challenging medical problems! 🌟

## 📈 [Differentiated Thyroid Cancer Recurrence Prediction](./Differentiated-Thyroid-Cancer-Recurrence.ipynb)

- **Features**: 📊 Mostly categorical (except 'Age')
- **Model Performance**: 🎯 100% accuracy with Random Forest
- **Key Insights**: 🔑 The most important features are 'Response', 'Risk', 'N' {Node}, 'T' {Tumor}, 'Age', 'Adenopathy', and 'Stage'.
- **Feature Importance**: Top 7 features gets us to 100% accuracy

- **References**: 
   - Borzooei, S., Briganti, G., Golparian, M. et al. Machine learning for risk stratification of thyroid cancer patients: a 15-year cohort study. Eur Arch Otorhinolaryngol (2023). https://doi.org/10.1007/s00405-023-08299-w


## 📈 [Heart Attack Prediction](Heart-Attack-Prediction.ipynb)

- **Overview**: Predicting the likelihood [classification] of a heart attack
- **Accuracy**: Achieved an accuracy of 88.52%.
- **Techniques Used**: 
  - Data Normalization: To improve model performance 
  - Hyperparameter Optimization: Employed GridSearch and Optuna 
- **References**: 
   - Rahman, R. (2021). Heart Attack Analysis & Prediction Dataset [Data set]. Kaggle. https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset



## 📈 [Obesity Prediction - Classification](Obesity-Classification-98-11-orig-91-47-comp.ipynb)

- **Overview**: Predicts obesity class based on various health indicators
- **Accuracy**: 98.11% Accuracy on base data and 91.47% on synthetic data.
- **Techniques Used**: 
  - Model Types: XGBoost, LGBM, CatBoost, HistGradBoost
  - Hyperparameter Optimization + Ensemble: Optuna 

- **References**: 
   - Fabio Mendoza Palechor, and ,Alexis de la Hoz Manotas. (2023). Obesity or CVD risk (Classify/Regressor/Cluster) [Data set]. Kaggle. https://doi.org/10.34740/KAGGLE/DSV/7009925

   - Walter Reade, Ashley Chow. (2024). Multi-Class Prediction of Obesity Risk. Kaggle. https://kaggle.com/competitions/playground-series-s4e2

