# 🏨 Hotel Reservation Cancellation Prediction using Data Analytics & Machine Learning

## 📌 Project Overview

This project was developed as part of the **Infotact Solutions Data Analytics Internship – Project 2**.

The objective of this project is to analyze hotel reservation data, understand booking patterns, identify the factors influencing booking cancellations, visualize business insights through interactive dashboards, and develop machine learning models capable of predicting whether a hotel reservation is likely to be cancelled.

The project combines **Data Cleaning, Exploratory Data Analysis (EDA), Dashboard Development, and Machine Learning** to provide valuable business insights for the hospitality industry.

---

# 🎯 Project Objectives

- Analyze hotel reservation booking data.
- Clean and preprocess raw data.
- Perform Exploratory Data Analysis (EDA).
- Engineer meaningful features.
- Build an interactive Power BI dashboard.
- Train and evaluate machine learning models.
- Predict hotel booking cancellations.
- Generate business insights and recommendations.

---

# 📊 Dataset Information

### Dataset Name

Hotel Reservation Dataset

### Source

Provided by **Infotact Solutions** for Data Analytics Internship Project 2.

### Dataset Statistics

| Attribute | Raw Dataset | Cleaned Dataset |
|-----------|------------:|----------------:|
| Records | 35,555 | 35,555 |
| Features | 18 | 25 |
| Missing Values | Present | 0 |
| Duplicate Records | Checked | Removed (if any) |
| Feature Engineering | Not Applied | Applied |
| Machine Learning Ready | ❌ No | ✅ Yes |

### Target Variable

**booking_status**

- **0** → Cancelled
- **1** → Not Cancelled

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
│   ├── eda.ipynb
│   ├── dashboard_analysis.ipynb
│   └── ml_preprocessing.ipynb
│
├── dashboard/
│   └── Hotel_Dashboard.pbix
│
├── reports/
│   ├── business_insights.md
│   ├── ml_findings.md
│   ├── business_recommendations.md
│   ├── model_summary.md
│   └── final_report.md
│
├── docs/
│
└── README.md
```

---

# 👥 Team Members & Responsibilities

| Team Member | Responsibility |
|-------------|---------------|
| **Jebin Joy (Team Leader)** | Machine Learning, Predictive Analytics, Documentation & GitHub Management |
| **Saurav Gopinath** | Data Cleaning, Data Preprocessing & Feature Engineering |
| **Rivya Roy** | Exploratory Data Analysis (EDA), Data Visualization & Power BI Dashboard |

---

# 🛠 Technologies Used

### Programming

- Python

### Libraries

- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

### Visualization

- Power BI

### Development Tools

- VS Code
- Jupyter Notebook

### Version Control

- Git
- GitHub

---

# 🔄 Project Workflow

## Week 1 – Data Preparation

- Repository Setup
- Dataset Collection
- Data Cleaning
- Missing Value Handling
- Duplicate Checking
- Data Validation
- Initial Project Planning

---

## Week 2 – Analysis & Preprocessing

- Exploratory Data Analysis
- Statistical Analysis
- Feature Engineering
- Data Visualization
- Dashboard Planning
- Machine Learning Dataset Preparation

---

## Week 3 – Dashboard & Machine Learning

### Dashboard

- KPI Development
- Interactive Dashboard
- Booking Analysis
- Pricing Analysis
- Customer Analysis

### Machine Learning

- Logistic Regression
- Decision Tree
- Model Evaluation
- Feature Importance
- Model Comparison

---

## Week 4 – Documentation & Reporting

- Business Insights
- Business Recommendations
- Final Report
- README Documentation
- GitHub Finalization
- Project Submission

---

# 🧹 Data Cleaning & Preprocessing

The dataset was cleaned and prepared before analysis.

Tasks Performed:

- Missing Value Handling
- Duplicate Record Checking
- Data Type Validation
- Feature Engineering
- Dataset Validation
- Machine Learning Dataset Preparation

---

# 📊 Exploratory Data Analysis (EDA)

EDA was performed to understand booking behaviour and discover meaningful business patterns.

Analysis Included:

- Booking Status Distribution
- Lead Time Analysis
- Average Room Price Analysis
- Room Type Analysis
- Meal Plan Analysis
- Market Segment Analysis
- Guest Composition Analysis
- Booking Segment Analysis
- Correlation Analysis

---

# 📈 Feature Engineering

Additional features were created to improve analysis and predictive performance.

New Features:

- arrival_date_full
- descriptive_room_type
- descriptive_meal_plan
- total_guests
- total_nights
- revenue_per_night
- booking_segment

---

# 📊 Dashboard Development

An interactive Power BI dashboard was developed to visualize booking behaviour and business performance.

Dashboard Components:

### KPI Cards

- Total Bookings
- Cancelled Bookings
- Successful Bookings
- Cancellation Rate
- Average Room Price
- Average Lead Time

### Charts

- Booking Status Distribution
- Market Segment Analysis
- Room Type Distribution
- Meal Plan Analysis
- Lead Time Analysis
- Booking Segment Analysis
- Average Room Price Comparison
- Monthly Booking Trend

### Interactive Features

- Filters
- Slicers
- Cross Filtering
- Dynamic Visualizations

---

# 🤖 Machine Learning

The cleaned dataset was prepared for predictive modeling.

### Data Preparation

- Feature Selection
- Removal of Redundant Columns
- Label Encoding
- Train-Test Split

### Models Trained

- Logistic Regression
- Decision Tree Classifier

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC Score

### Model Comparison

Both models were evaluated and compared to determine the best-performing classifier for booking cancellation prediction.

---

# 📌 Business Insights

The project identified several booking characteristics that influence hotel reservation cancellations.

Key observations include:

- Longer lead-time bookings show higher cancellation probability.
- Repeat guests are less likely to cancel reservations.
- Market segment significantly influences booking behaviour.
- Room pricing affects customer cancellation decisions.
- Booking patterns vary across different customer segments.

---

# 💡 Business Recommendations

Based on the analysis and machine learning results, the following recommendations were proposed:

- Monitor long lead-time bookings.
- Improve customer loyalty programs.
- Optimize room pricing strategies.
- Focus retention efforts on high-risk customer groups.
- Use predictive analytics to identify potential cancellations before arrival.
- Improve operational planning using cancellation forecasts.

---

# 🚀 Future Scope

Possible future enhancements include:

- Random Forest Classifier
- XGBoost
- Hyperparameter Tuning
- Cross Validation
- Real-time Prediction System
- Flask/Streamlit Deployment
- Cloud Deployment
- Live Dashboard Integration

---

# 📌 Project Outcome

Successfully developed a complete end-to-end hospitality analytics solution that combines:

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Interactive Dashboard
- Machine Learning
- Business Insights

The project demonstrates how data analytics and predictive modeling can help hotels reduce booking cancellations, improve operational efficiency, and support data-driven decision-making.

---

# 📜 License

This project was developed for educational and internship purposes under **Infotact Solutions**.

---

# 🙏 Acknowledgement

We sincerely thank **Infotact Solutions** for providing the opportunity, mentorship, and dataset that enabled us to complete this project successfully. We also appreciate the guidance provided throughout the internship, which helped us strengthen our practical knowledge of Data Analytics, Visualization, and Machine Learning.
