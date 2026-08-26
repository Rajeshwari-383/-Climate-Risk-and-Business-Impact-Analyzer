# 🌍 Climate Risk and Business Impact Analyzer

## 📌 Project Overview

The Climate Risk and Business Impact Analyzer is a Power BI project designed to analyze how different climate events impact businesses across industries and countries.

The dashboard helps identify high-risk businesses, analyze financial losses, compare climate risk levels, and understand the relationship between climate events and business disruption.

---

## 🎯 Project Objectives

- Analyze the impact of climate events on businesses.
- Identify high-risk businesses.
- Analyze revenue loss and property damage.
- Compare climate risk across industries and countries.
- Analyze the relationship between climate severity and business downtime.
- Identify climate events causing the highest financial impact.

---

## 📊 Dataset Information

The dataset contains **1,000 business records** and **23 columns**.

### Key Columns

| Column | Description |
|---|---|
| Business_ID | Unique business identifier |
| Business_Name | Name of the business |
| Industry | Business industry |
| Country | Country where the business is located |
| State_Province | State or province |
| City | Business location |
| Event_Date | Date of climate event |
| Year | Year of climate event |
| Climate_Event | Type of climate event |
| Severity | Severity of the event |
| Temperature_Change_C | Temperature change |
| Rainfall_Deviation_Percent | Rainfall deviation percentage |
| Exposure_Score | Business exposure score |
| Vulnerability_Score | Business vulnerability score |
| Risk_Score | Overall climate risk score |
| Risk_Level | Risk category |
| Downtime_Days | Number of business downtime days |
| Revenue_Loss_USD | Revenue loss |
| Property_Damage_USD | Property damage |
| Supply_Chain_Disruption | Supply chain disruption level |
| Employees_Affected | Number of employees affected |
| Recovery_Days | Days required for recovery |
| Risk_Mitigation_Investment_USD | Investment in risk mitigation |

---

## 🧹 Data Cleaning and Preparation

The following data quality checks were performed using Python:

- Checked dataset shape.
- Checked missing values.
- Checked duplicate records.
- Reviewed data types.
- Converted the Event_Date column to date format.
- Identified numerical columns.
- Performed outlier analysis using the IQR method.

### Data Quality Results

- **Total Records:** 1,000
- **Total Columns:** 23
- **Missing Values:** 0
- **Duplicate Records:** 0

Outliers were retained because extreme values may represent genuine high-impact climate events and are important for business risk analysis.

---

## 📈 Dashboard Pages

### 1️⃣ Executive Overview

Provides a high-level summary of climate risk and business impact.

#### Key KPIs

- Total Businesses
- Total Revenue Loss
- Total Property Damage
- Total Financial Impact
- Average Risk Score
- Average Downtime

#### Visualizations

- Distribution of Climate Events
- Financial Impact by Climate Event
- Average Risk Score by Industry
- Revenue Loss Trend Over Time

#### Filters

- Year
- Severity
- Industry
- Country
- Climate Event

---

### 2️⃣ Climate Risk Analysis

Focuses on identifying and analyzing climate risk across different countries, events, and severity levels.

#### Key KPIs

- High-Risk Businesses
- Average Risk Score
- Average Downtime

#### Visualizations

- Average Downtime by Severity
- Risk Level Distribution
- Geographic Distribution of Climate Risk
- Average Risk Score by Country
- Average Risk Score by Climate Event
- High-Risk Businesses Table

---

### 3️⃣ Business Impact Analysis

Focuses on the financial and operational impact of climate events on businesses.

#### Key KPIs

- Total Revenue Loss
- Total Property Damage
- Total Financial Impact
- Average Recovery Days

#### Visualizations

- Financial Impact by Severity
- Revenue Loss by Industry
- Top 10 Most Impacted Businesses
- Property Damage by Climate Event

---
### 🔍 Key Insights

- Climate events create significant financial and operational risks for businesses.
- Different industries experience different levels of climate risk and revenue loss.
- High-severity and critical events can result in greater financial impact and business disruption.
- Climate risk varies across countries and climate event types.
- Businesses with high and critical risk levels can be identified for targeted risk management.
- Revenue loss and property damage provide important indicators of overall business impact.

---
### 🛠️ Tools and Technologies

- Power BI – Dashboard development and visualization
- DAX – Data analysis and calculations
- Python – Data cleaning and exploration
- Pandas – Data manipulation

--- 
### Author
Rajeshwari
- Aspiring Data Analyst
- Skills: Power BI | DAX | SQL | Python | Excel | Data Analysis | Data Visualization
