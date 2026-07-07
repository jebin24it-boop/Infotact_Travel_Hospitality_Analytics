# 🏨 Hotel Reservation Cancellation Prediction using Machine Learning

## 📌 Project Overview

This project was developed as part of the **Infotact Solutions Data Analytics Internship (Project 2)**.

The objective of this project is to analyze hotel reservation data and build machine learning models capable of predicting whether a booking is likely to be cancelled. Early prediction of cancellations helps hotels improve revenue management, optimize room allocation, and enhance customer retention strategies.

---

# 🎯 Objectives

- Analyze hotel reservation booking patterns.
- Perform data preprocessing and feature engineering.
- Build predictive machine learning models.
- Compare multiple classification algorithms.
- Identify important factors influencing booking cancellations.
- Generate business recommendations based on model insights.

---

# 📂 Dataset Information

**Dataset Name**

Hotel Reservation Dataset

**Source**

Provided by Infotact Solutions for internship project.

**Dataset Size**

- Rows: 35,555
- Columns: 25

**Target Variable**

booking_status

- 0 → Cancelled
- 1 → Not Cancelled

---

# 📁 Project Structure

```
Infotact_Travel_Hospitality_Analytics/

│
├── data/
│   ├── raw/
│   ├── cleaned/
│   └── hotel_reservations_ml_ready.csv
│
├── notebooks/
│   └── ml_preprocessing.ipynb
│
├── dashboard/
│
├── reports/
│   ├── ml_findings.md
│   ├── business_recommendations.md
│   ├── model_summary.md
│   └── final_report.md
│
├── docs/
│
├── README.md
```

---

# 👥 Team Members

| Member | Responsibility |
|---------|---------------|
| **Jebin Joy** | Machine Learning & Predictive Analytics |
| **Saurav Gopinath** | Data Cleaning & Preprocessing |
| **Rivya Roy** | Exploratory Data Analysis & Dashboard Development |

---

# ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Power BI
- Git
- GitHub

---

# 🔄 Project Workflow

## Week 1

- Machine Learning Planning
- Feature Selection
- Workflow Preparation
- Research on Classification Models

---

## Week 2

- Dataset Validation
- Feature Selection
- Removal of Redundant Columns
- Encoding Categorical Variables
- Feature Matrix Preparation
- Train-Test Split

---

## Week 3

Machine Learning Models

- Logistic Regression
- Decision Tree Classifier

Model Evaluation

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC Score

Model Comparison

Feature Importance Analysis

Selection of Best Performing Model

---

## Week 4

- Machine Learning Findings
- Business Recommendations
- Final Documentation
- README Update
- Final Project Report

---

# 📊 Machine Learning Pipeline

```
Cleaned Dataset

↓

Feature Selection

↓

Data Encoding

↓

Train-Test Split

↓

Logistic Regression

↓

Decision Tree

↓

Model Evaluation

↓

Model Comparison

↓

Business Recommendations
```

---

# 📈 Evaluation Metrics

The following metrics were used to evaluate model performance:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC Score

---

# 🔍 Key Features Used

- Number of Adults
- Number of Children
- Weekend Nights
- Week Nights
- Meal Plan
- Room Type Reserved
- Lead Time
- Market Segment
- Repeated Guest
- Previous Cancellations
- Previous Successful Bookings
- Average Price Per Room
- Special Requests
- Total Guests
- Total Nights
- Booking Segment

---

# 📌 Business Insights

The project identifies booking characteristics that influence cancellation behaviour.

Key insights include:

- Longer lead time bookings tend to have higher cancellation probability.
- Repeat guests generally exhibit lower cancellation rates.
- Market segment influences booking behaviour.
- Room pricing impacts cancellation likelihood.
- Customer booking patterns help improve operational planning.

---

# 💡 Business Recommendations

- Monitor long lead-time reservations.
- Offer loyalty benefits to repeat guests.
- Develop pricing strategies based on demand.
- Focus retention efforts on high-risk customer groups.
- Use predictive models to identify cancellation risk before arrival.

---

# 🚀 Future Enhancements

- Random Forest Classifier
- XGBoost
- Hyperparameter Tuning
- Cross Validation
- Deployment using Flask or Streamlit
- Real-time Booking Cancellation Prediction

---

# 📌 Project Outcome

Successfully developed a machine learning pipeline capable of predicting hotel booking cancellations and identifying important factors affecting customer cancellation behaviour.

The project demonstrates how predictive analytics can support business decision-making within the hospitality industry.

---

# 📜 License

This project was developed for educational and internship purposes under **Infotact Solutions**.

---

# 🙏 Acknowledgement

We sincerely thank **Infotact Solutions** for providing the opportunity, guidance, and dataset to complete this project successfully.
