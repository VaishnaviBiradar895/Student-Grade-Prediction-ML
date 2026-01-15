Student Grade Prediction using Machine Learning

📌 Overview
This project predicts a student’s final grade using Machine Learning regression based on academic and demographic features.
The model outputs a numeric grade (0–100) and converts it into letter grades (A–F) for easy interpretation.

🎯 Objective
-Predict student performance using historical data
-Analyze factors affecting grades
-Convert numeric predictions into letter grades

📂 Dataset
-File: student_performance_regression.csv
-Target variable: final_grade
-Features include study hours, attendance, previous scores, assignments, and demographic details

⚙️ Technologies Used
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn

🧠 ML Approach
-Algorithm: Linear Regression
-Preprocessing: StandardScaler + OneHotEncoder
-Pipeline: ColumnTransformer + Regression model

🆕 New Student Prediction
The model predicts grades for new students and converts them into:
A (90–100)
B (80–89)
C (70–79)
D (60–69)
F (<60)

📁 Project Structure
Student-Grade-Prediction-ML/
├── Project_ML.ipynb
├── student_performance_regression.csv
├── README.md

🚀 How to Run
1. Open Project_ML.ipynb in Jupyter/Colab
2. Run cells sequentially
3. Modify new student values to test predictions

👩‍💻 Author
Vaishnavi Biradar
