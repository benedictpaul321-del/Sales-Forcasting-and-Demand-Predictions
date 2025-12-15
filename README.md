# 📊 Sales Forecasting & Customer Behavior Analysis

🔍 Project Overview

This project focuses on analyzing supermarket sales data to understand customer behavior, revenue drivers, and to build reliable models for short-term sales forecasting. The goal is to transform raw transactional data into actionable business insights using data analytics and time-series modeling techniques.


---

📁 Dataset

The dataset contains transactional-level supermarket sales data including:

Date & time of purchase

Product line

Quantity sold

Unit price

Tax, COGS, and gross income

Payment method, city, and branch



---

🛠️ Tools & Technologies

Python (Pandas, NumPy)

Matplotlib & Seaborn (Data Visualization)

Scikit-learn (Machine Learning Models)

Statsmodels (ARIMA / SARIMA Time Series Models)



---

🔄 Data Preprocessing

Handled missing values and data type conversions

Converted date columns to time-series format

Created lag features (lag-1, lag-7) to capture temporal dependencies

Performed groupby & pivot analysis (product, city, payment method)

Identified outliers and revenue variability using statistical measures



---

📈 Exploratory Data Analysis

Product-wise, city-wise, and payment-wise revenue analysis

Daily and weekly income trend analysis

Correlation analysis to identify key revenue drivers

Visualization using bar charts, pie charts, line plots, histograms, and boxplots


Key Insight:
Daily gross income showed high variability (CV ≈ 0.43), indicating fluctuating customer demand and revenue spikes on certain days.


---

⏳ Time Series Forecasting

Multiple forecasting models were implemented and compared:

ARIMA / SARIMA

Random Forest Regressor

Gradient Boosting Regressor


📊 Model Evaluation

Models were evaluated using MAE and RMSE.
ARIMA-based models were chosen due to their:

Lower error values

Ability to capture temporal patterns

Suitability for short-term forecasting on limited data



---

🧠 Customer Behavior Insights

Certain product lines consistently drive higher revenue

Customer spending varies significantly by day of the week

Revenue spikes suggest promotional or demand-driven effects



---

💼 Business Recommendations

Focus inventory and marketing efforts on top-performing product lines

Use short-term forecasting for staffing and stock optimization

Plan promotions strategically on high-variance days

