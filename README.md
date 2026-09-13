# 🏥💰 Insurance Cost Prediction using Machine Learning

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge\&logo=python\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge\&logo=pandas\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge\&logo=numpy\&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?style=for-the-badge\&logo=scikit-learn\&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge\&logo=jupyter\&logoColor=white)

</p>

---

## 📌 Project Overview

This project focuses on predicting **medical insurance charges** using **Machine Learning**.

The model analyzes different customer attributes such as **age, BMI, smoking status, number of children, sex, and region** to estimate the expected insurance cost.

🎯 The main objective is to understand how different factors influence insurance charges and build a Machine Learning model capable of making cost predictions.

---

## 📊 Dataset

The project uses a medical insurance dataset containing information about customers and their insurance charges.

### 🔹 Dataset Features

| Feature              | Description                   |
| -------------------- | ----------------------------- |
| 👤 Age               | Age of the customer           |
| 🚻 Sex               | Gender of the customer        |
| ⚖️ BMI               | Body Mass Index               |
| 👨‍👩‍👧‍👦 Children | Number of children/dependents |
| 🚬 Smoker            | Smoking status                |
| 🌍 Region            | Residential region            |
| 💰 Charges           | Medical insurance cost        |

### 🎯 Target Variable

**`charges`** — Medical insurance charges.

---

## 🛠️ Technologies Used

* 🐍 **Python**
* 🐼 **Pandas**
* 🔢 **NumPy**
* 📊 **Matplotlib**
* 🤖 **Scikit-learn**
* 📓 **Jupyter Notebook**

---

## 🔄 Machine Learning Workflow

```text
📥 Data Collection
       ↓
🧹 Data Cleaning
       ↓
🔍 Exploratory Data Analysis
       ↓
⚙️ Feature Engineering
       ↓
🔄 Data Preprocessing
       ↓
✂️ Train-Test Split
       ↓
🤖 Model Training
       ↓
🔮 Prediction
       ↓
📊 Model Evaluation
```

---

## 🔍 Exploratory Data Analysis

The dataset was explored to understand the relationship between customer attributes and insurance charges.

Key areas analyzed:

* 📈 Distribution of insurance charges
* 👤 Age vs Insurance Charges
* ⚖️ BMI vs Insurance Charges
* 🚬 Smoking Status vs Charges
* 👨‍👩‍👧‍👦 Children vs Charges
* 🌍 Region-wise analysis
* 🔗 Correlation between numerical features

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

* ✅ Checked dataset structure
* ✅ Identified missing values
* ✅ Checked duplicate records
* ✅ Converted categorical variables into numerical form
* ✅ Prepared features and target variable
* ✅ Split data into training and testing sets

---

## 🤖 Machine Learning Model

### 📈 Linear Regression

**Linear Regression** was used to predict insurance charges based on the available customer features.

The model learns the relationship between the input features and the target variable (`charges`) and uses that relationship to make predictions on unseen data.

---

## 📊 Model Evaluation

The model performance was evaluated using:

| Metric      | Purpose                                                  |
| ----------- | -------------------------------------------------------- |
| 📏 MAE      | Measures average absolute prediction error               |
| 📐 MSE      | Measures squared prediction error                        |
| 📊 RMSE     | Measures the typical prediction error                    |
| 🎯 R² Score | Measures how well the model explains the target variable |

### 🏆 Model Performance

**R² Score: ~0.74**

The Linear Regression model achieved an R² score of approximately **0.74**, indicating that the model explains a substantial portion of the variation in insurance charges.

---

## 💡 Key Insights

Some important observations from the analysis:

* 🚬 **Smoking status** has a strong relationship with insurance charges.
* 👤 **Age** influences the overall insurance cost.
* ⚖️ **BMI** can contribute to variations in medical expenses.
* 👨‍👩‍👧‍👦 The number of children/dependents can affect insurance charges.
* 🌍 Insurance charges can vary across different regions.

---

## 📁 Project Structure

```text
Insurance-Cost-Prediction-ML/
│
├── 📓 Insurance_Charges.ipynb
├── 📄 insurance.csv
├── 📖 README.md
└── ⚙️ requirements.txt
```

---

## 🚀 Future Improvements

The project can be improved by experimenting with more advanced Machine Learning algorithms:

* 🌳 Random Forest Regressor
* 🌲 Decision Tree Regressor
* ⚡ XGBoost Regressor
* 🔧 Hyperparameter Tuning
* 🔄 Cross-Validation
* 📊 Advanced Feature Engineering
* 🌐 Model Deployment using Streamlit

---

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

* 🐍 Python for Machine Learning
* 🐼 Data manipulation using Pandas
* 📊 Data visua
