# Diabetes Prediction Using Machine Learning

This project aims to predict whether a patient has diabetes based on diagnostic measurements. 

## 📂 Dataset Overview
The dataset used for this project is sourced from Kaggle: [Diabetes Data Set](https://www.kaggle.com/datasets/mathchi/diabetes-data-set).
The dataset consists of 768 observations with 8 clinical features used to predict diabetes. The target variable (`Outcome`) indicates whether the patient has diabetes (1) or not (0).

### Features:
- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration after 2 hours in an oral glucose tolerance test
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skin fold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m²))
- **DiabetesPedigreeFunction**: A function that scores the likelihood of diabetes based on family history
- **Age**: Age in years
- **Outcome**: Class label (0 = Non-Diabetic, 1 = Diabetic)

---

## ⚙️ Models Used
We implemented and fine-tuned multiple machine learning models for prediction:
1. **K-Nearest Neighbors (KNN)**
2. **Support Vector Machine (SVM)**
3. **Logistic Regression**
4. **Decision Tree**

---

## 📊 Model Comparison ⚖️
A performance comparison was made using **test accuracy** to evaluate how well each model generalizes. The Decision Tree model was excluded from the final comparison due to overfitting.
![image](https://github.com/user-attachments/assets/3f2071af-8019-40a3-9b1e-429710295f4d)



---

## 🔎 Model Prediction
![image](https://github.com/user-attachments/assets/043561ee-6326-4222-9864-09a9eae745c4)


---

## 🖥️ Interactive User Interface (Colab)
A simple **interactive UI** was built using `ipywidgets` in Google Colab, allowing users to input feature values and obtain predictions from the trained models.
![image](https://github.com/user-attachments/assets/5cd9da51-6db4-4b13-9203-48ab0e6db91d)


