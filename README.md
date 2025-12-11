# Port-Authority-NY-NJ-Bus-terminal-Project-2

# Port Authority of New York & New Jersey Traffic Forecasting & Congestion Analysis

This repository contains the complete analytics and forecasting project completed for The Port Authority of New York and New Jersey as part of the BANL 6900 - Business Analytics Capstone at the **University of New Haven**.

The project focuses on analyzing and forecasting traffic trends across major Port Authority facilities bridges, tunnels, and terminals to support data driven decisions on congestion management, staffing, and long-term infrastructure planning.

---

## Project Overview

The Port Authority operates some of the busiest transportation hubs in the U.S., including the George Washington Bridge, Lincoln Tunnel, and Holland Tunnel. The main goal of this project was to analyze past traffic patterns, identify critical influencing factors, and forecast future traffic volumes beyond 2025.

I used **Azure AutoML**, **Python**, and **Google Looker Studio** to develop predictive models and dashboards that answer five business questions related to traffic flow, toll violations, seasonality, and congestion pricing.

---

## Project Objectives

| Goal | Research Question | Analytical Approach |
|------|-------------------|---------------------|
| **Goal 1** | What are the top five factors affecting the usage of bridges and terminals? | Regression Analysis (Azure AutoML & Python) |
| **Goal 2** | How many toll violators are there, and how do they vary by year, month, and facility? | Classification / Aggregation Models |
| **Goal 3** | What are the busiest times and how do weather, seasonality, and holidays affect traffic? | Time Series & Regression (Prophet, AutoML) |
| **Goal 4** | How does congestion pricing in 2025 impact traffic and rerouting patterns? | Predictive Comparison (Regression + Aggregation) |
| **Goal 5** | Forecast facility usage beyond 2025 using AutoML. | Forecasting Model (Azure AutoML XGBoost & Prophet) |

---

## Tools and Technologies

### Modeling & Machine Learning
- **Azure AutoML** → Automated model selection (XGBoost, LightGBM, Voting Ensemble)
- **Python Libraries** → Prophet, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn
- **Statistical Models** → Regression, ARIMA, Prophet, Classification, Time-Series Forecasting

### Visualization
- **Google Looker Studio (Data Studio)** – Dashboard for Goals 1–5  


---
## My Contribution

As part of the Port Authority NY–NJ Bus Terminal Analytics Project, I contributed to the following areas:

### 🔹 Data Cleaning & Preparation
- Standardized and validated multiple datasets (ridership, terminal operations, delay metrics, etc.).  
- Handled missing values, inconsistent formats, and merged disparate data sources into a unified analytical dataset.

### 🔹 Exploratory Data Analysis (EDA)
- Conducted statistical analysis to identify peak congestion periods, route-level performance, and operational bottlenecks.
- Visualized trends in commuter patterns, weekday/weekend demand, and seasonal variations.

### 🔹 Feature Engineering
- Created time-based features (hour, weekday, month) to support demand forecasting.
- Derived KPIs such as *Average Delay per Route*, *Terminal Efficiency Score*, and *Load Factor Ratio*.

### 🔹 Dashboard Development
- Enhanced and extended Power BI/Tableau dashboards for executive reporting.
- Designed interactive visualizations for ridership flows, delay analysis, and operational performance.

### 🔹 Business Insights & Recommendations
- Identified major causes of delays and inefficiencies.
- Suggested actionable improvements such as optimized bus scheduling and terminal resource allocation.


## Key Insights & Results

- **Goal 1:** EZPass usage, cash payments, and violations were the strongest predictors of facility traffic.  
  Regression model achieved **R² = 0.9939** in Azure AutoML.
  
- **Goal 2:** Toll violations exceeded **5.7 million** between 2019–2025, with sharp increases in summer and around major holidays.

- **Goal 3:** Traffic peaks during **June–August** and weekdays, confirming commuter and tourism driven behavior.  
  Prophet model captured annual and weekly seasonality effectively.

- **Goal 4:** After congestion pricing in 2025, traffic dropped by **25 million vehicles**. However, rerouting led to higher usage of alternate bridges.

- **Goal 5:** Forecasting predicts steady post-pandemic recovery, with traffic growing from **130.2M (2025)** to **132.2M (2030)** — around **4% growth**.

---

## Machine Learning Summary

| Goal | Model Used | Platform | Key Algorithms |
|------|-------------|-----------|----------------|
| 1 | Regression | Azure AutoML / Python | XGBoost, LightGBM, ElasticNet |
| 2 | Classification | Azure AutoML | Random Forest, Decision Trees |
| 3 | Time Series | Python (Prophet) | Additive Trend + Seasonality |
| 4 | Comparative Forecast | Python / AutoML | Ensemble Regression |
| 5 | Long-term Forecast | Azure AutoML / Prophet | XGBoost, ARIMA |

---

##  Recommendations for the Port Authority

1. **Increase EZPass adoption** to reduce manual toll delays and violations.  
2. **Adjust staffing dynamically** during high-traffic weekday mornings and summer weekends.  
3. **Leverage predictive dashboards** to monitor seasonal patterns and plan maintenance during off-peak months.  
4. **Integrate external data** (fuel prices, NYC events, public transit reliability) for improved forecasting.  
5. **Implement real-time alerts** for congestion management using the dashboard insights.

---



