# 💼 Salary Prediction using Machine Learning

[![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/Scikit--Learn-ML-yellow?logo=scikit-learn)](https://scikit-learn.org/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

## 📌 Overview

This project aims to predict salaries using regression-based machine learning models. It is built for educational purposes under academic mentorship and demonstrates the complete machine learning workflow including data preprocessing, model training, hyperparameter tuning, and evaluation.

---

## 🚀 Highlights

- ✅ Cleaned and encoded a salary dataset containing education, experience, and job role.
- 🧠 Trained models like Linear Regression, Decision Tree, and Random Forest.
- ⚙️ Implemented one-hot encoding and handled categorical features effectively.
- 📊 Evaluated models using MAE, MSE, and RMSE metrics.
- 📈 Visualized predictions and model accuracy.

---

## 🧠 Dataset

The dataset contains the following features:
- `Experience (in years)`
- `Education Level`
- `Job Title`
- `Salary (Target)`

> 📂 Dataset used is small and ideal for introductory regression practice. It may be synthetic or sourced from simplified datasets used in ML bootcamps.

---

## 🛠️ Tech Stack

- **Language**: Python 3.10+
- **Libraries**:
  - Scikit-learn
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
- **Environment**: Jupyter Notebook

---

## 📁 Project Structure
├── salary_prediction.ipynb # Main Jupyter notebook (model development)
├── requirements.txt # Dependencies (for virtual env setup)
└── README.md # Project documentation


---

## 💡 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/AdityaSh-sys/Salary-Pridiction.git
   cd Salary-Pridiction
   
2. Create and activate a virtual environment (optional but recommended):
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

3.Install dependencies:
  pip install -r requirements.txt

---

## 📌 Future Enhancements
Expand dataset with real-world salary data (e.g., Glassdoor, Kaggle)

Implement pipeline and GridSearchCV

Deploy via Streamlit or Flask as a simple web app


