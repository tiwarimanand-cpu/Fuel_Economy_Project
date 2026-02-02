
---

Fuel Economy Project 🚗⛽


Fuel efficiency is a critical factor in vehicle design, cost optimization, and environmental sustainability.
However, discussions around fuel economy are often assumption-driven rather than data-driven.
This project aims to answer:

How has vehicle fuel efficiency evolved over time?
Which vehicle characteristics most influence City MPG?
Can machine learning models effectively predict and classify eco-friendly vehicles?

The goal is to convert raw, multi-year fuel economy data into actionable insights using structured data science and machine learning workflows.

📌 Project Overview

This project analyzes multi-year vehicle fuel economy data and applies Machine Learning techniques to identify trends, predict fuel efficiency, and classify eco-friendly vehicles.

The goal was not just visualization, but to follow a complete, real-world data science workflow — from raw data to interpretable ML results.

This project demonstrates:

Data cleaning & integration

Exploratory data analysis

Machine Learning–ready preprocessing

Regression & Classification modeling



---

💡 Why This Project?

Fuel efficiency directly impacts cost, sustainability, and regulatory decisions in the automotive domain.
Rather than relying on assumptions, I wanted to analyze real datasets across multiple years and evaluate how vehicle characteristics influence fuel economy using data and machine learning.


---

🎯 Objectives

Analyze how vehicle fuel economy has evolved over a span of 10 years

Study trends in eco-friendly (SmartWay) vehicles

Predict City MPG using regression models

Classify vehicles as SmartWay or Non-SmartWay

Compare model behavior and interpretability



---

📂 Project Structure

├── data/
│   └── fuel_economy_datasets.xlsx
│
├── notebooks/
│   └── Fuel_Economy_Analysis.ipynb
│
├── output/
│   ├── visualizations/
│   └── model_results/
│
└── README.md


---

📊 Dataset Description

Vehicle fuel economy data collected over multiple years

Key features include:

City MPG

Highway MPG

Combined MPG

Cylinders

Fuel type

Vehicle class

SmartWay (eco-friendly indicator)




---

🛠️ Steps Performed (Revised & Structured)

🔹 Step 1: Load & Clean Individual Datasets

Loaded fuel economy datasets from different years

Standardized column names across datasets

Selected common and relevant features

Converted numerical columns to correct data types

Handled missing and inconsistent values


Goal: Ensure each yearly dataset is clean and consistent before integration.


---

🔹 Step 2: Merge & Create Final Cleaned Dataset

Merged all cleaned yearly datasets into a single dataset

Added a year column to support trend analysis

Performed final validation checks after merging


Goal: Build a unified, reliable dataset spanning multiple years.


---

🔹 Step 3: Machine Learning–Ready Preprocessing

Selected features relevant for modeling

Encoded categorical variables where required

Scaled numerical features using StandardScaler

Split data into training and testing sets


Goal: Prepare normalized and structured data suitable for ML models.


---

🔹 Step 4: Linear Regression (Prediction)

Target Variable: City MPG

Features Used: Highway MPG, Combined MPG, Cylinders

Built a pipeline consisting of:

StandardScaler

Linear Regression


Evaluated performance using:

RMSE

R² Score



Insight: Mileage-related features strongly influence urban fuel efficiency.


---

🔹 Step 5: Logistic Regression (Classification)

Objective: Classify vehicles as SmartWay or Non-SmartWay

Implemented Logistic Regression with feature scaling

Evaluated using:

Accuracy score

Confusion matrix



Insight: Logistic Regression provided stable and interpretable classification results.


---

🔹 Step 6: Decision Tree Classification

Implemented Decision Tree to compare with Logistic Regression

Analyzed decision rules and feature importance

Compared model performance and interpretability


Insight: Highlighted trade-offs between model simplicity and complex decision boundaries.


---

📈 Key Results

Overall fuel efficiency has improved over the years

Number of SmartWay vehicles increased significantly

Linear Regression demonstrated strong predictive ability for City MPG

Logistic Regression performed well for eco-friendly vehicle classification

Decision Tree analysis improved understanding of feature influence



---

📚 Key Learnings

Real-world datasets require extensive cleaning before modeling

Simple models can be highly effective when features are meaningful

Model interpretability is crucial alongside performance

Comparing multiple models improves understanding of the problem domain



---

🧠 Technologies Used

Python

Pandas

NumPy

Matplotlib

Scikit-learn

Jupyter Notebook


🚀 Conclusion
This project demonstrates how raw, inconsistent real-world data can be transformed into interpretable machine learning models through systematic preprocessing and analysis.
By combining regression and classification techniques, the project highlights the importance of:
Data quality before modeling
Model interpretability alongside performance
Comparing multiple approaches to understand trade-offs
Overall, this project strengthened my understanding of end-to-end applied machine learning, from data ingestion to insight generation.

📌 Why this matters:
Ending strong = interviewer ke dimaag me clarity + maturity.
