# SQL-Based-Hospital-Mortality-Survival-Study
This project focuses on analyzing **hospital mortality rates** using structured healthcare data.   The dataset (`Healthcare.csv`) contains detailed patients informations, with this, performs exploratory and analytical queries to uncover patterns, survival factors, and risk contributors.
﻿Hospital Mortality SQL Analysis

 📌 Project Overview
This project focuses on analyzing **hospital mortality rates** using structured healthcare data.  
The dataset (`Healthcare.csv`) contains detailed patient information such as demographics, ICU admission details, comorbidities, vitals, and hospital outcomes.  
The SQL script (`Hospital_Mortality_SQL_Analysis.sql`) performs exploratory and analytical queries to uncover **patterns, survival factors, and risk contributors**.

The goal of this project is to **understand patient survival trends** and identify the most important factors influencing hospital deaths.


## ⚙️ Tech Stack
- **Database**: MySQL 
- **Language**: SQL
- **Dataset**: Healthcare patient survival dataset (`Healthcare.csv`)

 📂 Project Structure

---

## 🧪 Key SQL Analysis Performed
The SQL script explores multiple dimensions of patient survival:

1. **Data Cleaning**
   - Filled missing ethnicity values with `"Mixed"`.

2. **Overall Mortality**
   - Total hospital deaths and mortality rate (%).

3. **Demographics Analysis**
   - Death count by **ethnicity** and **gender**.
   - Age analysis: average & max ages of survivors vs non-survivors.
   - Age distribution in 10-year intervals.
   - Survival comparison across age groups (e.g., under 40, 40–59, 60–79, 80+).

4. **ICU Admission Analysis**
   - ICU admit sources where most patients died.
   - Mortality by ICU type (SICU, MICU, etc.).
   - Average age of deaths per ICU admit source/type.
   - Average ICU stay length (for survivors vs deaths).

5. **Physiological Factors**
   - Average **weight, BMI, and heart rate** of deceased patients.
   - BMI distribution by ethnicity.
   - Categorization of patients into **Underweight, Normal, Overweight, Obese**.

6. **Comorbidity Analysis**
   - Count of patients with comorbidities: AIDS, Cirrhosis, Diabetes, Cancer, etc.
   - Percentage of comorbidities among patients who died.

7. **Elective Surgery**
   - Percentage of patients who underwent elective surgery.
   - Average weight & height of male vs female elective surgery patients.

8. **High-Risk Groups**
   - Top 10 ICU IDs with highest predicted hospital death probability.
   - Mortality risk for obese patients in SICU (BMI > 30).

---

## 📊 Key Insights
- Mortality rate can be quantified and broken down by **age, gender, ethnicity, comorbidities, and ICU type**.  
- Patients **above 65** and those with **serious comorbidities** (cirrhosis, leukemia, etc.) showed higher mortality.  
- Certain **ICU types and admission sources** had significantly higher death rates.  
- **Elective surgery** patients generally had better survival outcomes.  
- **BMI and weight trends** revealed obesity as a contributing factor in ICU mortality.  

---

## 🚀 How to Run
1. Import `Healthcare.csv` into your SQL database.  
2. Create schema & table (`patient_survival.ps_data`).  
3. Run queries from `Hospital_Mortality_SQL_Analysis.sql`.  
4. Explore results and visualize in BI tools (Power BI / Tableau).

---

🎯 Why This Project Matters
- Demonstrates **advanced SQL querying** with real healthcare data.  
- Highlights **data cleaning, aggregation, grouping, and probability analysis**.  
- Useful for **data analyst roles in healthcare, insurance, or public health**.  
- Showcases the ability to **extract actionable insights from complex datasets**.  

---

by
Richy Colin B  
_Data Analyst | SQL Enthusiast | Healthcare Data Projects_
