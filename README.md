# ❤️ Heart Failure Prediction

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg) ![License](https://img.shields.io/badge/License-MIT-green.svg) ![Status](https://img.shields.io/badge/Status-Active-brightgreen)

Predicting the risk of heart failure using Machine Learning!  
This project builds a classifier to determine whether a patient is at risk based on clinical attributes.

---

## 📋 Table of Contents
- [📖 Project Overview](#-project-overview)
- [🗂️ Dataset](#️-dataset)
- [🛠️ Features Covered](#️-features-covered)
- [🚀 How to Run](#-how-to-run)
- [📈 Future Improvements](#-future-improvements)

---

## 📖 Project Overview

The **Heart_Failure_Prediction.ipynb** notebook covers the complete Machine Learning workflow:

- Loading and cleaning the dataset
- Exploratory Data Analysis (EDA) to understand data patterns
- Feature engineering and scaling
- Building a classification model using **Logistic Regression**
- Evaluating model performance using accuracy, confusion matrix, and classification report

The objective is to help predict heart failure at an early stage for preventive healthcare.

---

## 🗂️ Dataset

- **File:** `heart.csv`
- **Records:** Patient clinical information
- **Target variable:** `target` (1 → presence of heart disease, 0 → absence)

### 🩺 Key Features:
| Feature | Description |
| :--- | :--- |
| `age` | Age of the patient |
| `sex` | Gender (1 = male; 0 = female) |
| `cp` | Chest pain type |
| `trestbps` | Resting blood pressure |
| `chol` | Serum cholesterol in mg/dl |
| `fbs` | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false) |
| `restecg` | Resting electrocardiographic results |
| `thalach` | Maximum heart rate achieved |
| `exang` | Exercise-induced angina |
| `oldpeak` | ST depression induced by exercise |
| `slope` | Slope of the peak exercise ST segment |
| `ca` | Number of major vessels colored by fluoroscopy |
| `thal` | Thalassemia (3 = normal; 6 = fixed defect; 7 = reversible defect) |

---

## 🛠️ Features Covered

- ✅ Data Preprocessing & Cleaning
- ✅ Exploratory Data Analysis (EDA) using Matplotlib and Seaborn
- ✅ Feature Scaling (StandardScaler)
- ✅ Model Training (Logistic Regression)
- ✅ Evaluation Metrics (Accuracy, Confusion Matrix, Classification Report)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/heart-failure-prediction.git
   cd heart-failure-prediction
   ```

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook Heart_Failure_Prediction.ipynb
   ```

---

## 📈 Future Improvements

- 🔥 Add more models (Random Forest, XGBoost, Neural Networks)
- 🛠️ Perform hyperparameter tuning
- 🌐 Deploy as a simple web application (e.g., using Streamlit or Flask)
- 🧪 Add Cross-Validation and ROC-AUC curve analysis

---

## 🤝 Let's Connect!
If you like this project or want to collaborate, feel free to connect!

