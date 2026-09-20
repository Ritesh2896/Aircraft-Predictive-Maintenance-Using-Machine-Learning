# ✈️ Aircraft Predictive Maintenance Using Machine Learning

A machine learning-based aircraft predictive maintenance project that analyzes aircraft engine sensor data to predict **Remaining Useful Life (RUL)** and support proactive maintenance planning.

---

## 📌 Project Overview

Aircraft engines generate large amounts of sensor data during operation. Analyzing this data can help estimate the remaining useful life of an engine and support maintenance activities before unexpected failure occurs.

This project applies multiple machine learning regression techniques to aircraft engine degradation data and predicts the **Remaining Useful Life (RUL)** of aircraft engines.

The project uses the **NASA C-MAPSS dataset**, with the primary notebook workflow focused on the **FD001 dataset**.

---

## 🎯 Objectives

- Analyze aircraft engine sensor data
- Perform data preprocessing and feature preparation
- Calculate Remaining Useful Life (RUL)
- Train multiple machine learning regression models
- Evaluate model predictions using regression metrics
- Visualize model predictions and residuals
- Demonstrate a predictive maintenance workflow for aircraft engines

---

## 📊 Dataset

This project uses the **NASA C-MAPSS (Commercial Modular Aero-Propulsion System Simulation)** dataset.

The dataset contains simulated aircraft engine run-to-failure data collected through multiple sensor measurements over engine operating cycles.

### Primary Dataset Used

The notebook primarily works with:

- `train_FD001.txt` — Training engine sensor data
- `test_FD001.txt` — Testing engine sensor data
- `RUL_FD001.txt` — Actual RUL values for test engines

---

## 🧠 Remaining Useful Life (RUL)

**Remaining Useful Life (RUL)** represents the estimated number of operational cycles remaining before an aircraft engine reaches its failure condition.

RUL prediction can help support aircraft engine health monitoring and maintenance planning.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- LightGBM
- XGBoost
- CatBoost
- Jupyter Notebook

---

## 🤖 Machine Learning Models

The project experiments with multiple regression algorithms:

- Linear Regression
- Polynomial Regression
- Decision Tree Regression
- Random Forest Regression
- Lasso Regression
- LightGBM Regression
- XGBoost Regression
- CatBoost Regression

These models are used to estimate the Remaining Useful Life of aircraft engines from sensor and operational data.

---

## 🔄 Project Workflow

```text
Aircraft Engine Sensor Data
            ↓
     Data Preprocessing
            ↓
    Feature Preparation
            ↓
       RUL Calculation
            ↓
    Train/Test Preparation
            ↓
  Machine Learning Models
            ↓
      Model Prediction
            ↓
     Model Evaluation
            ↓
      RUL Prediction


      📈 Model Evaluation

The regression models are evaluated using:

Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R² Score

Prediction-error and residual plots are also used to visualize model performance.

📂 Project Structure
Aircraft-Predictive-Maintenance-Using-Machine-Learning/
│
├── CMAPSSData/
│   ├── train_FD001.txt
│   ├── test_FD001.txt
│   └── RUL_FD001.txt
│
├── Predictive_Maintenance_Using_Machine_Learning.ipynb
├── README.md
└── .gitignore

🚀 Applications

This predictive maintenance approach can support:

Aircraft engine health monitoring
Maintenance planning
Engine degradation analysis
Failure prevention
Reduction of unexpected downtime
Data-driven maintenance decisions

📜 Disclaimer

This project is developed for educational and machine learning project purposes using the NASA C-MAPSS dataset.

The predictions produced by the models are intended for experimental and academic analysis and should not be used as a substitute for certified aircraft maintenance procedures or safety-critical decision-making.