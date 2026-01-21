# 📈 Strategic Sales & Profitability Analysis — Imprimimos

## 📌 Overview
This project analyzes **15 years of historical sales data** for *Imprimimos*, a printing company, to identify revenue drivers, margin behavior, and business risks. The goal: transform raw transactional logs into decision-ready insights.

![Dashboard Preview](sales_analysis_plot.png) 
*(Note: Upload a screenshot of your Plotly chart to the repo and link it here)*

---

## 🎯 Objectives
- **Clean & Validate:** Transform raw sales data into a reliable dataset (handling missing values & outliers).
- **Analyze Risk:** Identify revenue concentration among top clients.
- **Track Trends:** Evaluate the shift from physical to digital sales channels.
- **Recommend Action:** Translate findings into specific business strategies.

---

## 🔍 Approach: The "QA First" Workflow
I applied a strict data integrity workflow to ensure the insights were trustworthy:

1. **Data Cleaning & Preparation** - Standardized 15 years of inconsistent text inputs (e.g., 'Referral' vs 'Referido').
   - Removed data entry errors (outliers < $1,000 COP).
   - Engineered new features: `Profit` (Revenue * Margin) and `Year/Month`.

2. **Exploratory Data Analysis (EDA)** - Segmented profitability by Client and Job Type.
   - Visualized seasonality trends using **Plotly** for interactive exploration.

3. **Strategic Framing** - Focused on "Net Profit" rather than just top-line revenue to find true value drivers.

---

## 📊 Key Insights
- **Digital Transformation:** A **40% shift** from physical to digital channels has occurred since **2015**, validating recent marketing investments.
- **Concentration Risk:** The top client drives a significant portion of *Profit* (not just Revenue), creating a stability risk.
- **Seasonality:** Demand peaks consistently in **February and July**, while December shows a historical dip.

---

## 💡 Recommendations
1. **Diversify Client Portfolio:** "Clone" the success of the top client to reduce dependency risk.
2. **Optimize Peak Operations:** Align inventory and staffing capacity for the **Feb/July** surges.
3. **Push High-Margin Products:** Focus sales efforts on 'Display Boards' and 'Cards', which drive the highest net profit.

---

## 🛠 Tools & Technologies
- **Python:** Pandas, NumPy
- **Visualization:** Plotly (Interactive), Seaborn, Matplotlib
- **Environment:** Jupyter Notebook

---

## 📦 Project Files
| File | Description |
| :--- | :--- |
| `dataset imprimimos original.xlsx` | Original 15-year company sales dataset (Anonymized). |
| `Imprimimos_Analysis.ipynb` | **The Main Analysis.** Step-by-step cleaning, code, and insights. |

---

## ⚠️ Limitations
- Analysis is based solely on historical transactional data.
- Operational costs (overhead, salaries) were not available, so "Profit" is based on gross margin only.
- Results should be interpreted as directional insights rather than precise financial forecasts.

---

## 🌟 Credits
Created and developed by **[Jordan Porras](https://github.com/PJordan10)**.

I welcome feedback and collaboration opportunities.  
📧 **jporras1994@gmail.com**