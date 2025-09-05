# 🏠 London Housing Data Analysis

## 📌 Project Overview
This project analyzes the **London Housing dataset** to uncover insights about housing prices, crime rates, and affordability across different areas of London.  
The dataset includes 13,549 records with features such as **date, area, average price, houses sold, and number of crimes**.

---

## 🔎 Key Steps in the Analysis
1. **Data Preprocessing**
   - Extracted the `year` column from `date` for easier time-based analysis.
   - Handled missing values in `houses_sold` and `no_of_crimes`.
   - Removed unnecessary columns for a cleaner dataset.

2. **Crime Analysis**
   - Identified all records with **0 reported crimes** and counted them.
   - Found the **maximum and minimum crimes per area** to highlight regional differences.

3. **Housing Price Analysis**
   - Calculated **yearly maximum and minimum average prices** across England.
   - Identified **affordable areas** where average prices were below £100,000.

---

## 📊 Insights & Conclusion
- The dataset reveals clear **trends in housing prices** over the years.  
- **Crime statistics vary significantly by area**, with some regions being much safer than others.  
- Certain areas had **affordable housing (< £100,000)**, making them attractive for budget buyers.  
- The analysis provides a foundation for **predictive modeling** (price forecasting) or studying **correlations between crime and housing values**.

---

## 🛠️ Tools & Libraries
- **Python**
- **Pandas**
- **Matplotlib / Seaborn**
- **Jupyter Notebook**

---

## 🚀 Next Steps
- Build a **prediction model** for housing prices.  
- Explore **correlations between crime and property values**.  
- Extend the analysis with **geospatial visualization** for better area insights.  

---
👨‍💻 *Developed by Rizvi Khan*
