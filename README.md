# HR-Attrition-Analysis

# HR-Attrition-Analsyis
This analysis was performed to check the HR attrition of a company 
# 👥 HR Attrition Analysis Dashboard

<img width="977" height="548" alt="Screenshot (306)" src="https://github.com/user-attachments/assets/e3fe8435-be25-42ce-bd5a-e93c15d9b0fb" />

<img width="967" height="540" alt="Screenshot (307)" src="https://github.com/user-attachments/assets/f9774972-5734-448e-8880-ee3b3a601a4e" />

---

## 1. Objectives

The objective of this analysis is to examine employee attrition within an organization by exploring workforce demographics, educational backgrounds, departmental distribution, and factors that may contribute to employees leaving. The analysis seeks to provide HR teams and management with a data-driven understanding of attrition patterns to support better workforce planning and retention strategies.

---

## 2. Goal

The primary goals of this project are to:

- Identify the rate and volume of employee attrition across the organization
- Understand the demographic and educational profile of the workforce
- Explore the relationship between attrition and factors such as job satisfaction, work-life balance, relationship satisfaction, commute distance, and daily rate
- Provide actionable recommendations to reduce attrition and improve employee retention

---

## 3. Data Preparation

The dataset consisted of **1,470 employee records** with the following key fields used in the analysis:

- **Employee Demographics** — Age range, gender, and marital status
- **Education Level** — Bachelor's, Master's, College, Below College, and Doctor
- **Department** — Research & Development, Sales, and Human Resources
- **Attrition Flag** — Whether an employee left (Yes/No), used to compute attrition count and rate
- **Work-related Factors** — Number of companies worked at, work-life balance rating, job satisfaction, relationship satisfaction, distance from home, and daily rate

Key calculated metrics include:

- **Total Employees:** 1,470
- **Employee Attrition Count:** 237
- **Employee Attrition Rate:** 16.12%

Data was cleaned, modeled, and visualized using **Microsoft Power Query**.

---

## 4. Analysis Interpretation

### 👤 Employee Demographics

**Age Distribution:**
The largest age group is **31–40 years (619 employees)**, followed by **21–30 (358)** and **41–50 (322)**. Employees above 50 account for 154, while those under 20 are the smallest group at just 17. The workforce is predominantly in its early-to-mid career stage.

**Gender:**
The workforce is **60% male and 40% female**, indicating a moderate gender imbalance that may be worth addressing in diversity initiatives.

**Marital Status:**
- Married: **673** (largest group)
- Single: **470**
- Divorced: **327**

Marital status can be a relevant factor in attrition, as single employees tend to have higher mobility.

---

### 🎓 Education Level
The majority of employees hold a **Bachelor's degree (572)**, followed by **Master's (398)**, **College (282)**, **Below College (170)**, and **Doctor (48)**. This indicates a well-educated workforce with significant graduate-level representation.

---

### 🏢 Department Distribution
- **Research & Development** dominates with **961 employees**
- **Sales** follows with **446**
- **Human Resources** is the smallest with only **63 employees**

Attrition by education level is further broken down by department, with Sales and R&D showing the most notable attrition patterns particularly among Bachelor's and Master's degree holders.

---

### 📉 Attrition Analysis

**Attrition Rate: 16.12% (237 out of 1,470)**

This is a moderately high attrition rate that signals a need for targeted retention efforts.

**Work-Life Balance:**
The majority of employees (893) report being **"Not Affected"** by work-life balance issues, while 344 find it **"Manageable"**. Only 80 report being **"Affected"**, suggesting work-life balance alone may not be the primary driver of attrition but still warrants monitoring.

**Number of Companies Worked:**
A large portion of employees (**1,225**) have worked at **5 or more companies**, compared to 245 who have worked at fewer than 5. This high job-hopping history may correlate with higher attrition likelihood.

**Distance from Home:**
- **0–5 km:** 42.99% of employees (closest group)
- **6–10 km:** 26.8%
- **Above 10 km:** 30.2%

Employees commuting longer distances may face higher dissatisfaction, contributing to turnover risk.

**Relationship Satisfaction:**
Most employees are **"Not Affected" (459)** or report **"Perfect" (432)** relationship satisfaction. Lower scores (Manageable: 303, Affected: 276) still represent a significant portion that may be at risk.

**Job Satisfaction:**
- **Satisfied:** 459
- **Manageable:** 442
- **Not Interested:** 289
- **Low:** 280

The fact that nearly **569 employees (39%)** fall in the "Not Interested" or "Low" satisfaction categories is a significant concern and a likely driver of attrition.

**Employee Daily Rate:**
The largest group earns between **401–800 (433 employees)**, followed by **801–1200 (415)**, **Above 1200 (322)**, and **100–400 (300)**. Compensation distribution appears relatively balanced but lower-rate employees may be more susceptible to leaving.

---

## 5. Recommendations

1. **Target High-Risk Groups — Single Employees & Job-Hoppers** — Single employees and those with 5+ previous employers represent the highest mobility risk. Tailored engagement programs, career development paths, and mentorship initiatives can improve their attachment to the organization.

2. **Address Low Job Satisfaction Urgently** — With nearly 40% of employees reporting low or disengaged job satisfaction, HR must conduct regular pulse surveys and exit interviews to uncover root causes and take corrective action. Role redesign, recognition programs, and clearer growth paths are recommended.

3. **Review Compensation for Lower Pay Bands** — Employees in the 100–400 daily rate bracket are most vulnerable to attrition. A compensation benchmarking exercise against industry standards could help retain talent in this segment.

4. **Improve Retention in Sales Department** — Sales shows notable attrition especially among Bachelor's and Master's degree holders. Incentive restructuring, better sales support tools, and clearer commission structures may help.

5. **Consider Flexible Work Options for Long-Distance Commuters** — The 30% of employees commuting above 10 km face a daily burden that can fuel dissatisfaction. Remote or hybrid work options for eligible roles could reduce turnover in this group.

6. **Strengthen R&D Retention** — As the largest department (961 employees), even a modest attrition rate in R&D translates into significant knowledge and productivity loss. Focused retention programs, competitive pay, and research growth opportunities should be prioritized here.

7. **Promote Gender and Diversity Balance** — The 60/40 gender split and department skew (especially in HR) suggest an opportunity to build a more diverse and inclusive workplace, which research consistently links to lower attrition.

---

## 🛠 Tools Used

- Microsoft Query
- Microsoft Power BI (Data Modeling, Analysis & Dashboard)

---

*Analysis conducted as part of a personal data analytics portfolio project.*
