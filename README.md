# 🧠 EDA for Feature Selection – Predicting Historical Cost of Ride

## 📌 Project Objective
This project focuses on performing detailed **Exploratory Data Analysis (EDA)** to identify which features contribute meaningfully to predicting the `Historical_Cost_of_Ride`. The main goal is to **select relevant features**, eliminate redundant ones, and transform skewed variables to prepare the data for machine learning.

---

### ✅ 1. Data Exploration
- Loaded and reviewed the dataset structure.
- Checked for missing values, column types, and basic statistics using Pandas.

### ✅ 2. Univariate Analysis
- Visualized individual feature distributions using histograms and KDE plots.
- Analyzed summary statistics like mean, median, and standard deviation.
- Detected outliers and skewness in numeric features.

### ✅ 3. Bivariate Analysis
- Created scatter plots for each feature vs. the target variable (`Historical_Cost_of_Ride`) to:
  - Assess correlation visually
  - Understand trends and feature importance

### ✅ 4. Feature Assessment & Selection
- Identified:
  - Irrelevant or constant features
  - Redundant/highly correlated features (via correlation matrix)
  - Features needing transformation (e.g., log or normalization)
- Finalized a cleaned, relevant feature set for modeling.

---

## 🛠 Tools & Technologies
- **Python** (Pandas, NumPy)
- **Visualization**: Matplotlib, Seaborn
- **Notebook**: Jupyter / Colab

---

## 📊 Key Learnings
- EDA is critical for building effective, interpretable, and efficient models.
- Visualization helped reveal hidden patterns, relationships, and outliers.
- Proper feature selection can significantly improve model performance and reduce overfitting.

