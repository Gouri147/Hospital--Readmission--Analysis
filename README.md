#  Hospital Readmission Analysis

##  Project Overview
Hospital readmissions are a critical indicator of healthcare quality, patient outcomes, and operational efficiency.  
This project focuses on analyzing hospital patient data to identify key factors contributing to readmissions and to provide actionable, data-driven recommendations for improving patient care and reducing unnecessary hospital returns.

---

##  Problem Statement
High readmission rates:
- Increase healthcare costs  
- Indicate potential gaps in treatment or discharge planning  
- Strain hospital resources  

**Objective:**  
To identify the primary drivers of readmissions and support strategic interventions to reduce them.

---

##  Key Objectives
- Identify high-risk patients prone to readmission  
- Analyze the impact of demographics, hospital utilization, and treatments  
- Evaluate patterns across medical conditions and care processes  
- Develop an interactive dashboard for stakeholder decision-making  

---

##  Tools & Technologies
- **Python (Pandas, NumPy)** – Data Cleaning & Exploratory Data Analysis  
- **Excel** – Initial preprocessing and data validation  
- **Power BI** – Dashboard development and visualization  

---

##  Data Preparation & Feature Engineering
- Handled missing values and standardized categorical variables (e.g., '?' → 'Unknown')  
- Converted categorical ranges (age, weight) into analyzable formats  
- Created derived features:
  - **Total Previous Visits** (patient utilization)
  - **Comorbidity Score** (based on number of diagnoses)  
- Ensured consistency in data types and data quality across the dataset  

---

##  Key Insights

### Demographics
- **Age**: Patients aged 70+ show significantly higher readmission rates  
- **Gender & Race**: Minor variations observed; requires deeper contextual analysis  

---

### Hospital Utilization
- Patients with frequent **emergency and prior visits** have a higher likelihood of readmission  
- Indicates a pattern of recurring health issues or insufficient follow-up care  

---

###  Comorbidity
- Higher **number of diagnoses** strongly correlates with increased readmission risk  
- Patients with multiple conditions require more comprehensive care plans  

---

###  Treatment Patterns
- **Medication changes** are associated with reduced readmission rates  
- **Diabetic patients** show relatively higher readmission trends  

---

###  Weight Analysis
- Majority of patients fall within mid-range weight categories  
- Slightly higher readmission trends observed in extreme weight groups  
-  Insight is indicative due to **significant missing values in weight data**  

---

##  Dashboard Overview
An interactive Power BI dashboard was developed to:
- Monitor **readmission KPIs**  
- Analyze **patient demographics and risk factors**  
- Identify **high-risk segments**  
- Enable **data-driven decision making** for hospital stakeholders  

---

##  Limitations
- High proportion of missing values in the **weight** variable  
- Limited interpretability of medication indicators (X1–X25)  
- Absence of time-based data restricts trend and seasonality analysis  

---

##  Business Impact
- Enables **early identification of high-risk patients**  
- Supports improved **discharge planning and follow-up strategies**  
- Reduces **avoidable readmissions and associated costs**  
- Enhances **overall healthcare quality and operational efficiency**  

---

##  Future Scope
- Develop a **predictive model** for readmission risk (Logistic Regression / Tree-based models)  
- Implement **patient segmentation** using clustering techniques  
- Perform **cost analysis** to quantify financial impact  
- Integrate **real-time data pipelines** for continuous monitoring  

---

##  About Me
**Gouri Sharma**  
Aspiring Data Analyst  

---

## ⭐ If you found this project insightful, feel free to star the repository!
