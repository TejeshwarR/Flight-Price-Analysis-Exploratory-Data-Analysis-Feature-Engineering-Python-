# Flight Price Analysis – Exploratory Data Analysis & Feature Engineering (Python)

---

## 📌 Project Overview
This project focuses on **Flight Price Analysis** using **Python**, with an emphasis on **Exploratory Data Analysis (EDA)** and **Feature Engineering (FE)**. The objective is to understand the key factors influencing airline ticket prices and prepare a clean, model-ready dataset for predictive modeling.

The analysis combines raw flight booking data with structured transformations to uncover pricing patterns across airlines, routes, stops, duration, and travel time.

---

## 🎯 Goal of the Project
The goals of this project are to:
- Analyze flight ticket price behavior across multiple attributes
- Identify factors that significantly influence flight prices
- Perform EDA to uncover trends and anomalies in pricing
- Apply feature engineering to convert raw data into model-ready features
- Prepare a clean dataset suitable for machine learning models

---

## 📂 Project Files
- Flight_price_analysis.ipynb – Python notebook containing EDA and feature engineering
- flight_price.xlsx – Raw flight pricing dataset

---

## 🧾 Dataset Overview
The dataset contains flight booking information with the following attributes:
- Airline
- Source and Destination
- Route
- Date of Journey
- Departure Time and Arrival Time
- Duration
- Total Stops
- Additional Information
- Ticket Price (Target Variable)

This dataset reflects real-world airline booking data with mixed data types and unstructured fields.

---

## 🔄 Procedure / Methodology
The project was executed using the following steps:

### 1. Data Understanding & Cleaning
Reviewed dataset structure, handled missing values, corrected data types, and removed redundant or inconsistent columns.

### 2. Exploratory Data Analysis (EDA)
Analyzed price distributions and relationships across airlines, number of stops, duration, and journey dates using statistical summaries and visual exploration.

### 3. Feature Engineering
Extracted and transformed features such as:
- Day and month from journey date
- Hour and minute from departure and arrival time
- Total duration converted into minutes
- Encoding of categorical variables

### 4. Data Preparation
Ensured all features were numeric and structured for downstream machine learning workflows.

---

## 📊 Key Analysis Highlights
- Flights with multiple stops generally have higher ticket prices
- Certain airlines consistently price higher than others
- Duration and number of stops are strong predictors of ticket price
- Travel time and journey date influence pricing trends
- Feature engineering significantly improves data usability

---

## ⭐ Project Highlights
- End-to-end EDA using Python
- Real-world data cleaning and preprocessing
- Feature engineering on datetime and categorical variables
- Machine-learning–ready dataset preparation
- Strong foundation for regression-based price prediction models
- Interview-ready analytical workflow

---

## 💡 Key Business Insights
- Non-stop flights tend to be priced differently compared to multi-stop routes
- Premium airlines maintain higher pricing consistency
- Longer flight durations generally correlate with higher prices
- Seasonal and time-based travel patterns impact ticket cost

---

## 🚀 Next Steps
- Build regression models to predict flight prices
- Perform feature importance analysis
- Apply hyperparameter tuning for model optimization
- Evaluate models using RMSE and R²
- Deploy a simple prediction interface or dashboard

---

## 👤 Author
**Tejeshwar R**  
Data Analyst | Python | SQL | Power BI | Excel  |  Statistics
