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


## 🟢 [Kidney Stone Classification](./kidney-stone-risk-analysis.ipynb)

- **Overview**: 🩺 Classification of kidney stone presence using tabular data.

- **Dataset**: 📊 Tabular data with columns 'gravity', 'ph', 'osmo', 'cond', 'urea', 'calc', and 'target'. The target column indicates the presence of kidney stones.

- **Models Used**:
  - **Random Forest**
  - **XGBoost**
  - **Neural Network**

- **Performance Metrics**:
  - **Accuracy**: 🎯 0.8889
  - **Precision**: 📏 1.0000
  - **Recall**: 🔄 0.7500
  - **F1 Score**: 🧩 0.8571
  
- **Key Insights**: 🔍
  - The models demonstrated strong precision and good overall performance, with particularly high precision indicating few false positives.
  - The dataset contains important features related to urine analysis that help predict kidney stone presence.
- **Techniques Used**:
  - 🛠️ Data Preprocessing: Handling missing values, encoding categorical variables, and feature scaling.
  - 🧠 Models: Random Forest, XGBoost, and Neural Network.
  - 🧮 Evaluation Metrics: Accuracy, Precision, Recall, and F1 Score.
- **Challenges**:
  - The small dataset size posed a challenge for model generalization.
  - Further data collection and feature engineering could help improve model robustness and accuracy.
- **References**: 📚
  - **Dataset**: Ghadiya, H. (2023). Kidney Stone Data. Retrieved from [https://www.kaggle.com/datasets/harshghadiya/kidneystone/data](https://www.kaggle.com/datasets/harshghadiya/kidneystone/data). Provided by Harsh Ghadiya. License: CC BY 4.0.

## 📈 [Parkinson Detection](./Parkinson-Disease-Detection.ipynb)

- **Overview**: 🧠 Classification of Parkinson’s disease using nonlinear recurrence and fractal scaling properties from voice data.
- **Dataset**: 📊 Features extracted from voice recordings to predict Parkinson’s disease. The dataset includes nonlinear metrics of fundamental frequency variation.
- **Model Performance**:
  - **Best Models**: 🎯 Random Forest, XGBoost, and CatBoost
  - **Accuracy**: 94.87%
  - **F1 Score**: 94.52%
- **Techniques Used**:
  - 🛠️ Data Preprocessing: Scaling and splitting the dataset.
  - 🧠 Models: Logistic Regression, Decision Tree, Random Forest, Support Vector Classifier, XGBoost, and CatBoost.
  - 🧮 Evaluation Metrics: Accuracy and F1 Score.
- **Key Insights**: 🔍
  - Ensemble models (Random Forest, XGBoost, and CatBoost) achieved the best performance.
  - Nonlinear voice metrics are highly effective in distinguishing between Parkinson's and non-Parkinson's cases.
- **References**: 📚
  - Little MA, McSharry PE, Roberts SJ, Costello DAE, Moroz IM. *Exploiting Nonlinear Recurrence and Fractal Scaling Properties for Voice Disorder Detection.* BioMedical Engineering OnLine 2007, 6:23 (26 June 2007). [Link](https://biomedical-engineering-online.biomedcentral.com/articles/10.1186/1475-925X-6-23)
