# Flu-Shot-Compliance-Dashboard

Tools Used: SQL, Tableau

📊 Overview
This dashboard analyzes flu shot compliance among active hospital patients in 2022. It highlights compliance trends by age and race and visualizes cumulative vaccination progress over the year.
All data transformations were performed using optimized SQL queries, and the interactive dashboard was built using Tableau.

🎯 Objectives
✅ Compute compliance percentage stratified by:
1. Age Group
2. Race

Overall:
📈 Visualize running total of flu shots given throughout the year
🔢 Display the total number of flu shots administered in 2022
🧾 Generate a list of patients showing individual flu shot status

⚙️ Data Processing (SQL)
1. Filtered for "Active Patients" in 2022
2. Calculated patient age and categorized into groups
3. Joined immunization records to identify flu shot administration
4. Used Common Table Expressions (CTEs) to:
5. Eliminate duplicate immunization records

📊 Dashboard Features (Tableau)
📌 Bar Charts: Flu shot compliance by age group and race
📈 Line Graph: Running total of flu shots administered monthly
📋 Patient Table: Searchable list showing individual flu shot status

📦 KPI Cards:
Total Compliance Percentage
Total Flu Shots Administered

💡 Key Insights (2022)
🧮 Overall Compliance
81.7% of active patients received flu shots
A total of 4,023 flu shots were administered

👵 By Age Group
Lowest compliance: 18–34 age group (64.8%)
Highest compliance: 50–64 age group (95.6%)
Compliance gap of 30.8% between age groups

🌍 By Race
Highest compliance: Native patients (93.8%)
Lowest compliance: “Other” racial group (75.0%)

📈 Running Total Trend
Flu shots steadily increased from January to November,
showing consistent monthly uptake and progress toward compliance goals.
