# 🫀 Heart Disease Prediction

This project is a Machine Learning-based predictive model that analyzes patient data to determine the likelihood of heart disease. It includes data preprocessing, visualization, model building, and evaluation techniques.

## 📁 Dataset

The dataset used is [Heart Disease UCI dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction), which includes the following key features:
- Age, RestingBP, Cholesterol, MaxHR
- Sex, ChestPainType, FastingBS, RestingECG
- ExerciseAngina, Oldpeak, ST_Slope
- HeartDisease (Target variable)

## 🧪 Technologies Used

- Python
- Pandas & NumPy
- Matplotlib & Seaborn (for EDA)
- Scikit-learn (for model building)

## 📊 Exploratory Data Analysis

- Handled missing values and duplicates
- Filled zero values in cholesterol using mean imputation
- Plotted distributions of numerical features
- Visualized correlation heatmaps and bar plots of target distribution

## 🤖 Machine Learning Models

Multiple classification algorithms were trained and evaluated, including:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine
- K-Nearest Neighbors

### 📈 Evaluation Metrics

- Accuracy
- F1-Score
- Confusion Matrix

## 🛠️ Installation

To run this project:

```bash
git clone https://github.com/yourusername/heart-disease-prediction.git
cd heart-disease-prediction
pip install -r requirements.txt


📌 Project Status
✅ Completed: EDA, model training, and evaluation
🛠️ Future Work: Hyperparameter tuning, web deployment using Streamlit

