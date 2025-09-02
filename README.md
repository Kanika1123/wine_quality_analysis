🍷 Wine Quality - Exploratory Data Analysis (EDA)
📌 Project Overview

This project explores the Red Wine Quality dataset (Cortez et al., 2009) using Python.
The goal is to understand the relationships between various physicochemical features (like alcohol, acidity, sulphates, etc.) and wine quality ratings.

Rather than training a predictive model, this notebook focuses on data cleaning, visualization, and statistical insights to uncover patterns in the dataset.

📂 Dataset

Source: Wine Quality Dataset (Kaggle)
Format: CSV
Rows: 1,599
Columns: 12 (11 features + quality label)
Features include:
Fixed acidity
Volatile acidity
Citric acid
Residual sugar
Chlorides
Free sulfur dioxide
Total sulfur dioxide
Density
pH
Sulphates
Alcohol
Quality (target variable: 0–10 scale)

🛠️ Tools & Libraries

Python
Pandas (data handling)
Matplotlib & Seaborn (visualizations)

📊 Exploratory Analysis Performed

Dataset structure overview (.shape, .info(), .describe())
Missing values check
Distribution of Wine Quality (countplot)
Correlation Heatmap of all features
Boxplots to study relation between:
Alcohol content vs Quality
Volatile acidity vs Quality
Selected features (alcohol, sulphates, citric acid)

📌 Key Insights

Higher alcohol content generally correlates with better wine quality.
Higher volatile acidity tends to reduce wine quality.
Sulphates and citric acid also play an important role in distinguishing good quality wines.
The dataset is slightly imbalanced (most wines are rated 5–6).

✅ Conclusion

This project demonstrates how exploratory data analysis (EDA) can provide meaningful insights before moving to predictive modeling.
Future steps could include training machine learning models (like Random Forest, Logistic Regression, or XGBoost) to predict wine quality based on chemical properties.
