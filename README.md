# 🏢 HR Analytics Dashboard (Excel + Power BI)

## 📌 Project Overview

Analyze HR data using an Excel dataset and build an interactive dashboard in Power BI. This project visualizes key HR metrics like employee count, attrition, salary, satisfaction, and absences—all sourced from a single Excel file.

---

## 📁 Repository Structure

```
📁 data/
   hr_data.xlsx            # Raw input dataset (Excel)

📁 viz/
   HR_Analytics_Dashboard.pbix  # Power BI dashboard file
   snapshot.png                 # Screenshot of the dashboard

README.md
```

---

## ⚙️ Tools & Technologies

* **Microsoft Excel** – Original dataset with employee demographics, performance scores, absences, hiring/termination dates
* **Power BI Desktop** – Data import, transformation (Power Query), DAX measures, and dashboard visualization
* **Power Query & DAX** – For data preparation, creating computed metrics and KPIs

---

## 🔍 Data Processing & Dashboard Logic

1. **Import Data**

   * Load `hr_data.xlsx` into Power BI via Power Query.

2. **Data Cleaning & Transformation**

   * Format date fields (DOB, hire, termination)
   * Create computed columns:

     * **Tenure** (in years or days)
     * **Attrition flag** (based on `DateofTermination` and `Termd`)
   * Calculate metrics:

     * **Age**, **Years Employed**, **Absences**

3. **DAX Measures**

   * Overall metrics: Total Employees, Active Employees, Attrition Rate
   * Aggregates: Avg Salary, Avg Age, Avg Tenure
   * Category breakdowns: by Department, Gender, Manager
   * KPIs: Engagement, satisfaction trends, absences

4. **Visualizations & Filters**

   * KPI cards: totals and averages
   * Charts:

     * Employee count and average salary by department
     * Attrition trends by department and manager
     * Absences, recruitment sources, satisfaction donut charts
   * Slicers: Department, Gender, Manager, Year

---

## 📊 Dashboard Highlights

* **KPI Summary**:

  * Total: 311 employees (207 active), Avg Salary ₹69K, Avg Age ≈46 years, Avg Tenure ≈2 years, Attrition Rate \~33%, 6 departments
* **Breakdowns**:

  * Employee counts and salary by department
  * Attrition by department and manager
  * Gender and marital status distributions
  * Engagement & satisfaction metrics
  * Absence trends, recruitment source counts

---

## 💡 Key Insights

* Departments with higher attrition and absence rates can be identified
* Single vs married employee attrition trends suggest focus areas
* Recruitment channels (LinkedIn vs Indeed vs referrals) effectiveness compared
* Satisfaction and engagement score impacts on turnover

---

## 🚀 How to Explore the Dashboard

1. Clone or download the repo
2. Open **HR\_Analytics\_Dashboard.pbix** in Power BI Desktop
3. Ensure `hr_data.xlsx` stays in the `data/` folder
4. Optionally refresh visuals if data path changes
5. Interact via slicers to filter by department, gender, manager, or year

---

## 📸 Preview

![oaicite:36](viz/snapshot.png)

---

## 🔭 Future Enhancements

* Automate data refresh with Power BI Gateway or Publish to Power BI Service
* Add predictive modeling for attrition and absence forecasting using ML
* Deeper demographic analysis: tenure by age/gender combo, diversity-focused insights

---


### 📞 Feedback & Contributions

Got suggestions? Open an Issue, share a screenshot of your improved dashboard, or email me at 
Contact:
name: Monika Doble
Email:monikadoble7@gmail.com. Let’s make this HR dashboard more insightful!

