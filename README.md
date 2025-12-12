# ❤️ Heart Disease Prediction – Data Science Project

This project focuses on analyzing a heart disease dataset using Python.  
It includes **data cleaning, exploratory data analysis (EDA), visualizations, feature scaling, and a Logistic Regression machine learning model** for prediction.

---

## 📌 Project Workflow

1. Import necessary Python libraries  
2. Load and inspect the dataset  
3. Identify missing values & duplicates  
4. Remove duplicate entries  
5. Perform Exploratory Data Analysis (EDA)
6. Visualize distributions and correlations  
7. Prepare features (X) and target (y)  
8. Split dataset into training and testing sets  
9. Scale numerical features  
10. Train Logistic Regression model  
11. Evaluate model accuracy, precision, recall, and confusion matrix  
12. Extract key insights  
13. Write final conclusion  

---

## 🧹 Data Cleaning Summary

- Dataset had **1 duplicate row**, which was removed  
- No missing values were present  
- All columns had correct data types  
✔ Dataset was ready for analysis

---

## 📊 Exploratory Data Analysis

The project includes:

- Histograms of all numeric features  
- Correlation heatmap  
- Count plots of categorical variables vs target  
- Relationship insights between features and heart disease

---

## 🤖 Machine Learning Model

Model used: **Logistic Regression**

### 🔎 Model Performance:
- **Accuracy:** ~77%  
- Good recall for detecting heart disease cases  
- Balanced precision/recall across both classes  

Confusion matrix & classification report are included in the notebook.

---

## 📝 Key Insights

- **Chest Pain Type (cp)** and **Maximum Heart Rate (thalach)** have strong influence on heart disease.  
- **Oldpeak** shows a negative correlation with the target variable.  
- **Slope, ca, and thal** also show meaningful patterns.  
- Logistic Regression works well as a baseline model.

---

## 🧾 Files in This Repository

- `heart_disease_analysis.ipynb` – Complete Jupyter Notebook  
- `heart.csv` – Dataset  
- `README.md` – Project documentation  

---

## 🚀 Future Improvements

- Try Random Forest, SVM, KNN, XGBoost  
- Add hyperparameter tuning  
- Use cross-validation  
- Deploy model using Streamlit for web interface  

---

## 👤 Author

**Vishal Rajeshbhai Patel**  
📍 Germany  
📧 vishal.rajeshbhai.patel@gmail.com  
GitHub: https://github.com/Vishu-DS

