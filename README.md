Employee Analytics Dashboard – Power BI Project

📌 Project Overview
This project presents an end-to-end HR analytics dashboard developed in Power BI. The dataset was modeled from multiple dimensions including Employee, Education Level, Performance Rating, Rating Level, Satisfaction Level, and DimDate, allowing analysis of workforce demographics, performance trends, and attrition rates.
The objective was to demonstrate how data modeling, DAX, Power Query, and visualization best practices can be applied to transform raw HR data into actionable business insights.

🎯 Key Skills Applied
Data Modeling: Designed star schema with fact and dimension tables (Employee, Performance, Satisfaction, DimDate).
Power Query (M language): Cleaned, transformed, and standardized datasets for reporting.
DAX Measures: Built KPIs such as Attrition Rate %, Active vs Inactive Employees, Margin%, Satisfaction Scores.
Data Visualization: Applied professional dashboarding techniques (cards, bar charts, treemaps, line charts) with consistent design and interactivity.
Business Insights: Delivered key findings for HR decision-making: hiring trends, attrition by job role/department, employee satisfaction over time, and demographics breakdown.

📊 Dashboard Features
Overview Page
Total Employees, Active vs Inactive, Attrition Rate.
Hiring trend by year and attrition status.
Active employees by department and job role.

Demographics Page
Age distribution, youngest vs oldest employees.
Gender, marital status, and ethnicity breakdown.
Salary analysis by demographic groups.

Performance Tracker Page
Individual employee tracker with job satisfaction, work-life balance, manager rating, and self rating over time.

Attrition Analysis Page
Attrition rate by job role, overtime, years at company, and business travel frequency.
Yearly attrition trend visualization.

📷 Dashboard Pages & Insights
1. Overview
![z7069833832094_fce7b65d4c0a781b263323979b1755b8](https://github.com/user-attachments/assets/e53dd674-2cbb-4adb-ab86-57a7bd841bea)

KPIs: 1,470 total employees, 1,233 active, 237 inactive, and an attrition rate of 16.1%.
Hiring trend: Volatile, with dips (2016–2018) and recovery (2019–2022). Attrition persists each year alongside new hires.
Department structure: Technology dominates (~828 active), followed by Sales (~354) and HR (~51).
Job roles: Largest groups include Software Engineers (~247), Data Scientists (~199), and Sales Executives (~269).
➡️ Implication: Technology and Sales are core workforce segments; changes here strongly affect overall performance.

2. Demographics
![z7069833832096_0f1f6a81dc9462ab9d9514c0a1f02b2e](https://github.com/user-attachments/assets/32facdc4-634e-4bce-bbfe-7dfdc9a57777)

Age range: Youngest 18, oldest 51; majority in 20–29 group (~1,000 employees).
Marital status: Married (42.4%), Single (37.3%), Divorced (20.2%).
Gender by age group: Balanced distribution, but younger cohorts dominate overall.
Salary by ethnicity: Salaries cluster between 106K–115K, but “Other” group is slightly lower (~101.6K).
➡️ Implication: Workforce skews young, requiring investment in development; salary equity across ethnic groups should be reviewed.

3. Performance Tracker
![z7069833908675_24c6474a125312080f483b9e838adec2](https://github.com/user-attachments/assets/bc7e27d5-7dfc-4dca-95b1-e29084952155)

Individual profile tracking (e.g., Anet Dublin):
Job & relationship satisfaction fluctuate, with some strong years followed by declines.
Self vs Manager rating: Inconsistent, sometimes misaligned.
Work-life balance & environment satisfaction: Periods of drop to critical levels (2–3), signaling risk of disengagement.

Review dates clearly marked for follow-up.
➡️ Implication: Useful for identifying at-risk employees and guiding manager interventions before formal reviews.

4. Attrition Analysis
![z7069833908677_30c13179826ec5fd420394549f876652](https://github.com/user-attachments/assets/415c5f3a-121f-407b-b58d-1037768c7139)

Attrition rate: 16.1% overall.
By job role: Highest among Sales Reps (39.8%), Recruiters (37.5%), Data Scientists (23.8%), Sales Executives (17.4%), Software Engineers (16%).
By travel: Frequent travelers face highest attrition; no-travel employees lowest.
By overtime: Overtime employees have significantly higher attrition.
By tenure: Attrition peaks at 0–1 years, then declines with seniority.
➡️ Implication: Early tenure, workload (OT), and heavy travel are strong predictors of attrition.

📝 Recommendations
A. Reduce Attrition & Retain Talent
Early tenure retention (0–12 months): structured onboarding, mentoring, and frequent check-ins; target ≥30% reduction in first-year attrition.
High-risk roles (Sales Reps, Recruiters, Data Scientists): review workloads, incentives, and career paths; introduce role-specific retention initiatives.
Workload & travel policy: enforce OT limits, compensate with time-off, optimize business travel policies to prevent burnout.

B. Workforce Planning & Talent Development
Technology & Sales planning: invest in technical leadership programs and sales enablement training.
Demographics strategy: leverage the young 20–29 cohort with career fast-tracks; prepare succession planning for older employees.
C. Compensation & Equity
Pay equity analysis: conduct controlled comparisons by role/level; adjust salary bands to close unjustified gaps.

D. Performance & Engagement Processes
Early-warning risk score: combine satisfaction, manager rating, OT, travel, and tenure to trigger manager alerts; act before disengagement leads to attrition.

E. Power BI Enhancements
Standardized measures: Attrition %, Active/Inactive, Satisfaction Index, Tenure Buckets for consistency.
Advanced reporting: Drillthrough from overview → individual profiles; role-based access (RLS); bookmarks for executive vs HRBP views.
Data ops: Automated refresh, data quality logging, and a data dictionary for transparency.

🚀 Key Outcomes
Built a professional HR dashboard consolidating multiple dimensions.
Identified insights into retention, workforce structure, and performance dynamics.
Demonstrated full-cycle Power BI expertise: data ingestion → modeling → DAX → dashboard storytelling.

