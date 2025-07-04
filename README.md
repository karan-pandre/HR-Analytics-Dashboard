📊 HR Analytics Dashboard – Attrition & Performance
🔍 Overview

This project explores employee attrition using the IBM HR Analytics dataset. The goal is to identify key factors behind employee turnover and build an interactive dashboard for HR decision-makers. A machine learning model is also built using Python to predict attrition likelihood.

🚀 Features

Interactive Power BI dashboard to analyze attrition trends by age, department, overtime, job role, etc.

Built logistic regression and decision tree models in Python to predict attrition probability.

Published dashboard online for real-time access and presentation.

📷 Dashboard Preview

🔗 Live Demo
👉 View Live HR Analytics Dashboard (https://app.powerbi.com/view?r=eyJrIjoiZTg5MDA1ZWYtZTNhMi00OWRmLWJmYzktOTY2ODEwZjY3NDg3IiwidCI6IjZiYWI3NzY1LWMzODctNGQwZC05YmU3LTdmNTY3OTI1MTU5NCIsImMiOjEwfQ%3D%3D)

🛠️ Tools & Technologies
Power BI – Data visualization and dashboard 

Python – Data preprocessing, model building

pandas, seaborn, scikit-learn – Data analysis, visualization, ML

Jupyter Notebook – Interactive model development

IBM HR Analytics Dataset – Public dataset for HR attrition analysis

🧪 Machine Learning Model

A logistic regression model and decision tree classifier were trained to predict the Attrition variable using features like:

Age

Monthly Income

Job Satisfaction

Overtime

Years at Company

Distance from Home


from sklearn.linear_model import LogisticRegression
from sklearn.tree import DecisionTreeClassifier

# Train/Test Split
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2)

# Logistic Regression
lr = LogisticRegression()
lr.fit(X_train, y_train)

# Decision Tree
dt = DecisionTreeClassifier()
dt.fit(X_train, y_train)

📁 Folder Structure
kotlin
Copy
Edit
HR-Analytics-Dashboard/
├── data/
├── notebook/
├── dashboard/
├── screenshots/
└── README.md

📄 Dataset Source
📂 IBM HR Analytics Dataset on Kaggle

👤 Author
Karan Umaji Pandre
🎓 Information Technology Student (2021–2025), Alliance University
✉️ karanpandre3@gmail.com
🌐 Bangalore, India

