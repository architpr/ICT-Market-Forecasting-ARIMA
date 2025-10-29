# 📈 ICT Market Demand Forecasting: Strategic Analysis using ARIMA

## 🌟 Project Overview: Aligning with Market Analyst Job Responsibilities

This project serves as a comprehensive demonstration of the skills required for a Market Analyst role, specifically focusing on the ICT sector. It utilizes advanced time-series analysis to produce actionable, substantiated recommendations for executive decision-making.

| Job Requirement | Demonstrated Skill | Status |
| :--- | :--- | :--- |
| **Quantitative Techniques** | $\text{ARIMA}(1, 1, 0)$ Modeling & $\text{RMSE}$ Validation | ✅ Complete |
| **Market Forecasts** | 5-Year Quarterly Forecast of U.S. ICT Investment | ✅ Complete |
| **Strategic Recommendations** | Full Report with Cautious Expansion Strategy | ✅ Complete |
| **In-Depth Data Analysis** | ADF, ACF, and PACF Analysis for Stationarity | ✅ Complete |

---

## 🛠️ Technical Stack

| Tool/Library | Purpose |
| :--- | :--- |
| **Python 3.x** | Core Programming Language |
| **Pandas** | Data Ingestion and Manipulation |
| **Statsmodels** | $\text{ARIMA}$ Time-Series Modeling |
| **Scikit-learn** | Model Validation ($\text{RMSE}$) |
| **Matplotlib** | Visualization of Trends and Forecasts |

**** (You can add Shields.io badges here for Python version, libraries, etc., if you choose to implement them.)

---

## 🚀 Key Results & Strategic Deliverable

The model determined the most robust fit for the stationary ICT Investment data is **$\text{ARIMA}(1, 1, 0)$**.

### Model Performance (Validation)

| Metric | Result | Interpretation |
| :--- | :--- | :--- |
| **ARIMA Order** | $\mathbf{(1, 1, 0)}$ | Investment change is highly dependent on the **previous quarter's change** ($\mathbf{d=1, p=1}$). |
| **RMSE** | **$12.34 \text{ Billion}$** | On average, the quarterly prediction error is **\$12.34 Billion**. |

### Final Executive Summary (Actionable Insight)

> The forecast shows moderate long-term growth for U.S. ICT Investment but highlights **significant volatility** with a wide $95\%$ Confidence Interval in outer years.
>
> **Primary Recommendation:** Companies must adopt a **Cautious Expansion Strategy**. Investment priority should be placed on **flexible, high-margin software platforms** (OpEx) over fixed hardware infrastructure (CapEx) to mitigate the high downside risk identified in the forecast.

---

## 🔬 Dive Deeper: The Analysis Notebook

### **Click here to view the full, interactive analysis step-by-step:**

### [➡️ **VIEW JUPYTER NOTEBOOK** (`ICT_Market_Forecast.ipynb`) ](./ICT_Market_Forecast.ipynb)

* **Phase 1: EDA & Stationarity:** See the $\text{ADF}$ test result ($\mathbf{p=0.000000}$) that confirmed $\mathbf{d=1}$.
* **Phase 2: Parameter Selection:** Review the $\text{ACF}$ and $\text{PACF}$ plots used to determine $\mathbf{p=1}$ and $\mathbf{q=0}$.
* **Phase 3: Final Forecast:** Examine the final $\text{ARIMA}$ summary and the **5-Year Forecast Chart**.

---

## 📊 Strategic Visualization (Optional: Tableau/Power BI Link)

If you have created a dashboard (highly recommended for market analysis roles), link it here!

### [🌐 **View Interactive Dashboard on Tableau Public**](<Insert Your Tableau Public Link Here>)

**(Add a screenshot of your final forecast chart here using an image tag or direct file link)**
