# 🩺 Early Heart Disease Prediction Using Machine Learning

## 📘 Problem Statement
Heart disease is one of the leading causes of death globally. Early detection can help prevent severe complications and save lives, but traditional diagnostic methods are often time-consuming and expensive.

This project aims to build a **machine learning model** that predicts the **likelihood of heart disease** based on various **medical attributes** such as age, sex, blood pressure, cholesterol level, chest pain type, and other health indicators.

By identifying patterns in patient data, the system can assist healthcare professionals in **early diagnosis** and **risk assessment**, enabling timely preventive care.

---

## 🎯 Objective
- Predict whether a patient is likely to have heart disease.
- Analyze and visualize patterns in medical data.
- Assist in early diagnosis using data-driven insights.

---

## 🧠 Tech Stack
- **Programming Language:** Python  
- **Libraries Used:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Model Used:** Random Forest Classifier  
- **Dataset:** [Heart Disease Dataset (Kaggle)](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)

---

## 🧾 Dataset Description
| Feature | Description |
|----------|-------------|
| **Age** | Age of the patient |
| **Sex** | Male or Female |
| **ChestPainType** | Type of chest pain (TA, ATA, NAP, ASY) |
| **RestingBP** | Resting blood pressure (mm Hg) |
| **Cholesterol** | Serum cholesterol (mg/dl) |
| **FastingBS** | Fasting blood sugar (1 = true, 0 = false) |
| **RestingECG** | Resting electrocardiogram results (Normal, ST, LVH) |
| **MaxHR** | Maximum heart rate achieved |
| **ExerciseAngina** | Exercise-induced angina (Y/N) |
| **Oldpeak** | ST depression induced by exercise |
| **ST_Slope** | Slope of the peak exercise ST segment |
| **HeartDisease** | Target variable (1 = Disease, 0 = No Disease) |

---

## ⚙️ How It Works
1. Import and preprocess the dataset.  
2. Encode categorical variables and scale features.  
3. Split the data into training and testing sets.  
4. Train a **Random Forest Classifier** on the training set.  
5. Evaluate model accuracy, precision, recall, and F1-score.  
6. Visualize results using heatmaps and distribution plots.  
7. Predict heart disease for new patient data.

---

## 📊 Results
- Achieved **high accuracy** in predicting heart disease.  
- Visual insights show strong relationships between features such as age, cholesterol, and chest pain type with heart disease risk.

---

## 🚀 Future Enhancements
- Deploy the model as a **web application** using Flask or Streamlit.  
- Improve prediction accuracy with ensemble methods or deep learning.  
- Integrate real-time patient data for live predictions.

---

## 👩‍💻 Author
**Chowdam Dharani Priya**  
Machine Learning Enthusiast 💙  
📧 chowdamdharanipriya1105@gmail.com 
🔗 linkedin.com/in/chowdamdharanipriya

Scikit-learn (Machine Learning — Random Forest, Logistic Regression, etc.)
