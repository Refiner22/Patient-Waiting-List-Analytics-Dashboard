# 📊 Patient Waiting List Analytics Dashboard (2018–2021)

## 📘 Project Overview

The **Patient Waiting List Analytics Dashboard** provides a comprehensive, interactive view of healthcare waiting list data.  
It enables stakeholders to monitor current backlog levels, analyze historical trends, and perform detailed specialty and demographic analysis to support data-driven decision-making.

This project follows the **STAR (Situation, Task, Action, Result)** documentation framework.


Healthcare organizations face ongoing challenges in managing patient waiting lists across inpatient, outpatient, and day-case services.  
Prior to this solution:

- Waiting list data lacked centralized visibility
- Historical trend analysis was manual and fragmented
- Specialty, age, and long-wait analysis required significant effort
- Decision-makers had limited real-time insights into backlog drivers

A scalable, visual analytics solution was required to improve transparency and operational efficiency.

---
## 🎯 Task

The goal of this project was to design and deliver an **interactive BI dashboard** that enables:

### Business Objectives
- Tracking the current status of patient waiting lists
- Analyzing historical monthly trends (2018–2021)
- Comparing inpatient, outpatient, and day-case volumes
- Performing detailed specialty-level and age-profile analysis

### Key Requirements
- Support **Average** and **Median** waiting list metrics
- Provide executive-level summaries and operational drill-downs
- Enable flexible filtering and self-service exploration

---

## ⚙️ Action

### 📂 Data Scope

- **Time Period:** January 2018 – March 2021
- **Core Dimensions:**
  - Archive Date
  - Case Type (Inpatient, Outpatient, Day Case)
  - Specialty Name
  - Age Profile (0–15, 16–64, 65+)
  - Time Bands (0–3, 3–6, 6–9, 9–12, 12–15, 15–18, 18+ months)

### 📊 Key Metrics
- Total Waiting List
- Average Waiting List
- Median Waiting List
- Month-on-Month trend
- Year-over-Year comparison

---

## 🧭 Dashboard Structure

The solution consists of **two integrated dashboards**.
---

## 📌 Summary Dashboard

**Purpose:**  
Provides high-level insights for executives and senior stakeholders.

### Features

- **KPI Cards**
  - Latest Month Total Waiting List
  - Previous Year (PY) Latest Month Comparison

- **Case Type Split**
  - Donut chart showing Inpatient, Outpatient, and Day Case distribution

- **Time Band vs Age Profile**
  - Stacked bar chart highlighting waiting duration by age group

- **Top 5 Specialties**
  - Ranked by Average / Median Waiting List

- **Monthly Trend Analysis**
  - Separate trends for:
    - Inpatient & Day Case
    - Outpatient

- **Global Filters**
  - Archive Date range
  - Case Type
  - Specialty Name
  - Average / Median toggle

---

## 🔍 Detailed Dashboard
<img width="1156" height="680" alt="Screenshot 2025-12-18 153152" src="https://github.com/user-attachments/assets/25761639-a3db-4c91-97aa-a3de6f6c8a15" />
<img width="1157" height="628" alt="Screenshot 2025-12-18 153208" src="https://github.com/user-attachments/assets/2e90ec36-9a11-468f-b7d8-996ede7bf096" />



**Purpose:**  
Supports in-depth, operational-level analysis.

### Features

- **Hierarchical Table View**
  - Drill-down by:
    - Archive Date
    - Time Band
    - Age Profile
    - Specialty

- **Metrics Displayed**
  - Day Case count
  - Inpatient count
  - Outpatient count
  - Total Waiting List

- **Advanced Filtering**
  - Case Type
  - Specialty
  - Age Profile
  - Time Bands
  - Date range

### Use Cases
- Identify specialty-level backlog drivers
- Analyze long-wait patients (9–12 months, 18+ months)
- Support capacity planning and operational reporting

---

## ✅ Result

### Business Impact
- Delivered a **single source of truth** for waiting list performance
- Enabled faster, data-driven decision-making
- Improved visibility of long-wait risks and specialty bottlenecks

### Operational Benefits
- Reduced manual reporting effort
- Enabled proactive backlog management
- Improved insight into age-specific waiting patterns

### Strategic Value
- Executive-level KPI visibility
- Operational-level analytical depth
- Scalable foundation for future enhancements

---

## 📊 Metrics Summary

| Metric | Description |
|------|------------|
| Total Waiting List | Current patient backlog |
| Average Waiting List | Mean waiting list size |
| Median Waiting List | Central tendency (outlier-resistant) |
| Monthly Trend | Historical performance tracking |
| Case Type Split | Inpatient / Outpatient / Day Case |

---

## 🛠️ Tools & Technologies

- Business Intelligence Platform (e.g., Power BI)
- Interactive slicers and drill-down visuals
- Optimized data model for performance and scalability

---

## 🚀 Future Enhancements

- Target vs Actual waiting time benchmarks
- Predictive backlog forecasting
- Automated alerts for long-wait thresholds
- Integration with real-time operational systems

---

## 📄 Conclusion

The Patient Waiting List Analytics Dashboard transforms complex healthcare data into clear, actionable insights.  
By combining **executive-level summaries** with **granular operational detail**, it supports informed decision-making and improved patient flow management.

---

