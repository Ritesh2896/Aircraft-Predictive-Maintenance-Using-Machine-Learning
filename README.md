# ✈️ Aircraft Predictive Maintenance Using Machine Learning

A machine learning-based aircraft predictive maintenance project that analyzes aircraft engine sensor data to predict **Remaining Useful Life (RUL)** and support proactive maintenance decisions.

---

## 📌 Project Overview

Aircraft engines generate large amounts of sensor data during their operation. Analyzing this data can help estimate the remaining useful life of an engine and identify potential maintenance requirements before failure occurs.

This project uses machine learning techniques to analyze aircraft engine degradation data and predict the **Remaining Useful Life (RUL)** of aircraft engines.

The project is implemented using the **NASA C-MAPSS FD001 dataset** and compares multiple machine learning regression models.

---

## 🎯 Objectives

- Analyze aircraft engine sensor data.
- Perform data preprocessing and feature preparation.
- Calculate engine Remaining Useful Life (RUL).
- Train multiple machine learning regression models.
- Compare model predictions using evaluation metrics.
- Develop a predictive maintenance approach for aircraft engines.

---

## 📊 Dataset

This project uses the **NASA C-MAPSS FD001 dataset**.

The dataset contains simulated aircraft engine run-to-failure data collected from multiple sensors under different operating conditions.

### Dataset Files

```text
CMAPSSData/
├── train_FD001.txt
├── test_FD001.txt
└── RUL_FD001.txt
````

* `train_FD001.txt` — Training sensor data
* `test_FD001.txt` — Testing sensor data
* `RUL_FD001.txt` — Actual Remaining Useful Life values for test engines

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* LightGBM
* XGBoost
* CatBoost
* Jupyter Notebook

---

## 🤖 Machine Learning Models

The project experiments with multiple regression algorithms:

* Linear Regression
* Polynomial Regression
* Decision Tree Regression
* Random Forest Regression
* Lasso Regression
* LightGBM Regression
* XGBoost Regression
* CatBoost Regression

These models are used to estimate the Remaining Useful Life of aircraft engines.

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
    Train/Test Data Split
            ↓
    Machine Learning Models
            ↓
       Model Prediction
            ↓
    Model Evaluation
            ↓
    RUL Prediction Results
```

---

## 📈 Model Evaluation

The models are evaluated using regression metrics such as:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

Prediction and residual plots are also used to visualize model performance.

---

## 📂 Project Structure

```text
Aircraft-Predictive-Maintenance-Using-Machine-Learning/
│
├── CMAPSSData/
│   ├── train_FD001.txt
│   ├── test_FD001.txt
│   └── RUL_FD001.txt
│
├── Predictive_Maintenance_Using_Machine_Learning.ipynb
│
├── README.md
│
└── .gitignore
```

---

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/Ritesh2896/Aircraft-Predictive-Maintenance-Using-Machine-Learning.git
```

### 2. Open the project folder

```bash
cd Aircraft-Predictive-Maintenance-Using-Machine-Learning
```

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn lightgbm xgboost catboost jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the notebook

Open:

```text
Predictive_Maintenance_Using_Machine_Learning.ipynb
```

and run the cells sequentially.

---

## 💡 Key Concept

### Remaining Useful Life (RUL)

Remaining Useful Life represents the estimated number of operational cycles remaining before an aircraft engine reaches its failure condition.

Predicting RUL can help maintenance teams plan maintenance activities before unexpected engine failure.

---

## 🚀 Applications

This type of predictive maintenance approach can support:

* Aircraft engine health monitoring
* Maintenance planning
* Failure prevention
* Reduced unexpected downtime
* Data-driven maintenance decisions

---

## 🔮 Future Improvements

Possible future improvements include:

* Hyperparameter optimization
* Feature engineering
* Time-series based deep learning models
* LSTM/GRU based RUL prediction
* Real-time engine health monitoring
* Deployment as a web application
* Model API using FastAPI or Flask

---

## 👨‍💻 Author

**Ritesh**

GitHub:
[https://github.com/Ritesh2896](https://github.com/Ritesh2896)

---

## 📜 Disclaimer

This project is developed for educational and machine learning project purposes using the NASA C-MAPSS dataset.

```

### GitHub mein kaise lagana hai

Tumhari repository open karo:

:contentReference[oaicite:0]{index=0}

Phir **README.md → Edit ✏️** par click karke upar wala content paste karo → **Commit changes**.

**Ek cheez check kar lena:** README mein notebook ka naam exactly tumhare actual `.ipynb` filename ke same hona chahiye. Agar tum mujhe current GitHub repo ka screenshot bhej do, main README ko tumhari actual file structure ke according exact kar dunga.
```
