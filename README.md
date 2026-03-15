#  Hotel Harmony: Data Insights for Optimized Operations

**Developed by:** Adarsh Dwivedi  
**Role:** Data and Business Analyst  

This repository features a comprehensive **Exploratory Data Analysis (EDA)** on the booking patterns of *Elite Hotels International*.  
By analyzing a dataset of **119,390 bookings**, this project identifies key drivers of cancellations, seasonal demand, and guest behavior to optimize hospitality operations and revenue management.

---

##  Technical Highlights & Tool Stack
- **Python (Pandas, NumPy):** Advanced data cleaning, handling missing values (children, country, agent), and variable re-typing.  
- **Data Transformation:** Engineered new features like `Total_Stay_Duration` and `Revenue_per_Booking`.  
- **Exploratory Data Analysis (EDA):** Univariate & bivariate analysis to uncover correlations (e.g., lead time vs. cancellation rates).  
- **Visualization (Matplotlib & Seaborn):** Box plots, heatmaps for seasonal booking trends.  
- **Dashboarding:** Interactive KPI summaries (ADR, Cancellation Ratios).  

---

##  Technical Workflow
1. **Data Quality Audit:** Cleaned raw CSV, treated missing values, removed duplicates.  
2. **Market Segmentation:** Booking behavior across channels (Direct, TA/TO, Corporate).  
3. **Temporal Analysis:** Arrival patterns across years/months to identify peak seasons.  

---

##  Business Logic & Impact
- **Cancellation Mitigation:** High lead time → higher cancellations. Suggested *Strict Deposit* policy for >6 months advance bookings.  
- **Revenue Optimization:** ADR analysis for dynamic pricing strategies.  
- **Operational Efficiency:** Ratio of adults/children/babies → optimized room assignments & amenities.  
- **Customer Loyalty:** Segmented repeated vs. new guests to evaluate loyalty programs.  

---

##  Strategic Insights
- **Peak Seasonality:** City hotels show higher demand in specific months → better staff scheduling.  
- **Booking Channels:** Certain segments have longer lead times → target early-bird promotions.  
- **Special Requests:** Strong correlation with lower cancellations → engaged guests more likely to stay.  

---

##  Repository Structure
- `hotel_bookings.csv` → Raw dataset (31 features).  
- `Hotel_Operations_EDA.ipynb` → Python notebook with detailed commentary.  
- `EDA02 - Hotel Operations Analysis.docx` → Project background, data dictionary, solution guide.  

---
