# Fuel Economy Project 🚗⛽

## 📌 Project Overview
This project focuses on analyzing vehicle fuel economy data over multiple years and applying Machine Learning techniques to understand trends, predict fuel efficiency, classify eco-friendly vehicles, and segment vehicles into meaningful clusters.

The project demonstrates **end-to-end data science workflow**:
- Data cleaning
- Data visualization
- Regression
- Classification
- Clustering

---

## 🎯 Objectives
- Analyze how vehicle fuel economy has changed over a span of 10 years
- Study trends in eco-friendly (SmartWay) vehicles
- Predict **City MPG** using regression
- Classify vehicles as **SmartWay or Non-SmartWay**
- Segment vehicles using clustering techniques

---

## 📂 Project Structure
│
├── data/
│ └── fuel_economy_datasets.xlsx
│
├── notebooks/
│ └── Fuel_Economy_Analysis.ipynb
│
├── output/
│ ├── visualizations/
│ └── model_results/
│
└── README.md


---

## 📊 Dataset Description
- Vehicle fuel economy data collected over multiple years
- Key features include:
  - City MPG
  - Highway MPG
  - Combined MPG
  - Cylinders
  - Fuel type
  - Vehicle class
  - SmartWay (eco-friendly indicator)

---

## 🛠️ Steps Performed

### 🔹 Step 1: Data Cleaning
- Standardized column names
- Selected common columns across all datasets
- Converted numeric columns to proper data types
- Handled missing values
- Added `year` column for trend analysis

### 🔹 Step 2: Data Visualization
Created multiple visualizations using **Matplotlib**:
- Fuel economy trends over years
- Growth of SmartWay vehicles
- Distribution of City MPG
- Relationship between engine size and fuel efficiency
- Outlier detection using boxplots

### 🔹 Step 3: Regression (Linear Regression)
- **Target**: City MPG
- **Features**: Highway MPG, Combined MPG, Cylinders
- Used pipeline with:
  - StandardScaler
  - Linear Regression
- Evaluated using:
  - RMSE
  - R² score

### 🔹 Step 4: Classification
#### Logistic Regression
- Predicted whether a vehicle is SmartWay or not
- Used pipeline with scaling
- Evaluated using accuracy and confusion matrix

#### Decision Tree
- Compared performance with Logistic Regression
- Interpreted model behavior

### 🔹 Step 5: Clustering
- Applied K-Means clustering
- Identified optimal number of clusters
- Visualized clusters using 2D scatter plots
- Interpreted cluster characteristics

---

## 📈 Key Results
- Fuel efficiency has improved over the years
- Number of SmartWay vehicles increased significantly
- Regression model showed strong predictive power for City MPG
- Logistic Regression provided stable and interpretable classification results
- Clustering revealed meaningful vehicle segments based on performance

---

## 🧠 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

