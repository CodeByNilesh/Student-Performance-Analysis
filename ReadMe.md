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
<img width="1905" height="914" alt="Response Dashboard" src="https://github.com/user-attachments/assets/4ecdf16c-8d08-438c-b4d4-8ab636a95fa9" /><br>
<img width="1890" height="855" alt="Response Sheet" src="https://github.com/user-attachments/assets/a0fc4431-497e-4786-861d-633bf977e2f9" /><br>
<img width="1895" height="856" alt="Student Raw Data" src="https://github.com/user-attachments/assets/c0c59c0f-0822-4956-94ba-368880583eec" /><br>


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
<img width="1892" height="869" alt="Student Cleaned Data" src="https://github.com/user-attachments/assets/ce254fdb-9d70-4049-a00a-673334b2dbff" /><br>

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
<img width="1017" height="631" alt="Graph1" src="https://github.com/user-attachments/assets/f5f1efeb-1cf0-45cd-8e93-bdf091d69f47" /><br>
<img width="1040" height="637" alt="Graph2" src="https://github.com/user-attachments/assets/9095bf35-6653-475a-9609-74383e80cc96" /><br>
<img width="1040" height="637" alt="Graph2" src="https://github.com/user-attachments/assets/d2546d08-75d8-42de-961b-13407fefc4be" /><br>

---

## 🤖 Machine Learning Model

### Model Used:
✅ Linear Regression
<img width="1081" height="709" alt="Model Building" src="https://github.com/user-attachments/assets/932be92d-9e5a-455c-bde8-2c485d3b8656" /><br>

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

## 📌 Conclusion

This project demonstrates the practical implementation of the Data Science workflow:
Data Collection → Data Cleaning → Data Analysis → Model Building → Evaluation.

The analysis shows that study hours, attendance, and internal marks are significant predictors of student academic performance.

---

## 👨‍💻 Author
Mini Project for  
**Data Science and Big Data Analytics**  
Academic Year: 2025-26
