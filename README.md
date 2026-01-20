# 🏥 Hospital Emergency Room Dashboard (Power BI)

> **From ER pressure to performance clarity — a Power BI dashboard built to uncover bottlenecks, trends, and opportunities for better patient care.**

---

## 🚑 Turning Emergency Room Chaos into Clear, Actionable Insights
Emergency rooms are fast-paced, high-pressure environments where every minute matters. Delays, overcrowding, and limited visibility into operational data can directly impact patient experience and care quality.

This project is a **personal Power BI portfolio dashboard**, inspired by the *Data Tutorials* YouTube channel, built to cut through that complexity. It transforms raw emergency room data into **clear, interactive, and decision-ready insights**, enabling stakeholders to quickly understand **what’s happening, when it’s happening, and where action is needed**.

### 📊 Dashboard Overview

<img src="Main Dashboard.png" alt="Main Dashboard" width="800">

## 🎯 Problem Statement
Hospitals generate vast amounts of emergency room data, yet decision-makers often lack a consolidated and intuitive way to:
- Monitor patient inflow trends
- Track wait-time performance against SLAs
- Understand admission outcomes
- Assess patient satisfaction
- Identify peak days and peak hours

This dashboard addresses these challenges by delivering a **single source of truth** for ER performance monitoring and analysis.

---

## 🧩 Objectives
- Monitor key ER metrics on a **month-by-month basis**
- Identify trends, bottlenecks, and operational inefficiencies
- Provide **granular patient-level visibility** for investigation and validation
- Summarize insights in a clear, stakeholder-friendly format

### 📌 Key Takeaways

<img src="screenshots/Key Takeaways.png" alt="Patient Details" width="800">

---

## 🗂️ Dataset Information
- **Source:** Dataset provided by the tutorial author (*Data Tutorials – YouTube*)
- **Type:** Sample / tutorial dataset
- **Rows:** 9,216
- **Time Period:** January 2023 – December 2024

### Core Fields
- Patient ID  
- Admission Date  
- Gender, Age, Race  
- Department Referral  
- Admission Flag  
- Satisfaction Score  
- Wait Time (minutes)  

---

## 🛠️ Tools & Technologies Used
- **Power BI Desktop**
- **Power Query** – Data cleaning & transformation
- **DAX** – Measures and calculated columns  
  - SWITCH-based business logic  
  - KPI calculations  
  - Custom categorization and flags  

---

## 🧠 Skills Demonstrated
- Business Requirements & KPI Definition  
- Healthcare Operations Analytics  
- Data Cleaning & Quality Checks  
- Data Modeling in Power BI  
- DAX Calculations (SWITCH, KPIs, SLA logic)  
- Time-Based Trend Analysis  
- Interactive Dashboard Design  
- Data Storytelling for Stakeholders  

---

## 🔄 Project Workflow
1. Requirement Gathering & Business Understanding  
2. Data Walkthrough  
3. Data Connection  
4. Data Cleaning & Quality Validation  
5. Data Modeling  
6. Data Processing  
7. DAX Calculations  
8. Dashboard Layout & UX Design  
9. Visual Development & Formatting  
10. Report Development  
11. Insights Generation  

---

## 📊 Dashboard Components

### 🔹 Key Performance Indicators (KPIs)
- Total Number of Patients  
- Average Wait Time  
- Average Satisfaction Score  
- Number of Patients Referred  

<img src="screenshots/No. of Patients.png" alt="Patient Details" width="300">

<img src="screenshots/Avg Waittime.png" alt="Patient Details" width="300">

<img src="screenshots/Patients Satisfaction Score.png" alt="Patient Details" width="300">

<img src="screenshots/No. patients Reffered.png" alt="Patient Details" width="300">
---

### 🔹 Admission & SLA Analysis
- Admitted vs Non-Admitted Patients  
- Percentage of Patients Seen Within 30 Minutes  

#### Admitted vs Non-Admitted
<img src="screenshots/Admitted vs Non Admitted.png" alt="Patient Details" width="800">

#### Patients Seen Within 30 Minutes
<img src="screenshots/Patients seen within 30 mins.png" alt="Patient Details" width="800">

---

### 🔹 Patient-Level Details
A dedicated patient details view allows granular analysis and troubleshooting at the individual record level.

<img src="screenshots/Patients' Details.png" alt="Patient Details" width="800">
---

## 📈 Executive Insights
- **Patient inflow is uneven across the week**, with mid-week days consistently experiencing higher volumes — highlighting opportunities for staffing optimization.
- **Wait-time SLA performance falls short during peak periods**, indicating capacity and process bottlenecks.
- **Longer wait times correlate with lower patient satisfaction**, reinforcing the impact of operational efficiency on care quality.
- **Most ER visits do not result in admissions**, suggesting potential improvements in triage and resource allocation.
- **Hourly congestion patterns** provide actionable guidance for shift planning and workload balancing.

---

## 📁 Repository Structure
```text
Hospital-ER-Dashboard-PowerBI/
│
├── 📁 dataset/
|     ├── Hospital ER_Data.csv
|
├── 📁 screenshots/
│     ├── Asmitted vs Non Admitted.png
│     ├── Avg Waitime.png
│     ├── Key Takeaways.png
│     ├── No. of Patients.png
|     ├── No. of Patients Reffered.png
|     ├── Patients' Details.png
|     ├── Patients Satisfaction Score.png
│     └── Patients seen within 30 mins.png
|
├── Hospital ER Dashboard.pbix
|
├── Main Dashboard.png
|
└── README.md
```

## ⭐ Acknowledgment
Inspired by the **Data Tutorials** YouTube channel and created for learning and portfolio demonstration.

## 📬 Connect with me 
👩‍💻 **Created by:** Ramsha Arshad 

🔗 www.linkedin.com/in/ramshaarshad 

✉️ email: ramsha_arshad467@hotmail.com

⭐ *If you find this project helpful, feel free to star the repository!*

