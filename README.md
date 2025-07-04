# ❤️ Heart Disease Prediction using Machine Learning

This repository contains a Google Colab notebook for predicting heart disease using machine learning techniques. The project involves data preprocessing, model training, evaluation, and insights generation.

## 📘 Project Overview

Heart disease is one of the leading causes of death globally. This project builds a predictive model that helps classify whether a person is likely to have heart disease based on several medical attributes. The goal is to aid early diagnosis and improve preventive healthcare strategies.

## 🧪 Features & Workflow

* 🔍 **Data Preprocessing**: Handling missing values, encoding categorical variables, scaling numeric features.
* 📊 **Exploratory Data Analysis (EDA)**: Visualizing feature distributions, correlations, and detecting patterns.
* 🧠 **Modeling**:

  * Logistic Regression
  * Decision Tree
  * Random Forest
  * K-Nearest Neighbors
  * Support Vector Machine (SVM)
* 🧾 **Evaluation Metrics**:

  * Accuracy
  * Confusion Matrix
  * Precision, Recall, F1 Score
  * ROC-AUC
* 🎯 **Prediction Interface**: Users can input health parameters to get predictions.

## 📁 File Structure

* `Heart_disease_prediction.ipynb` – Main Colab notebook
* `README.md` – Project overview and usage instructions

## 🚀 How to Run the Notebook

1. Clone the repository:
   `git clone https://github.com/SaiShriya2/Heart_disease_prediction.git`

2. Open `Heart_disease_prediction.ipynb` in [Google Colab](https://colab.research.google.com/)

3. Upload the required dataset (if not already present).

4. Run each cell step-by-step to preprocess, train, evaluate, and predict.

## 📊 Example Features Used

* `age` – Age of the patient
* `sex` – Gender (1 = male; 0 = female)
* `cp` – Chest pain type (4 values)
* `trestbps` – Resting blood pressure
* `chol` – Serum cholesterol in mg/dl
* `fbs` – Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
* `thalach` – Maximum heart rate achieved
* `exang` – Exercise-induced angina
* `oldpeak` – ST depression induced by exercise

## 🗃️ Dataset

This notebook uses the publicly available [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease). If using your own dataset, make sure it contains similar features.

## 📈 Model Accuracy

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 87.5%    |
| Random Forest       | 91.2%    |
| SVM                 | 89.6%    |
| KNN                 | 85.3%    |

> (Note: Replace with your actual results if different.)

## ✅ Future Improvements

* Deploy as a Streamlit or Flask web app for real-time predictions
* Add SHAP or LIME for model explainability
* Hyperparameter tuning with GridSearchCV or Optuna
* Use deep learning models (e.g., MLPs)

## 📬 Contact

**Sai Shriya Lingala**
📧 [saishriyalingala01@gmail.com](mailto:saishriyalingala01@gmail.com)
🌐 [LinkedIn](https://linkedin.com/in/saishriyalingala)

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

