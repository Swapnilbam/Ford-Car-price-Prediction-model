# 🚗 Ford Car Price Prediction using Machine Learning

An end-to-end Machine Learning project that predicts the selling price of Ford cars using Linear Regression. This project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and model evaluation.

---

## 📌 Project Overview

The objective of this project is to predict the selling price of Ford cars based on various vehicle attributes such as:

- Model
- Year
- Transmission
- Mileage
- Fuel Type
- Tax
- MPG
- Engine Size

Two different encoding techniques were implemented and compared:

- **One-Hot Encoding + Linear Regression**
- **Label Encoding + Linear Regression**

The models were evaluated using standard regression metrics to compare their performance.

---

## 📂 Project Structure

```
Ford-Car-Price-Prediction/
│
├── data/
│   └── ford.csv
│
├── notebook/
│   └── Ford_Car_Price_Prediction.ipynb
│
├── images/
│   ├── Correlation Heatmap.png
│   ├── price Distribution.png
│   ├── Milage relation with price.png
│   └── model vs price.png
│
├── README.md
└── requirements.txt
```

---

## 📊 Exploratory Data Analysis

Performed comprehensive EDA including:

- Dataset overview
- Missing value analysis
- Duplicate value removal
- Data type inspection
- Statistical summary
- Correlation analysis
- Distribution plots
- Outlier detection
- Feature relationship analysis

---

## ⚙️ Feature Engineering

The preprocessing pipeline included:

- Duplicate removal
- Label Encoding
- One-Hot Encoding
- Feature Scaling using StandardScaler
- Feature selection
- Train-Test Split

---

## 🤖 Models Trained

### Model 1

- Linear Regression
- One-Hot Encoded Features

### Model 2

- Linear Regression
- Label Encoded Features

Both models were trained independently and their performances were compared.

---

## 📈 Model Evaluation

Regression metrics used:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score
- Adjusted R² Score

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## 📌 Learning Outcomes

Through this project, I gained hands-on experience in:

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Categorical Encoding Techniques
- Feature Scaling
- Linear Regression
- Regression Model Evaluation
- Model Comparison

---

## 🚀 Future Improvements

- Ridge Regression
- Lasso Regression
- ElasticNet
- Random Forest Regressor
- XGBoost Regressor
- Hyperparameter Tuning
- Deployment using FastAPI & Streamlit

---

## 📜 License

This project is developed by Swapnil Bam 
