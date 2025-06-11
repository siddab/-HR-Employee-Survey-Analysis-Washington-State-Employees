# 🧠 HR Employee Survey Analysis – Washington State Employees

This project analyzes survey responses from approximately 14,725 public sector employees in Washington state. The goal was to clean, profile, and visualize the data to uncover actionable insights for HR leaders on employee satisfaction, engagement, and workplace conditions.

---

## 📁 Dataset Overview

- **Source**: Maven Analytics (Employee Survey Project)
- **Format**: Excel
- **Structure**: Single table
- **Original Records**: 14,725  
- **Final Records (after cleaning)**: 14,575  
- **Fields**: 10 survey-related columns

---

## 🎯 Project Objectives

### ✅ Objective 1: Profile & QA the Data

**Tasks Completed:**
- Calculated basic metrics: `min`, `max`, `count`, and number of blanks for each numeric field
- Removed all **blank** and **duplicate** responses
- Standardized inconsistent text entries in fields such as `Department` and `Question`
- Analyzed frequency counts for key fields like `Department` and `Question`

### ✅ Objective 2: Prepare the Data for Visualization

**Tasks Completed:**
- Created a new tab: `Chart source`
- Extracted a **unique list of questions**
- Calculated the **frequency of each response type** (1 to 4) per question
- Computed the **average score per question**, excluding zeros
- Derived **response proportions** (% of total valid responses)
- Sorted questions by descending average score for effective ranking

### ✅ Objective 3: Visualize & Summarize Findings

**Tasks Completed:**
- Built a **100% stacked bar chart** for all questions, showing proportion of responses (1–4)
- Applied color scheme:
  - 🔴 Shades of red/orange for negative responses (1, 2)
  - 🔵 Shades of blue for positive responses (3, 4)
- Removed unnecessary elements: x-axis, chart title, gridlines
- Added **data labels** and formatted chart for improved readability

🎯 **Bonus Feature**: Implemented a Likert-style layout where:
- Bars are centered,
- Negative responses skew **left**,
- Positive responses skew **right**,
- Based on custom calculated columns like `Left`, `Right`, `1.1`, `4.1`

---

## 📊 Key Insights & Recommendations

- Questions related to **role clarity** and **purpose alignment** scored the highest on average.
- Responses were more negative for questions tied to **inclusivity** and **recognition**.
- Some departments showed significantly lower engagement scores — these require further investigation.
- Recommend targeted HR interventions in low-scoring departments, with a focus on manager support, diversity, and communication strategies.

---

## 🧰 Tools Used

- **Microsoft Excel**: Data cleaning, transformation, visualization
- **Pivot Tables & Charts**: Response aggregation
- **Custom formulas**: Proportion and average calculations
- **Excel Chart Formatting**: For advanced Likert-style visual alignment

---

## 📁 Files Included

| File Name | Description |
|-----------|-------------|
| `HR Employee Survey Responses.xlsx` | Raw dataset with 14,725 survey responses |
| `HR Employee Survey Responses completed.xlsx` | Final cleaned version with added charting data and visualizations |


---

## 🏁 Final Thoughts

This project highlights the power of thoughtful data cleaning and presentation. By preparing well-structured charts and dashboards, HR leadership can easily grasp complex feedback and make informed decisions. The entire workflow, from QA to visualization, was designed with clarity and actionability in mind.


