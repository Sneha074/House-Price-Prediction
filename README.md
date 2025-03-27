# House-Price-Prediction

This data science project series walks through step by step process of how to build a real estate price prediction. Let's understand this project using STAR technique: 

# Situation (S):
The real estate market in Bengaluru is highly dynamic, with property prices varying based on multiple factors such as location, size, number of bedrooms, and amenities. Buyers and sellers often struggle with price estimation, leading to mispricing and financial losses.

To solve this problem, we needed a data-driven approach that could accurately predict house prices based on historical data and relevant features.

# Task (T):

The objective of this project was to:
* Develop a machine learning model to predict house prices in Bengaluru.
* Ensure high model accuracy by applying advanced data science techniques like outlier removal, feature engineering, hyperparameter tuning, and cross-validation.

# Action (A):

1️. Data Collection & Preprocessing 

* Dataset Source: Kaggle (Bangalore Home Prices Dataset)
* Libraries Used: Pandas, NumPy for data manipulation

2. Loaded data and performed data cleaning:

* Removed duplicates and missing values.
8 Standardized unit measurements (sq. ft.).

3. Outlier detection and removal:

* Used Z-score and IQR methods to eliminate extreme values.
* Example: Properties listed at abnormally high or low prices were removed.

4. Feature Engineering:

* Created a new feature price per square foot for better prediction.
* Used one-hot encoding for categorical features like location.
* Reduced dimensionality by selecting the most important features.

5. Model Building
   
* Libraries Used: Scikit-learn, Matplotlib, Seaborn
* Trained different models:
* Linear Regression (baseline model).
* Decision Trees & Random Forest for comparison.
* Hyperparameter tuning using GridSearchCV to improve performance.
* K-Fold Cross Validation to ensure model generalization.

* Final Model: Achieved a high accuracy with Linear Regression, as it performed well on numerical real estate data.

# Result (R):

* ✅ Successfully built an end-to-end house price prediction system with:
* ✅ Accurate price predictions based on real estate data.
* ✅ Improved real estate decision-making for buyers and sellers.
* ✅ Applied key data science concepts, strengthening machine learning skills.
