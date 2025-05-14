# 📊 Student Performance Analysis & Prediction

This project analyzes student performance data and predicts final exam outcomes (Pass/Fail) based on various features like study hours, attendance rate, parental education level, internet access, and more.

---

## 🔍 Project Overview

**Objective:**  
To build an end-to-end machine learning pipeline that:
- Performs **Exploratory Data Analysis (EDA)** on student academic data.
- Applies **feature engineering** to process categorical variables.
- Trains a **classification model** to predict whether a student will pass or fail the final exam.

---

## 📁 Dataset Features

| Feature | Description |
|--------|-------------|
| Student_ID | Unique ID for each student |
| Gender | Male or Female |
| Study_Hours_per_Week | Average hours studied per week |
| Attendance_Rate | Attendance percentage |
| Past_Exam_Scores | Average score from previous exams |
| Parental_Education_Level | Highest education level of parents |
| Internet_Access_at_Home | Whether the student has internet access at home |
| Extracurricular_Activities | Participation in extracurricular activities |
| Final_Exam_Score | Score in the final exam |
| Pass_Fail | Target variable – whether the student passed or failed |

---

## 🛠️ Technologies Used

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **scikit-learn** (Label Encoding, Train/Test Split, Random Forest, Evaluation Metrics)
- **Jupyter Notebook**

---

## 📊 Exploratory Data Analysis (EDA)

- Plotted Pass/Fail distribution
- Analyzed correlation between features
- Explored the relationship between study hours, attendance, and performance
- Visualized feature importance using Random Forest

---

## 🧠 Model Training

- Used **Random Forest Classifier** for prediction
- Encoded categorical variables using **Label Encoding**
- Split data into **training and test sets (80/20)**
- Evaluated model using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-Score)

---

## ✅ Results

- Achieved **~XX% accuracy** in predicting whether a student will pass/fail.
- Key features impacting performance:
  - Study Hours
  - Attendance Rate
  - Past Exam Scores
  - Internet Access & Parental Education Level

---

## 📌 Future Improvements

- Include more data points like psychological health, sleep patterns, and school environment.
- Try other models: Logistic Regression, XGBoost, Neural Networks.
- Deploy a web app using **Streamlit** or **Flask** for interactive predictions.

---

## 📂 How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/student-performance-predictor.git

# Navigate into the project folder
cd student-performance-predictor

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter Notebook
jupyter notebook Student_Performance_Analysis.ipynb
