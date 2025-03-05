Employee Turnover Prediction & Retention Strategy

📌 Project Overview
This project focuses on predicting employee turnover using machine learning models and developing targeted retention strategies. By analyzing historical employee data, the goal is to identify employees at risk of leaving and recommend strategies to improve employee retention.

📊 Dataset Description
The dataset contains various features related to employee performance, job satisfaction, and company policies. Key features include:

Satisfaction Level
Last Evaluation Score
Number of Projects
Average Monthly Hours
Time Spent at the Company
Salary Level (Low, Medium, High)
Department
Promotion in Last 5 Years
Work Accident History
Target Variable: left (1 = Employee Left, 0 = Employee Stayed)
⚙️ Machine Learning Models Used
We implemented multiple models and compared their performance:

Logistic Regression
Random Forest Classifier
Gradient Boosting Classifier
📌 Model Evaluation Metrics
The models were evaluated using:

Classification Report (Precision, Recall, F1-Score)
Confusion Matrix
ROC-AUC Score & Curve
🛠️ Implementation Steps
1️⃣ Data Preprocessing
Handling missing values and outliers
Encoding categorical variables using One-Hot Encoding
Feature scaling using StandardScaler
Handling class imbalance using SMOTE (Synthetic Minority Over-sampling Technique)
2️⃣ Model Training & Cross-Validation
Applied 5-fold Cross-Validation to ensure model generalization
Used cross_val_predict to validate predictions
3️⃣ Employee Turnover Risk Categorization
We classified employees into risk categories based on their turnover probability:

Risk Zone	Probability Score (%)	Action Required
🟢 Safe Zone	< 20%	Minimal risk, maintain engagement
🟡 Low-Risk Zone	20% - 60%	Monitor workload & satisfaction
🟠 Medium-Risk Zone	60% - 90%	Personalized training & career growth programs
🔴 High-Risk Zone	> 90%	Immediate intervention, salary revision, mentorship
📌 Key Findings & Business Insights
✔️ Employees with low satisfaction levels and high workloads are more likely to leave.
✔️ Employees in the low salary bracket have higher turnover rates.
✔️ Promotion frequency & career growth significantly impact employee retention.
✔️ Departments with higher attrition rates need targeted retention policies.

🚀 How to Run the Project
1️⃣ Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
2️⃣ Run the Python Script
bash
Copy
Edit
python employee_turnover.py
📌 Future Enhancements
✅ Deploy the model using Flask/Django for real-time predictions
✅ Integrate with HR Management Systems for automated retention strategies
✅ Apply Deep Learning (Neural Networks) for improved accuracy

👨‍💻 Contributors
Anoop Raveendran
📧 anoop15raveendran@gmail.com
🔗 [https://www.linkedin.com/in/anoop-r-45989411/)]
