# 💉 Pima Indians Diabetes Exploratory Data Analysis (EDA)

This repository contains an in-depth Exploratory Data Analysis (EDA) performed on the Pima Indians Diabetes Dataset. The primary goal is to understand the distribution, relationships, and statistical properties of the features to inform future Machine Learning model development for predicting diabetes onset.

## 🚀 Analysis Workflow

The analysis was conducted in several key stages, focusing on data understanding, quality assessment, feature engineering, and visualization:

1.  **Data Loading and Initial Inspection:** Checking the dataset shape, data types, and initial summary statistics.
2.  **Handling Missing Values (Zero Imputation):** Identifying features where a value of `0` is biologically impossible (e.g., Blood Pressure, BMI, Glucose) and treating them as missing values (`NaN`).
3.  **Missing Value Treatment:** Imputing the treated missing values using appropriate statistical measures (e.g., mean or median).
4.  **Univariate Analysis:** Analyzing the distribution of individual features using histograms and box plots to identify skewness and outliers.
5.  **Bivariate Analysis:** Exploring the relationship between each feature and the target variable (`Outcome`).
6.  **Multivariate Analysis:** Analyzing relationships among multiple features, including a pairplot of the most important variables.

## 📊 Key Findings

* **Significant Missing Data:** Several key features like `Glucose`, `BloodPressure`, and `BMI` had a substantial number of zero values (treated as missing), necessitating careful imputation.
* **Feature Distribution:** Features like `Insulin` and `SkinThickness` showed high skewness and numerous outliers.
* **Correlation with Outcome:** `Glucose` and `BMI` emerged as the features with the strongest positive correlation with the `Outcome` (Diabetes status).

## 🛠️ Technologies Used

* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, SciPy (stats)

## 📁 How to Run

1.  Clone this repository: `git clone YOUR_REPO_URL`
2.  Install dependencies: `pip install pandas numpy matplotlib seaborn scipy`
3.  Open the notebook: `jupyter notebook diabetes_EDA.ipynb`
4.  Execute the cells sequentially to reproduce the analysis.

---
