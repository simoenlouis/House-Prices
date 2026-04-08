# House Prices: Advanced Regression Techniques
Kaggle Score: (0.13494)
(https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

## 📌 Project Overview
This project aims to predict residential home prices in Ames, Iowa, using 79 explanatory variables. It is a competition hosted on Kaggle where the goal is to practice advanced regression techniques like Random Forest and XGBoost.

## 📊 Performance
- *Top Score (RMSLE):* 0.13494
- *Validation R² Score:* 0.90+
- *Rank:* Top 15% (Approx. 2000 out of 15,000+ competitors)

## 🛠️ Machine Learning Pipeline

### 1. Data Cleaning & Exploratory Data Analysis (EDA)
- *Handling Missing Values:* Imputed numerical nulls with the mean/median and categorical nulls with the most frequent values (Mode).
- *Target Transformation:* Applied log1p transformation to the SalePrice to handle skewness and ensure a normal distribution.

### 2. Feature Engineering
- *New Features:* Created interaction features
- *Encoding:* Converted categorical variables into numerical format using *One-Hot Encoding*.
- *Scaling:* Standardized numerical features using *StandardScaler* to ensure all features contribute equally to the model.

### 3. Modeling & Optimization
- *Algorithms:* Evaluated multiple models including Linear Regression and *XGBoost Regressor*.
- *Hyperparameter Tuning:* Optimized XGBoost parameters to reach the best balance between bias and variance.

## Repository Structure
- data/: Contains train.csv and test.csv.
- notebook.ipynb: The main Jupyter Notebook containing the full analysis and model.
- submission.csv: The final output file submitted to Kaggle.

## Author
-Simoen Louis
-GitHub: simoenlouis

License
This project is licensed under the MIT License.
