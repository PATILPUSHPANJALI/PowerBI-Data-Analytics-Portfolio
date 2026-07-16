# Student Depression Monitoring Dashboard

An interactive, multi-page Power BI dashboard designed to visualize, analyze, and monitor key factors influencing student mental health. The project transforms student demographic, academic, and lifestyle data into actionable insights to help educational institutions understand and support student well-being.

---

## 🚀 Dashboard Pages & Features

The dashboard consists of a main landing hub and 6 dedicated analytical pages, detailed below:

### 1. Home / Navigation Hub
*   Acts as the central landing page of the report.
*   Features a clean, themed interface with dynamic navigation buttons to seamlessly explore all analysis sections.

### 2. Demographic Factors
*   **Key Metrics:** Tracks overall data footprint (`16K` total depression-related records analyzed, `214K` CGPA reference points).
*   **Visuals:** 
    *   *Depression by Gender:* Donut chart showing a breakdown of records across genders (55.8% Male, 44.2% Female).
    *   *Count of Gender by Age:* Column chart highlighting student distribution across age brackets.
    *   *Granular Data:* Comprehensive data table breaking down demographic variables by unique IDs, Cities (e.g., Ahmedabad, Vadodara, Kalyan), and professions.

### 3. Academic and Work Pressure Level
*   **Visuals:**
    *   *Academic Pressure by Degree:* Horizontal bar chart isolating pressure levels across academic paths (Class 12, B.Ed, B.Com, B.Arch, BCA, etc.).
    *   *Work Pressure by Profession:* Analysis of workload strain by job categories.
    *   *Correlation Scatter Plots:* Dual scatter plots mapping **CGPA vs. Academic Pressure** and **Study Satisfaction & Work Pressure vs. CGPA** to discover performance trends.

### 4. Mental Health Indicators
*   **Visuals:**
    *   *Study Satisfaction by Sleep Duration:* Identifies how variations in sleep (Less than 5 hours, 7-8 hours, 5-6 hours, More than 8 hours) correlate to overall satisfaction.
    *   *Suicidal Ideation Breakdown:* Pie chart mapping the presence of suicidal thoughts across demographics (63.28% No, 36.72% Yes).
    *   *Depression by Dietary Habits:* Analyzes habits categorized into Unhealthy (44.67%), Moderate (34.02%), and Healthy (21.26%).
    *   *Work/Study Hours vs. Sleep Duration:* Horizontal stacked bar chart analyzing time distribution.

### 5. Satisfaction And Stress
*   **Visuals:**
    *   *Count of Study Satisfaction by Degree:* Detailed ranking of satisfaction scores across various fields of study.
    *   *Family History of Mental Illness vs. Financial Stress:* Bar chart displaying how external household stress factors compile against financial burden levels.
    *   *Average Job Satisfaction by Gender:* Column chart monitoring career/workplace happiness levels between Male and Female groups.

### 6. Family History and Support
*   **Visuals:**
    *   *Family History of Mental Illness by Gender:* Pie chart dividing historical genetic risk patterns among the student group.
    *   *Student Support Roster:* Detailed cross-reference data table sorting student profiles by City, Age, Family History, and documented indicators.

### 7. Depression Analysis
*   **Visuals:**
    *   *Depression by Dietary Habits:* Deep dive into how lifestyle routines match depression matrices.
    *   *Depression and Academic/Work Pressure by Age:* Multi-variable scatter plots showing how depression scales alongside advancing age and rising workloads.
    *   *Comprehensive Summary Roster:* Clean student lookup log displaying IDs, Cities, Genders, Dietary Habits, and Degrees for quick auditing.

---

## 🛠️ Tech Stack & Tools

*   **BI Tool:** Power BI Desktop
*   **Data Modeling & Expressions:** DAX (Data Analysis Expressions)
*   **Design & Theme:** Customized dark canvas theme with customized graphic cards for intuitive dashboard navigation.

---

## 📂 Folder Structure

This project is part of a larger Power BI Data Analytics Portfolio:
```text
PowerBI-Data-Analytics-Portfolio/
└── Student Depression Analysis Dashboard/
    ├── README.md                      # Project documentation
    └── STUDENT DEPRESSION ANALYSIS.pbix # Main Power BI project file
