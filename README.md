**Hotel Revenue Forecasting & Prediction using Machine Learning**

**Introduction**

Understanding hotel revenue trends is crucial for pricing optimization, demand forecasting, and financial planning. This project applies time-series forecasting (Prophet) and machine learning regression (XGBoost) to predict Average Daily Rate (ADR) and total monthly revenue based on historical booking data.

**By leveraging predictive analytics, hotels can:**

1. Adjust pricing dynamically based on expected ADR trends.
2. Forecast monthly revenue for budgeting and marketing strategies.
3. Identify key revenue drivers to optimize booking strategies.
   
This project provides both statistical (Prophet) and machine learning-based (XGBoost) models to improve revenue management in the hospitality industry.

**Project Workflow**

**1️⃣ Data Preparation & Cleaning**

1. Loaded cleaned hotel booking dataset.
2. Converted reservation_status_date to datetime format.
3. Aggregated ADR & total revenue by month for time-series forecasting.

**2️⃣ Time-Series Forecasting (Prophet)**

**ADR Prediction**
1. Used Facebook Prophet to predict Average Daily Rate (ADR) for the next 12 months.
2. Identified seasonality trends in pricing behavior.

**Total Revenue Prediction**

1. Forecasted monthly total revenue using Prophet.
2. Modeled both yearly and weekly revenue fluctuations.
3. Plotted trend & seasonality components to analyze revenue patterns.

**3️⃣ Revenue Prediction using XGBoost Regression**

**Trained XGBoost Regressor to predict total revenue using:**

1. Lead Time (Days before check-in when booking was made).
2. ADR (Pricing per night).
3. Total Nights Stayed (Sum of weekday & weekend nights).
4. Cancellation Status (Whether the booking was canceled).

**Evaluated model performance using:**

1. Mean Absolute Error (MAE)
2. Root Mean Squared Error (RMSE)
3. R² Score

**4️⃣ Feature Importance Analysis**

Identified which factors impact revenue the most using XGBoost.

**✔ Key Findings:**

1. Total Nights had the highest impact on revenue.
2. ADR was the second most significant factor.
3. Lead time and cancellations had minimal influence.

**5️⃣ Key Insights & Business Impact**

**Revenue Forecasting Helps Hotels Plan Ahead**
1. Hotels can anticipate high-revenue months and adjust staffing, inventory, and marketing strategies.

**ADR Optimization for Maximum Profitability**
1. Dynamic pricing adjustments based on seasonality & demand trends.
   
**Understanding Key Revenue Drivers**
1. Longer guest stays significantly impact revenue.
2. Focus on marketing extended stays and promotions to increase profitability.

**Machine Learning Improves Accuracy**
1. XGBoost model achieved high accuracy in revenue predictions.
2. Automates revenue forecasting for better financial planning.

## Tech Stack

| **Category**              | **Technology Used**       |
|---------------------------|--------------------------|
| **Programming Language**  | Python                 |
| **Data Processing**       | Pandas, NumPy            |
| **Time-Series Forecasting** | Facebook Prophet     |
| **Machine Learning Model** | XGBoost Regression    |
| **Visualization**         | Matplotlib, Seaborn      |
| **Development Tools**     | Jupyter Notebook, GitHub |


**6️⃣ Conclusion**

This project demonstrates how predictive analytics and machine learning can improve hotel revenue management. By leveraging time-series forecasting & regression models, hotels can optimize pricing, forecast demand, and maximize revenue.
