# 📊 Employee Retention Cohort Analysis Dashboard

> **Author:** Mohan Anbazhagan | Business Analytics Strategist – myeX Analytics  
> **Client Region:** United Kingdom  
> **Project Type:** B2B Cohort Analysis – HR & Workforce Analytics  
> **Tools Used:** Tableau Desktop, Excel, Data Wrangling, Retention Cohort Methodology

---
## 📚 Table of Contents

- [🚀 Project Summary](#-project-summary)  
- [📁 Project Files](#-project-files)  
- [📌 Key Features of the Dashboard](#-key-features-of-the-dashboard)  
- [📊 Sample Visual (Dashboard Screenshot)](#-sample-visual-dashboard-screenshot)  
- [🔍 Analytical Approach](#-analytical-approach)  
- [💼 Business Value Delivered](#-business-value-delivered)  
- [✅ Strategic Recommendations](#-strategic-recommendations)  
- [🔗 Connect with Me](#-connect-with-me)  
- [🏁 How to Use](#-how-to-use)  
- [📌 Tags](#-tags)

---

## 🚀 Project Summary

This project presents a dynamic **Cohort Retention Dashboard** developed in Tableau for a UK-based client to visualize **employee retention trends over 65 weeks**. The goal was to empower HR and operations stakeholders to identify drop-off patterns and improve workforce retention strategies based on location, start cohorts, and weekly trends.

The dashboard delivers actionable insights by applying **cohort analysis methodology**, tracking weekly employee presence from start to exit. Locations are intelligently grouped (North London, South, Outside London, etc.) to support **region-specific decision-making** and align with modern HR analytics best practices in the **UK and US markets**.

---

## 📁 Project Files

- `EMPLOYEE DATA.xlsx` – Raw input file provided by client  
- `Cohort Matrix_ Employee Retention %.twbx` – Tableau packaged workbook file  
- `Employee Retention % Cohort Analysis` – Images of dashboard views  

- [Download}(https://drive.google.com/drive/folders/1bcT8M4DxDli6fyKb0MVv7wkBSMwjwxl6?usp=sharing) 
---

## 📌 Key Features of the Dashboard

- 📅 **Cohort-based Retention Tracking:** Shows percentage of employees retained every week up to 65 weeks since joining  
- 🔄 **Employee Left Count:** Highlights how many employees exited in each week  
- 🌍 **Location Grouping:** Smart categorization of `Primary Work Locations` into:
  - North London
  - South London
  - East London
  - West / NW London
  - Greater London
  - Outside London

- 📊 **Interactive Views:** Filter by work country, start date, and cohort grouping  
- 🧠 **Business-Ready Visuals:** Suitable for executive reviews, HR dashboards, and predictive workforce planning

---

## 📊 Sample Visual (Dashboard Screenshot)

![Retention Cohort Matrix](screenshots/retention_dashboard.png)

---

## 🔍 Analytical Approach

### ➤ Input Fields Used
- `effective_date`  
- `employee_id`  
- `primary_work_location`  
- `worker_start_date`  
- `termination_date`  
- `retention_week_01` to `retention_week_65` (binary status flags)

### ➤ Cohort Logic
- Each employee was grouped by their **start week**.
- Retention flags per week were calculated based on the difference between `start date` and `termination date`.
- A matrix view was created with **rows as cohort weeks** and **columns as Retention Week 01 to 65**.
- **% Retained** was calculated as:



### ➤ Location Grouping Logic (UK-centric)

| Group Location     | Primary Work Locations |
|--------------------|------------------------|
| North London       | Spoke Enfield, Spoke Walthamstow, Zoom Leyton, Zoom Canning Town |
| East London        | Spoke Dagenham         |
| South London       | Spoke Crawley, Spoke Merton, Spoke Ruislip |
| West/North-West London | Spoke Park Royal, Spoke Wimbledon, Spoke West Drayton, Spoke Weybridge |
| Greater London     | Home UK, Hybrid UK, Trident Place One/Two |
| Outside London     | CFC Erith, CFC Hatfield, CFC Bicester, Spoke Milton Keynes, etc. |

Full breakdown of 41 unique locations grouped and de-duplicated.

---

## 💼 Business Value Delivered

- Identified **critical churn windows** in Weeks 4–8 for targeted intervention.
- Delivered **location-based retention analysis** to refine local HR practices.
- Empowered client to measure the impact of **hybrid and remote models**.
- Provided actionable insights for **regional managers** to optimize employee experience and reduce turnover.
- Enabled leadership to **track improvement after retention programs** deployment.

---

## ✅ Strategic Recommendations

1. **Invest in onboarding and training during Weeks 1–8**, where drop-off is highest.
2. **Customize retention strategies per region**, based on grouped location trends.
3. **Use historical trends to forecast upcoming churn windows.**
4. **Benchmark location-specific retention goals** for site managers.
5. Explore **automated alerts in future dashboards** to highlight churn spikes.

---

## 🔗 Connect with Me

📇 **Kavitha Mohan**  
🎯 *Business Analytics Strategist – myeX Analytics*  
📧 **Email:** [your-email@example.com]  
🔗 **LinkedIn:** [https://linkedin.com/in/your-link](https://linkedin.com/in/your-link)  
📂 **Portfolio:** [myeX Analytics Portfolio](https://github.com/iammohan8)  
🌍 **Region:** India (Serving clients globally – UK, US, Asia)

---

## 🏁 How to Use

1. Download `TEST Dash.twbx` and open in Tableau Desktop.
2. Review `TEST DATA.xlsx` for input structure.
3. Explore different cohort filters in the dashboard to view insights by region and time.
4. Modify groupings or parameters to adapt to other markets or locations.

---

## 📌 Tags

`#cohort-analysis` `#employee-retention` `#tableau` `#workforce-analytics` `#uk-market` `#data-visualization` `#b2b-analytics` `#hr-analytics` `#dashboarding` `#myeXAnalytics`

