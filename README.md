🎓 Student Performance Prediction using Machine Learning
----------------------------------------------------------------------------------------------------------------------------------------
📌 Project Overview
This project predicts student exam performance using Machine Learning algorithms based on academic and behavioral factors.
Using Exploratory Data Analysis (EDA) and predictive modeling, the system identifies patterns that influence student outcomes such as:
Study hours
Attendance
Assignment completion
Sleep patterns
Previous academic scores
The goal is to demonstrate how data-driven insights can help understand and predict student performance.

🧠 Machine Learning Models Used
Two regression models were implemented and compared:
1️⃣ Linear Regression
Simple statistical model
Captures linear relationships between variables
2️⃣ Random Forest Regressor
Ensemble machine learning algorithm
Uses multiple decision trees
Provides higher prediction accuracy

📊 Dataset Description
The dataset contains 300 student records with the following attributes:

Feature	Description
Hours_Studied	  Average study hours per day
Attendance	    Attendance percentage
Assignments	    Number of assignments completed
Sleep_Hours	    Average daily sleep hours
Previous_Score	Score in previous exam
Exam_Score	    Final exam score (Target Variable)

⚙️ Project Workflow
The machine learning pipeline consists of the following stages:
1️⃣ Data Collection
Student academic data is stored in a CSV dataset.
2️⃣ Data Preprocessing
Dataset loading
Feature separation
Train-test split
3️⃣ Exploratory Data Analysis (EDA)
Visualizations were created to identify relationships between variables.
Examples include:
Correlation heatmaps
Scatter plots
Feature comparison graphs
4️⃣ Model Training
Two machine learning models were trained:
Linear Regression
Random Forest Regressor
5️⃣ Model Evaluation
Performance metrics used:
Mean Squared Error (MSE)
R² Score
Random Forest achieved better predictive accuracy.
6️⃣ Prediction
The trained model predicts exam scores for new student data.

🛠 Technologies Used
Python, Pandas, NumPy
Matplotlib, Seaborn, Scikit-Learn

👩‍💻 Author
Srihita Kotagiri
