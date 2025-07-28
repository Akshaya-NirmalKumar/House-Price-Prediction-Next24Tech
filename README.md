# 🏠 House Price Prediction System

This project involves developing a machine learning-based regression model to predict house prices using a wide range of features such as location, size, amenities, and construction attributes. It was completed as part of my **Data Analytics Internship** at **Next24tech Technology & Services**.

---

# 📂 Dataset

Two datasets were used in this project:

1. 📋 **Sample Dataset** — used for preliminary testing and demo.
2. 📊 **Advanced Dataset** — from Kaggle's renowned competition:

🔗 [House Prices - Advanced Regression Techniques (Kaggle)](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)

The dataset contains detailed information on residential homes in Ames, Iowa, including:
- Lot size and location
- Year built and remodeled
- Type of construction
- Basement, garage, and pool features
- Amenities and quality indicators

---

# 🔧 Technologies Used

- 💻 Python 3.x
- 📒 Jupyter Notebook (VS Code)
- 🐼 `pandas`, `numpy`
- 📊 `matplotlib`, `seaborn`
- 🧠 `scikit-learn` (Linear Regression, Random Forest Regressor)

---

# 🧠 Workflow

# 🧹 1. Data Cleaning
- Handled missing values (median, mode imputation)
- Dropped features with excessive nulls
- Converted data types where necessary

# 📊 2. Exploratory Data Analysis (EDA)
- Plotted distributions, correlations, and trendlines
- Identified top features influencing sale prices
- Visualized impact of categorical variables on price

# 🏗️ 3. Feature Engineering
- Label encoding for categorical columns
- Log transformations to reduce skewness
- Feature scaling using normalization techniques

# 🤖 4. Model Building
- Trained models: `LinearRegression`, `RandomForestRegressor`
- Hyperparameter tuning with GridSearchCV (optional)
- Evaluation using RMSE (Root Mean Squared Error)

---

# ✅ Final Result

- 📌 **Model Used**: Random Forest Regressor (best performance)
- 📉 **Root Mean Squared Error (RMSE)**: ~39,652
- 🎯 **Outcome**: Successfully predicted house prices with decent real-world accuracy and interpretability.

---

# 📁 Project Structure
📦 House-Price-Prediction-System
├── SampleDataset.csv
├── AdvancedDataset.csv
├── HousePricePrediction.ipynb
└── README.md


---

## 📷 Sample Output

```text
Root Mean Squared Error: 39652.79

✍️ Author
Akshaya N R
🎓 Final Year BCA Analytics Student
🚀 Data Analytics Intern @ Next24tech
🟣 GitHub Profile




