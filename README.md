# Google-Colab-File-Fire-Risk-Prediction-System
# 🔥 Fire Risk Prediction System

This project is a Machine Learning-based system to predict **Fire Risk Severity** using environmental and sensor data. It was developed as part of the AI Bootcamp Lab Project.

## 📌 Project Goals

- Predict the **fire risk score** using regression techniques.
- Classify **fire risk levels** (Low, Medium, High) using classification algorithms.
- Evaluate and compare model performances.
- Perform complete end-to-end data processing and analysis.

---

## 📁 Dataset

The project uses two CSV files:
- `fire_risk_train.csv` – for training
- `fire_risk_test.csv` – for evaluation

Each file contains multiple features like:
- Temperature
- Humidity
- Wind Speed
- Gas readings
- And other environmental indicators

---

## 📊 Tasks Breakdown

### 1. 🧪 Exploratory Data Analysis (EDA)
- Checked null values
- Visualized distributions
- Statistical summaries

### 2. 🔧 Data Preprocessing
- Standardization of features using `StandardScaler`
- Handling missing values
- Feature-target split

### 3. 📈 Regression Modeling
- Linear Regression
- Ridge Regression
- Random Forest Regressor

**Evaluation Metrics:**
- RMSE (Root Mean Squared Error)
- R² Score

### 4. 🧠 Classification Modeling
- Converted risk scores into 3 classes: **Low**, **Medium**, **High**
- Applied:
  - Logistic Regression
  - Random Forest Classifier
  - Decision Tree

**Evaluation Metrics:**
- Accuracy
- Confusion Matrix
- Classification Report

---

## 📌 Key Results

| Model Type  | Algorithm             | Accuracy / R² |
|-------------|------------------------|----------------|
| Regression  | Random Forest Regressor| ~0.58 (R²)     |
| Classification | Random Forest Classifier | Good Accuracy (exact % not specified) |

---

## 🛠 Tools & Libraries Used

- Python (Colab)
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

---

## 🙋‍♂️ Author

**Nasir Sharif**  
AI Bootcamp Project Contributor  
[GitHub Profile](https://github.com/Nasir-Sharif)

---

## ✅ Future Work

- Hyperparameter tuning for better accuracy
- Feature engineering
- Real-time data ingestion
- Web app deployment using Flask or Streamlit

---

## 📜 License

This project is for educational purposes and part of a bootcamp assignment. Feel free to fork and experiment.

