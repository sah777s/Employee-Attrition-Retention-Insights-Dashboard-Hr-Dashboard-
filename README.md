# Employee-Attrition-Retention-Insights-Dashboard-Hr-Dashboard-

## 📌 Project Overview

Built an interactive Power BI dashboard analyzing employee attrition across 1,470 records, focusing on key drivers like satisfaction, promotion delays, compensation, and overtime. Used DAX to calculate risk scores, high-performer attrition, and diversity insights to support data-driven HR decisions.

## Link
<a href="https://github.com/sah777s/Employee-Attrition-Retention-Insights-Dashboard-Hr-Dashboard-">Dashboard</a>

#  📌 Business Questions Answered

- This Power BI HR Attrition Dashboard addresses the following key business questions:

- What is the overall attrition rate, and how much does employee turnover cost the organization?

- Which departments and job roles show the highest attrition risk?

- Are top-performing employees (PerformanceRating ≥ 4) leaving at an alarming rate?

- Does lower compensation correlate with higher attrition and shorter tenure?

- How does lack of promotion (3+ years without promotion) impact employee retention?

- Are employees working overtime more likely to leave or experience poor work-life balance?

- What is the relationship between job satisfaction and attrition?

- Which demographic groups (by age, gender, education) are most likely to leave?

- Can a custom attrition risk score help identify at-risk employees proactively?

- What strategic HR actions can improve retention, equity, and engagement?

## 📊 Key Insights from the Dashboard

- **Overall Attrition Rate**: 16.12%  
- **Attrition Cost**: Estimated at ₹1.54M annually due to turnover.  
- **Sales Representatives** show the highest attrition (39.76%), followed by **employees aged 18–25** (38%).  
- **High Performers (Performance Rating ≥ 4)** are leaving at a rate of 16.37%.  
- **25.37% of employees** haven't received a promotion in 3+ years — a major disengagement signal.  
- **Overtime workers** experience 2× higher attrition than those without overtime.  
- **Employees earning < ₹2K/month** churn at 54.5%; higher earners tend to stay significantly longer.  
- **Job Satisfaction ≤ 2** is strongly linked to higher attrition in high-stress roles.  
- **Lower Work-Life Balance and Environment Satisfaction scores** are common among those who left.  
- **Attrition Risk Score (scale 0–5)** effectively identifies at-risk employees by department and role.  
- **Diversity Metrics** reveal varying attrition rates by **gender**, **age group**, and **education level**.

  ## 🔄 Project Process

1. **📥 Data Collection**  
   - Downloaded HR attrition dataset from **ZoomCharts public dataset repository** (CSV format).

2. **🧹 Data Cleaning (Excel)**  
   - Checked for duplicates, missing values, and formatting issues.  
   - Standardized column names and cleaned categorical values (e.g., Gender, Department).

3. **🔎 Exploratory Data Analysis (Python - Pandas & NumPy)**  
   - Analyzed key trends: Attrition distribution, satisfaction scores, promotion history.  
   - Engineered new fields like `Attrition_Flag` and grouped metrics (e.g., Age Band, Income Band).  
   - Created intermediate summaries and calculated risk metrics.

4. **📊 Data Visualization & Dashboarding (Power BI)**  
   - Built interactive dashboards with DAX measures for KPIs and attrition insights.  
   - Designed visuals: KPI cards, scatterplots, heatmaps, and demographic filters.  
   - Added dynamic slicers (Department, Gender, Job Role, Age Group) for drill-down analysis.
 ![image alt](https://github.com/sah777s/Employee-Attrition-Retention-Insights-Dashboard-Hr-Dashboard-/blob/528041124f58e7241866c79ee1fa6e4190ec4afd/Screenshot%202025-06-30%20204619.png)
 ![image alt](https://github.com/sah777s/Employee-Attrition-Retention-Insights-Dashboard-Hr-Dashboard-/blob/528041124f58e7241866c79ee1fa6e4190ec4afd/Screenshot%202025-06-30%20204805.png)
 ![image alt](https://github.com/sah777s/Employee-Attrition-Retention-Insights-Dashboard-Hr-Dashboard-/blob/528041124f58e7241866c79ee1fa6e4190ec4afd/Screenshot%202025-06-30%20204820.png)
 ![image alt](https://github.com/sah777s/Employee-Attrition-Retention-Insights-Dashboard-Hr-Dashboard-/blob/528041124f58e7241866c79ee1fa6e4190ec4afd/Screenshot%202025-06-30%20204839.png)
![image alt](https://github.com/sah777s/Employee-Attrition-Retention-Insights-Dashboard-Hr-Dashboard-/blob/528041124f58e7241866c79ee1fa6e4190ec4afd/Screenshot%202025-06-30%20204858.png)

#  Project Insights

- Overall attrition rate is 16.12%, costing the company approximately ₹1.54M annually.

- Sales Representatives and employees aged 18–25 show the highest attrition, exceeding 35%.

- High-performing employees (Rating ≥ 4) are leaving at a 16.37% rate, risking top talent loss.

- 25.37% of employees haven't been promoted in over 3 years, correlating with higher attrition.

- Overtime significantly increases attrition risk, with 2× higher exit rates than non-overtime staff.

- Low-income employees (< ₹2K/month) face a 54.5% attrition rate — the highest in all salary bands.

- Job Satisfaction scores ≤ 2 are common among leavers, especially in high-pressure roles.

- Poor Work-Life Balance and Environment Satisfaction scores strongly align with attrition.

- Attrition Risk Score (0–5) effectively flags high-risk roles and departments for early HR intervention.

- Diversity trends show higher attrition among younger employees and certain education levels.

# ✅ Final Conclusion

- The HR Attrition Dashboard reveals that employee turnover is highest among young, underpaid, overworked, and under-promoted staff—highlighting the urgent need for data-driven HR strategies focused on compensation, career growth, and employee well-being to improve retention and workforce stability.
