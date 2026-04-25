# 🎓 Student Academic Performance Analysis and Prediction Using Machine Learning

## 📌 Project Overview
This project focuses on analyzing and predicting student academic performance using Data Science and Machine Learning techniques. The objective is to identify key factors affecting performance and build a predictive model based on academic and lifestyle attributes.

Data was collected using Google Forms and analyzed using Python.

---

## 🎯 Problem Statement
Many educational institutions lack a data-driven system to monitor and predict student academic performance. This project aims to analyze student data and build a machine learning model to predict final exam results.

---

## 📊 Data Collection
Data was collected using Google Forms.

🔗 Google Form Link:  
https://forms.gle/VbTgE8rMVxEef9Hg7

### Features Collected:
- Name
- Age
- Gender
- Branch
- Semester
- Study Hours per Day
- Attendance Percentage
- Internal Marks
- Assignment Completion Rate
- Participation in Extra Activities
- Sleep Hours
- Internet Usage
- Coaching Classes
- Final Exam Result (%)

Total Responses Collected: 15  
Final Cleaned Records Used: 9

---

## 🧹 Data Preprocessing
The dataset was cleaned to ensure consistency and accuracy.

Steps Performed:
- Removal of unrealistic age values
- Removal of inconsistent entries
- Handling missing values using mean substitution
- Removal of duplicate records

The cleaned dataset was used for analysis and model training.

---

## 📈 Exploratory Data Analysis (EDA)

EDA was performed to understand relationships between different features and student performance.

### Visualizations Created:
- Study Hours vs Final Result (Scatter Plot)
- Attendance vs Final Result (Scatter Plot)
- Internal Marks vs Final Result
- Correlation Heatmap

Key Findings:
- Study hours positively influence final results.
- Attendance percentage shows strong correlation with performance.
- Internal marks significantly impact final exam scores.

---

## 🤖 Machine Learning Model

### Model Used:
✅ Linear Regression

### Steps Performed:
- Feature selection
- Train-test split (80:20 ratio)
- Model training
- Prediction
- Model evaluation

### Evaluation Metrics:
- Mean Absolute Error (MAE)
- R² Score

The model demonstrated satisfactory predictive performance based on the available dataset.

---

## 🛠 Tools and Technologies Used

- Google Forms (Data Collection)
- Google Sheets (Data Storage)
- Microsoft Excel (Data Cleaning)
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- GitHub

---

## 📂 Project Structure
Student-Performance-Analysis/
│
├── student_raw_data.xlsx
├── student_cleaned_data.xlsx
├── student_performance_model.ipynb
├── screenshots/
│ ├── form.png
│ ├── raw_data.png
│ ├── cleaning.png
│ ├── graphs.png
│ └── model_output.png
└── README.md


---

## 📌 Conclusion

This project demonstrates the practical implementation of the Data Science workflow:
Data Collection → Data Cleaning → Data Analysis → Model Building → Evaluation.

The analysis shows that study hours, attendance, and internal marks are significant predictors of student academic performance.

---

## 👨‍💻 Author
Mini Project for  
**Data Science and Big Data Analytics**  
Academic Year: 2025-26