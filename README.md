🏠 House Price Prediction – Feature Engineering
📖 Problem

Predict house prices based on various features (location, size, quality, etc.) using the House Prices – Advanced Regression Dataset from Kaggle.

🛠 Solution

Downloaded dataset directly from Kaggle using opendatasets.

Performed data cleaning: handled missing values (median for numeric, mode for categorical).

Applied feature engineering:

One-Hot Encoding for categorical variables

Label Encoding for ordinal variables

Log transformation for skewed target (SalePrice)

Trained a Random Forest Regressor on the processed dataset.

Evaluated model performance using Root Mean Squared Error (RMSE).

Identified top 15 most important features influencing house prices.

🧰 Tools & Libraries

Python

Pandas, NumPy

Matplotlib, Seaborn

scikit-learn

opendatasets

📊 Impact

Improved model performance by handling missing values and applying feature engineering.

Achieved lower RMSE by transforming skewed features.

Provided insights into the most important factors that affect house prices (e.g., Overall Quality, Living Area, Garage Cars).

📂 Files in this Repo

TASK 8 House Prices.ipynb → Colab notebook

data. description.text

README.md → project explanation
