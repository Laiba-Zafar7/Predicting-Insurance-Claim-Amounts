# Predicting-Insurance-Claim-Amounts
## 📝 Project Description Medical insurance companies often need to estimate the expected claim amounts for policyholders.   This project uses **machine learning regression** techniques to predict the **medical insurance charges** based on a person’s demographics and lifestyle factors such as age, BMI, and smoking status. 

## 📌 Objective
To **predict the medical insurance claim amount** for individuals based on their personal and lifestyle data.  
By identifying key cost drivers, the project also aims to provide insights into how various factors influence insurance charges.



## 📂 Dataset
**Name:** Medical Cost Personal Dataset  
**Description:** Contains information about individuals’ age, sex, BMI, number of children, smoking status, region, and insurance charges.



## 🚀 Approach

### 1. Data Preparation
- Loaded dataset and inspected for missing values.
- Converted categorical variables (e.g., `sex`, `smoker`, `region`) into numerical format using **one-hot encoding**.
- Checked correlations between features and the target variable (`charges`).

### 2. Model Development
- Selected **Linear Regression** as the primary model.
- Split data into **training** and **testing** sets.
- Trained the model to predict `charges` using all available features.

### 3. Visualization & Insights
- Visualized the effect of **BMI**, **age**, and **smoking status** on insurance charges using scatter plots and boxplots.
- Observed strong correlations between smoking status and higher insurance charges.

### 4. Model Evaluation
- Evaluated predictions using:
  - **Mean Absolute Error (MAE)**
  - **Root Mean Squared Error (RMSE)**



## 📊 Results & Insights

| Metric | Value       |
|--------|------------|
| MAE    | 4,267.21   |
| RMSE   | 6,191.69   |

### Key Findings:
- **Smoking status** has the most significant impact — smokers tend to have much higher claim amounts.
- **BMI** and **age** are also strong predictors of charges; higher BMI and older age generally lead to increased costs.
- Linear Regression performs reasonably well, but non-linear models could potentially improve accuracy.


## 🛠️ Skills Used
- **Regression Modeling:** Linear Regression (Scikit-learn)
- **Data Preprocessing:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Model Evaluation:** MAE, RMSE

