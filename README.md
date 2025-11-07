# Business-Data-Management-Project-
Data-driven demand forecasting and customer segmentation analysis for Sri Meenakshi Screen Printing using Python and Excel. Includes data cleaning, regression modeling, statistical segmentation, and business insights for production and market planning.

# 🧮 Demand Forecasting and Customer Insights for Sri Meenakshi Screen Printing

This project was developed as part of the **Business Data Management (BDM)** coursework at **Amrita Vishwa Vidyapeetham**.  
It applies data analytics techniques to optimize production planning, customer segmentation, and regional demand forecasting for *Sri Meenakshi Screen Printing*, a Thamboolam bag manufacturer based in Madurai, Tamil Nadu.

---

## 🏢 Organization Overview

**Business Name:** Sri Meenakshi Screen Printing  
**Sector:** Printing Industry  

Established in 2011, the company specializes in **Offset and Screen Printing**, **ID card printing**, and **customized Thamboolam bags** for businesses and individuals across Tamil Nadu.  
It serves thousands of recurring clients, maintaining strong customer loyalty and consistent monthly demand.

---

## 🧹 Data Preprocessing

- **Dataset:** 500 order records (2022–2025)  
- **Tools Used:** Excel, Python (`pandas`, `matplotlib`, `sklearn`)  
- **Steps:**
  - Standardized date and categorical formats  
  - Removed duplicates and corrected inconsistent entries  
  - Aggregated monthly demand for forecasting  
  - Computed descriptive statistics (mean, median, std, skewness, kurtosis)

---

## 🔍 Analysis Components

### 1️⃣ Demand Forecasting
- **Model:** Linear & Polynomial Regression (degree = 7)  
- **Metrics:** MAE, RMSE, MAPE  
- **Result:** Polynomial model reduced MAPE to ~23%, indicating improved forecasting accuracy.  
- **Insight:** Demand shows a **nonlinear upward trend** with occasional spikes from bulk orders.

---

### 2️⃣ Customer Segmentation
- **Method:** Statistical segmentation (Mean ± SD)  
- **Finding:** Six high-value clients contribute ~42% of total volume, revealing dependency on key accounts.  
- **Recommendation:** Introduce **retention programs** for top clients and engagement campaigns for medium-value customers to increase repeat orders.

---

### 3️⃣ Regional Demand Analysis
- **Regions Covered:** Madurai, Coimbatore, Theni  
- **Finding:** Madurai dominates with ~78% of total orders.  
- **Recommendation:** Strengthen **logistics capacity in Madurai** and promote expansion in Coimbatore and Theni to diversify sales.

---

## 📊 Key Insights

- Nonlinear upward demand trend with moderate variability (std ≈ 1420)  
- Regional dominance in Madurai (~78% of total volume)  
- High-value clients generate 42% of total sales  
- Polynomial regression offers higher accuracy than linear forecasting  
- Actionable insights for production, customer retention, and regional expansion  

---

## 🧭 Technologies Used

- **Languages:** Python, Excel  
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `scikit-learn`  
- **Tools:** Jupyter Notebook / Google Colab, Microsoft Excel  

---

## 💡 Business Impact

The analysis enables **data-driven production planning**, **inventory optimization**, and **customer retention**, providing Sri Meenakshi Screen Printing with a sustainable competitive advantage through analytics-based decision-making.

---

## 🏁 How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/<your-username>/demand-forecasting-screen-printing.git
   cd demand-forecasting-screen-printing
