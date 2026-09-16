# 🚘 Car Insurance Risk and Claim Analysis | Power BI Dashboard

An interactive Power BI dashboard that analyzes auto insurance claims data across policyholder demographics, vehicle attributes, geography, and coverage type — helping insurers identify high-risk segments and understand what drives claim costs.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Status](https://img.shields.io/badge/status-completed-brightgreen?style=for-the-badge)

---

## 📌 Project Description

This project turns raw auto insurance policy and claims data into a single-page, densely-informative Power BI dashboard designed for risk analysts, actuaries, and underwriting teams. The report breaks down total claim amount across a wide range of risk factors — car use, make, coverage zone, driver age group, education, marital status, number of kids driving, and vehicle model year — enabling teams to quickly spot which segments are driving claim costs and adjust pricing or underwriting strategy accordingly.

The report answers key business questions such as:
- What is the total policy count, total claim amount, average claim amount, and average claim frequency?
- Is claim cost concentrated among commercial or private vehicle use?
- Which car makes and coverage zones generate the highest claim amounts?
- How does claim amount vary by policyholder age group and gender?
- Does the number of kids driving in a household correlate with claim amount?
- How do claim amounts trend across vehicle model years?
- How do education level and marital status jointly influence claim amount?

---

## ✨ Features

- **📋 Summary KPI Panel** — Total Policies, Total Claim Amount, Average Claim Amount, and Average Claim Frequency
- **👫 Gender Split Visual** — Icon-based male vs. female policyholder counts
- **🚗 Total Claim Amount by Car Use** — Donut chart comparing Commercial vs. Private vehicle claims
- **🏭 Total Claim Amount by Car Make** — Ranked horizontal bar chart across manufacturers (Ford, Chevrolet, Dodge, Toyota, GMC, Mitsubishi, Mazda, Pontiac, etc.)
- **🗺️ Total Claim Amount by Coverage Zone** — Donut chart across Urban, Highly Urban, Rural, Suburban, and Highly Rural zones
- **🎂 Total Claim Amount by Age Group** — Column chart across six driver age bands (15–25 through 66–75)
- **👶 Total Claim Amount by Kids Driving** — Column chart showing claim concentration by number of kids driving in the household
- **📈 Total Claim Amount by Car Year** — Line chart trending claim amount across vehicle model years (1990–2020)
- **🎓 Total Claim Amount by Education** — Pie chart across Bachelors, High School, Masters, and PhD
- **📊 Claim Amount by Education & Marital Status Matrix** — Cross-tab table (Divorced, Married, Separated, Single) with row and column totals
- **🎛️ Dynamic Filtering** — Gender slicer and a dynamic **Select Measure** control to swap the underlying metric across visuals
- **🎨 Custom Theme** — Dark teal background with mint/seafoam accent palette for a calm, data-forward look

---

## 🛠️ Technologies Used

| Tool / Skill | Purpose |
|---|---|
| **Power BI Desktop** | Report design, data modeling, and visualization |
| **Power Query (M)** | Data cleaning, shaping, and transformation |
| **DAX (Data Analysis Expressions)** | Calculated measures (Avg. Claim Amount, Avg. Claim Frequency, dynamic measure switching) |
| **Data Modeling** | Relationship modeling between policy, claims, and vehicle attribute tables |
| **Excel / CSV** | Source data format (insurance policy and claims export) |

---

## 📈 Key Metrics Tracked

| KPI | Description |
|---|---|
| **Total Policies** | Count of active insurance policies analyzed |
| **Total Claim Amount** | Sum of all claims paid across the portfolio |
| **Average Claim Amount** | Mean claim value per policy |
| **Average Claim Frequency** | Mean number of claims filed per policy |
| **Claim Amount by Car Use** | Commercial vs. Private use claim split |
| **Claim Amount by Coverage Zone** | Claims concentration by geographic risk zone |
| **Claim Amount by Age Group** | Claims concentration by driver age band |

---

## 🗂️ Project Structure

```
car-insurance-risk-claim-analysis/
│
├── screenshots/
│   └── 1_dashboard_overview.png
│
├── data/
│   └── car_insurance_claims_data.csv     # (add your source dataset here)
│
├── Car_Insurance_Risk_Claim_Analysis.pbix    # Power BI report file
├── README.md                             # Project documentation
└── LICENSE
```

---

## 👤 Author

** Vikas Kumar **
📧 Email: vikashkumarsilco@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/vikash-kumar-data-analyst/
💼 Portfolio: https://vikashraghav.netlify.app/
🐙 GitHub: https://github.com/vikashraghav26

---


⭐ **If you found this project useful, consider giving it a star on GitHub!**
