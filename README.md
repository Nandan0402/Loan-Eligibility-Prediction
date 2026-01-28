🏦 Loan Eligibility Prediction using Machine Learning 📊
<p align="center"> <img src="https://img.icons8.com/color/96/artificial-intelligence.png"/> <img src="https://img.icons8.com/color/96/python.png"/> <img src="https://img.icons8.com/color/96/combo-chart--v1.png"/> <img src="https://img.icons8.com/color/96/bank.png"/> </p> <p align="center"> <b>A clean, structured, and beginner-friendly Machine Learning project using Classification Algorithms</b> </p> <p align="center"> <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExbHpxbmdvZ21lcGJ0c2d1M3NnYjJrbTFubHdzMW1mODRzOHZ2eXk0NyZlcD12MV9naWZzX3NlYXJjaCZjdD1n/xT9IgzoKnwFNmISR8I/giphy.gif" width="420"/> </p>
🚀 Project Overview

This project implements a Loan Eligibility Prediction System using core
Machine Learning concepts and multiple classification algorithms.

The goal is to predict whether a loan application will be Approved or Rejected based on applicant details such as income, education, credit history, and property area.

The project demonstrates the complete ML lifecycle:

Data understanding

Data preprocessing

Exploratory Data Analysis (EDA)

Model training

Evaluation & comparison

✅ Suitable for:

🎓 College mini / major projects

💡 Machine Learning beginners

🧠 Classification algorithm practice

💼 GitHub & LinkedIn portfolios

🧠 Problem Statement

Financial institutions receive thousands of loan applications daily.

Manual loan approval:

❌ Is time-consuming

❌ Can be biased

❌ Is error-prone

👉 Machine Learning helps automate and improve loan approval decisions by learning patterns from historical data.

📂 Dataset Information

The dataset used is loan_data_set.csv.

📄 Column Description

Column	Description

🆔 Loan_ID	Unique loan identifier

🚻 Gender	Applicant gender

💍 Married	Marital status

👨‍👩‍👧 Dependents	Number of dependents

🎓 Education	Graduate / Not Graduate

🧑‍💼 Self_Employed	Employment status

💰 ApplicantIncome	Applicant income

💵 CoapplicantIncome	Co-applicant income

🏦 LoanAmount	Loan amount

⏳ Loan_Amount_Term	Loan term (months)

📊 Credit_History	Credit history record

🌍 Property_Area	Urban / Semiurban / Rural

✅ Loan_Status	Approved (Y) / Rejected (N)

🛠️ Technologies Used
<p> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/> <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/> <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/> <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge"/> <img src="https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge"/> </p>
🧠 Methodology

📥 Load dataset using Pandas

🧹 Handle missing values (mean / mode)

🔄 Encode categorical features (One-Hot Encoding)

📊 Perform Exploratory Data Analysis (EDA)

⚖ Handle class imbalance using SMOTE

📐 Apply feature scaling (MinMaxScaler)

🤖 Train multiple ML models

📊 Evaluate and compare model performance

🤖 Machine Learning Models Used

Logistic Regression

K-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

Decision Tree

Random Forest

Gradient Boosting

▶️ How to Run the Project
1️⃣ Clone the repository
git clone https://github.com/Nandan0402/Loan-Eligibility-Prediction.git

2️⃣ Navigate to the project directory
cd Loan-Eligibility-Prediction

3️⃣ Install required libraries
pip install pandas numpy scikit-learn matplotlib seaborn imbalanced-learn

4️⃣ Run the project
python loan_prediction.py


(or open and run the Jupyter Notebook)

📈 Model Evaluation

Models are evaluated using:

📊 Accuracy Score

📉 Confusion Matrix

📋 Classification Report

The best-performing model is selected based on accuracy comparison.

🎯 Learning Outcomes

✔ Understanding real-world data preprocessing
✔ Handling missing & imbalanced data
✔ Applying multiple classification algorithms
✔ Model evaluation & comparison
✔ End-to-end ML project experience

📌 Use Cases

🎓 Academic mini / major project

💼 Entry-level Machine Learning portfolio

🧠 Classification concept practice

🏦 FinTech & Banking use-case simulation

👤 Author
<p align="center"> <img src="https://avatars.githubusercontent.com/Nandan0402" width="120" style="border-radius: 50%;" /> </p> <p align="center"> <b>Nandan B</b><br> BCA Student | Machine Learning Enthusiast </p> <p align="center"> 🌐 <a href="https://github.com/Nandan0402">GitHub</a> | 💼 <a href="https://www.linkedin.com/in/nandan-b-2a9b1b334/">LinkedIn</a> </p>
⭐ Conclusion

This project focuses on strong Machine Learning fundamentals and mirrors real-world loan approval systems, making it ideal for students and beginners.

⭐ If you find this project useful, please star the repository.

📁 Project Structure

Loan-Eligibility-Prediction/

│
├── loan_data_set.csv        # Dataset

├── loan_prediction.ipynb    # ML implementation

├── README.md                # Documentation

└── requirements.txt         # Dependencies (optional)
