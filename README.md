# 🎓 Student Performance Analysis & Prediction

## 📌 About the Project
This project focuses on analyzing student data and predicting their final exam scores using Machine Learning.

The main goal was to understand what factors affect student performance and then build a model that can predict final scores based on those factors.

---

## ⚙️ What I Did in This Project

I followed a complete Data Science workflow step by step:

### 1. Data Loading & Understanding
- Explored dataset structure, columns, and data types  
- Checked missing values and basic statistics  
- Identified data quality issues  

### 2. Data Cleaning
- Fixed inconsistent text values (Gender, Department, etc.)  
- Handled missing values using median  
- Removed unrealistic values (like invalid scores/attendance)  
- Converted incorrect data types  
- Removed duplicate records  

### 3. Data Analysis & Visualization
- Analyzed how student scores are distributed  
- Explored relationships between:
  - Attendance and Final Score  
  - Study Hours and Final Score  
  - Midterm and Final Score  
- Created visualizations to clearly understand trends  

👉 Key finding:  
Students with higher attendance, more study hours, and better midterm scores tend to perform better.

---

### 4. Feature Engineering
- Created a new feature: **Total Academic Score**  
- Categorized attendance into levels (Low, Medium, High)  
- Applied:
  - One-Hot Encoding (for categorical data)  
  - Ordinal Encoding (for ordered data)  
  - Standard Scaling (for numerical features)  

- Built a complete **sklearn pipeline** to handle all steps properly  

---

### 5. Model Building & Evaluation
- Used **Linear Regression** model  
- Split data into training and testing sets  
- Evaluated model using:
  - MAE  
  - RMSE  
  - R² Score  

---

## 📈 Model Performance

The model achieved:

**R² Score: 0.59**

This means the model explains around **59% (~60%) of the variation** in student final scores.

👉 This is a **moderate performance**, meaning:
- The model is working reasonably well  
- But there is still room for improvement  

---

## 🔍 Key Insights

- Attendance has a strong impact on performance  
- Study hours are directly related to better scores  
- Midterm performance is a strong indicator of final results  
- Different departments show variation in performance  

---

## 🚀 What Can Be Improved

To make the model better in future:

- Use advanced models like:
  - Random Forest  
  - Decision Tree  

- Perform hyperparameter tuning  
- Add more useful features such as:
  - Student behavior  
  - Background information  
  - Learning environment  

---

## 📁 Project File

- `Sana_Malik(_Final_Project_).ipynb` → Complete project notebook  

---

## 🧠 Final Thought

This project helped me understand how real-world data is handled from start to finish — from cleaning messy data to building a prediction model.

It also showed that while models can make good predictions, having better data and features is just as important.

---
