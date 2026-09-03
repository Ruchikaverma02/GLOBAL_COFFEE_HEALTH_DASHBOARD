# ☕ Global Coffee & Health Dashboard 

> An interactive Microsoft Excel dashboard designed to analyze global coffee consumption, caffeine intake, sleep duration, stress levels, health issues, occupation, and demographic patterns using Pivot Tables, Pivot Charts, Slicers, and KPI Cards.

---

## 📸 Dashboard Preview

<img width="1875" height="693" alt="DASHBOARD" src="https://github.com/user-attachments/assets/3694a428-be00-48b6-afaa-81b1d22b8e78" />

The **Global Coffee & Health Dashboard** provides an interactive visual summary of coffee consumption and its associated lifestyle and health indicators.

Users can interact with the dashboard using multiple slicers to analyze different demographic, occupational, and lifestyle segments.

---

# 📖 Project Overview

Coffee consumption is an important lifestyle behavior that can be analyzed alongside factors such as caffeine intake, sleep duration, stress levels, health issues, occupation, smoking, and alcohol consumption.

This project transforms a dataset containing **10,000 participant records** into an interactive and visually engaging **Coffee & Health Dashboard using Microsoft Excel**.

The dashboard provides a consolidated view of:

* Coffee consumption
* Caffeine intake
* Sleep duration
* Heart rate
* Stress levels
* Health issues
* Occupational differences
* Gender differences
* Country-wise coffee consumption
* Lifestyle factors

The project demonstrates how Microsoft Excel can be used as a practical **Data Analytics and Business Intelligence tool** to transform raw data into meaningful visual insights.

> **Note:** The dashboard presents descriptive patterns observed in the dataset. The results should not be interpreted as medical conclusions or proof of cause-and-effect relationships.

---

# 🎯 Project Objectives

The main objectives of this project are:

* Analyze global coffee consumption patterns
* Measure average coffee intake among participants
* Analyze average caffeine consumption
* Compare coffee consumption across different countries
* Compare caffeine intake across occupations
* Examine the relationship between coffee intake and sleep duration
* Analyze stress-level distribution
* Understand the distribution of reported health issues
* Compare coffee consumption across genders
* Explore lifestyle factors such as smoking and alcohol consumption
* Build an interactive Excel dashboard using slicers
* Present data-driven insights through effective visualization
* Demonstrate practical Excel data-analysis and dashboard-development skills

---

# 📂 Dataset Information

The dashboard is created using a global coffee and health dataset containing demographic, coffee-consumption, lifestyle, sleep, stress, and health-related information.

### Dataset Size

| Dataset Attribute |               Details |
| ----------------- | --------------------: |
| Total Records     |                10,000 |
| Total Variables   |                    17 |
| Analysis Tool     |       Microsoft Excel |
| Dashboard Type    | Interactive Dashboard |

---

## 📋 Dataset Features

| Category           | Variables                                             |
| ------------------ | ----------------------------------------------------- |
| Identification     | ID                                                    |
| Demographics       | Age, Gender, Country                                  |
| Coffee Consumption | Coffee_Intake, Coffee_Category                        |
| Caffeine           | Caffeine_mg                                           |
| Sleep              | Sleep_Hours, Sleep_Quality                            |
| Health             | BMI, Heart_Rate, Health_Issues                        |
| Stress             | Stress_Level                                          |
| Lifestyle          | Physical_Activity_Hours, Smoking, Alcohol_Consumption |
| Occupation         | Occupation                                            |

---

# 📑 Dataset Columns

The dataset contains the following 17 columns:

```text
ID
Age
Gender
Country
Coffee_Intake
Caffeine_mg
Sleep_Hours
Sleep_Quality
BMI
Heart_Rate
Stress_Level
Physical_Activity_Hours
Health_Issues
Occupation
Smoking
Alcohol_Consumption
Coffee_Category
```

### Coffee Category

The `Coffee_Category` field is used to group participants according to their daily coffee consumption.

| Coffee Category | Consumption Range                |
| --------------- | -------------------------------- |
| 0–2 Cups        | Up to 2 cups/day                 |
| 3–4 Cups        | More than 2 and up to 4 cups/day |
| 5–6 Cups        | More than 4 and up to 6 cups/day |
| 7+ Cups         | More than 6 cups/day             |

This categorization is particularly useful for analyzing the observed relationship between coffee consumption and sleep duration.

---

# 📊 Dashboard Overview

The dashboard is designed as a single-page interactive analytical report.

It contains:

### KPI Cards

* 👥 Total Participants
* ☕ Average Coffee Intake
* ⚡ Average Caffeine Intake
* ❤️ Average Heart Rate
* 😴 Average Sleep Hours

### Visualizations

* 🌍 Average Coffee Consumption by Country
* 💼 Average Caffeine Intake by Occupation
* 😴 Relationship Between Coffee Intake and Sleep Hours
* 🧠 Stress Level Distribution
* 🩺 Health Issues Distribution
* 👤 Average Coffee Intake by Gender

### Interactive Slicers

* 🌍 Country
* 👤 Gender
* 💼 Occupation
* 🍷 Alcohol Consumption
* 🚬 Smoking

---

# 📌 KPI Cards

The dashboard contains five KPI cards that provide a quick summary of the dataset.

### KPIs Included

| KPI                       |          Value |
| ------------------------- | -------------: |
| 👥 Total Participants     |         10,000 |
| ☕ Average Coffee Intake   |  2.51 cups/day |
| ⚡ Average Caffeine Intake |  238.41 mg/day |
| ❤️ Average Heart Rate     |      70.62 bpm |
| 😴 Average Sleep Hours    | 6.64 hours/day |

These KPIs provide an immediate overview of the major coffee, caffeine, sleep, and health-related indicators.

### What the KPIs Tell Us

* The dataset contains **10,000 participants**.
* Average coffee consumption is **2.51 cups/day**.
* Average caffeine intake is **238.41 mg/day**.
* Average heart rate is **70.62 bpm**.
* Average sleep duration is **6.64 hours/day**.

---

# 🎛️ Interactive Slicers

The dashboard uses Excel slicers to make the analysis interactive.

### Slicers Included

* 🌍 **Country**
* 👤 **Gender**
* 💼 **Occupation**
* 🍷 **Alcohol_Consumption**
* 🚬 **Smoking**

Users can select one or more values from these slicers to dynamically filter the dashboard.

For example, selecting:

```text
Country → USA
Gender → Female
Occupation → Healthcare
```

allows users to analyze the corresponding segment across the dashboard.

The slicers are connected to the dashboard's Pivot Tables and Pivot Charts, allowing the visualizations and analytical results to update according to the selected filters.

---

# 🌍 Average Coffee Consumption by Country

This horizontal bar chart compares the average coffee intake across different countries.

### Countries Included

The dataset contains participants from countries including:

* Australia
* Belgium
* Brazil
* Canada
* China
* Finland
* France
* Germany
* India
* Italy
* Japan
* Mexico
* Netherlands
* Norway
* South Korea
* Spain
* Sweden
* Switzerland
* United Kingdom
* USA

### Key Observation

**Spain records the highest average coffee intake at approximately 2.60 cups/day**, while **Belgium records the lowest at approximately 2.41 cups/day**.

The chart provides a quick geographical comparison of coffee consumption patterns.

### Analytical Purpose

This visualization helps answer:

* Which countries have higher average coffee consumption?
* Which countries have lower average coffee consumption?
* How does coffee consumption vary geographically?

---

# 💼 Average Caffeine Intake by Occupation

This visualization compares the average caffeine intake of participants across different occupation groups.

### Occupation Categories

The dashboard contains the following occupation categories:

* Healthcare
* Office
* Other
* Service
* Student

### Observed Pattern

The chart allows users to compare average caffeine intake across occupational groups.

For example, the dashboard shows differences in average caffeine intake between Healthcare, Office, Other, Service, and Student participants.

### Analytical Purpose

This visualization helps answer:

* Which occupation has the highest average caffeine intake?
* Which occupation has the lowest average caffeine intake?
* How does caffeine consumption vary across professional groups?

---

# 😴 Relationship Between Coffee Intake and Sleep Hours

This line chart examines the observed relationship between coffee consumption categories and average sleep duration.

### Coffee Consumption Categories

* 0–2 Cups
* 3–4 Cups
* 5–6 Cups
* 7+ Cups

### Analysis

| Coffee Category | Average Coffee Intake | Average Sleep Hours |
| --------------- | --------------------: | ------------------: |
| 0–2 Cups        |                  1.07 |                6.88 |
| 3–4 Cups        |                  2.97 |                6.55 |
| 5–6 Cups        |                  4.72 |                6.29 |
| 7+ Cups         |                  6.54 |                6.15 |

### Key Observation

The dashboard shows a clear **downward pattern in average sleep duration as coffee consumption increases**.

Average sleep decreases from:

**6.88 hours/day → 6.15 hours/day**

as coffee consumption moves from the **0–2 Cups** category to the **7+ Cups** category.

This suggests an observed association between higher coffee consumption and lower average sleep duration within this dataset.

> **Important:** This is a descriptive observation and does not prove that higher coffee consumption causes reduced sleep.

---

# 🧠 Stress Level Distribution

The dashboard includes a column chart showing the distribution of stress levels among participants.

### Stress Categories

* High
* Low
* Medium

### Overall Distribution

| Stress Level | Percentage |
| ------------ | ---------: |
| Low          |     69.89% |
| Medium       |     20.50% |
| High         |      9.61% |

### Key Observation

The **Low Stress** category represents the majority of participants, accounting for approximately **69.89%** of the dataset.

The High Stress category represents approximately **9.61%** of participants.

### Analytical Purpose

The chart helps users understand:

* Overall stress distribution
* Relative size of each stress category
* How stress distribution changes when dashboard slicers are applied

---

# 🩺 Health Issues Distribution

The dashboard uses a doughnut chart to visualize the distribution of reported health issues.

### Health Issue Categories

The chart contains four categories:

* None
* Mild
* Moderate
* Severe

### Distribution

The dataset shows that:

* **None** is the largest category
* **Mild** represents a substantial proportion
* **Moderate** represents a smaller proportion
* **Severe** represents the smallest proportion

### Key Observation

Approximately **88.17%** of participants fall into the Mild health-issues category when considering the underlying health-issue distribution used in the analysis.

> The dashboard treats health issues as a descriptive dataset variable and does not provide medical diagnosis or health recommendations.

### Analytical Purpose

This visualization helps users understand the overall distribution of reported health conditions and compare health-issue patterns using the available dashboard filters.

---

# 👤 Average Coffee Intake by Gender

This column chart compares average coffee consumption across gender categories.

### Gender Categories

* Female
* Male
* Other

### Average Coffee Intake

| Gender | Average Coffee Intake |
| ------ | --------------------: |
| Female |         2.50 cups/day |
| Male   |         2.52 cups/day |
| Other  |         2.49 cups/day |

### Key Observation

Coffee consumption is relatively similar across the three gender categories.

Male participants record the highest average coffee consumption at approximately **2.52 cups/day**, followed by Female participants at **2.50 cups/day** and Other participants at **2.49 cups/day**.

---

# ☕ Coffee Consumption Analysis

The dataset groups coffee consumption into four categories:

```text
0–2 Cups
3–4 Cups
5–6 Cups
7+ Cups
```

### Category Distribution

The **3–4 Cups** category represents the largest group, accounting for approximately **46.56% of participants**.

This indicates that moderate coffee consumption is the most common consumption group in the dataset.

---

# ⚡ Caffeine Intake Analysis

The overall average caffeine intake is:

**238.41 mg/day**

Average caffeine intake changes substantially across coffee-consumption categories.

| Coffee Category | Average Caffeine |
| --------------- | ---------------: |
| 0–2 Cups        |    101.30 mg/day |
| 3–4 Cups        |    282.24 mg/day |
| 5–6 Cups        |    448.68 mg/day |
| 7+ Cups         |    621.69 mg/day |

### Key Observation

Participants in the **7+ Cups** category have an average caffeine intake of approximately **621.69 mg/day**, compared with **101.30 mg/day** among participants consuming 0–2 cups.

---

# 🏃 Lifestyle Indicators

The dataset also contains lifestyle-related variables that can be explored through the dashboard.

### Physical Activity

Average physical activity:

**7.49 hours/week**

### Smoking

Approximately:

**20.04% of participants are recorded as smokers.**

### Alcohol Consumption

Approximately:

**30.07% of participants are recorded as consuming alcohol.**

The Smoking and Alcohol Consumption slicers allow users to examine whether dashboard patterns change for different lifestyle groups.

---

# 📈 Key Insights

The dashboard provides the following major observations:

### 1. ☕ Average Coffee Consumption

The overall average coffee consumption is:

**2.51 cups/day**

---

### 2. 😴 Coffee & Sleep

Average sleep duration decreases from **6.88 hours/day** for the 0–2 Cups category to **6.15 hours/day** for the 7+ Cups category.

This represents an observed downward pattern between coffee consumption and sleep duration.

---

### 3. ⚡ Caffeine Intake

Average caffeine intake increases significantly with higher coffee consumption:

**101.30 mg/day → 621.69 mg/day**

from the 0–2 Cups to 7+ Cups categories.

---

### 4. 🌍 Country Comparison

**Spain** has the highest average coffee consumption at approximately **2.60 cups/day**.

**Belgium** has the lowest average coffee consumption at approximately **2.41 cups/day**.

---

### 5. 🧠 Stress

Approximately **69.89% of participants report Low stress**, making it the largest stress category.

---

### 6. 👤 Gender

Average coffee consumption is very similar across genders:

* Male: **2.52 cups/day**
* Female: **2.50 cups/day**
* Other: **2.49 cups/day**

---

### 7. ☕ Most Common Coffee Category

The **3–4 Cups** category is the most common, representing approximately **46.56% of participants**.

---

### 8. 🏃 Lifestyle

Average physical activity is approximately **7.49 hours/week**.

Approximately **20.04%** of participants are recorded as smokers, while approximately **30.07%** are recorded as consuming alcohol.

---

# ❓ Analytical Questions Answered

The dashboard helps answer the following questions:

### Coffee Consumption

* What is the average coffee consumption?
* Which country has the highest average coffee intake?
* Which country has the lowest average coffee intake?
* Which coffee-consumption category is most common?
* How does coffee consumption differ across genders?

### Caffeine

* What is the average caffeine intake?
* How does caffeine intake vary across occupations?
* How does caffeine intake change as coffee consumption increases?

### Sleep

* What is the average sleep duration?
* How does sleep duration change across coffee-consumption categories?
* Is there an observed relationship between coffee intake and sleep hours?

### Stress

* What percentage of participants have Low, Medium, or High stress?
* How does the stress distribution change when slicers are applied?

### Health

* What proportion of participants report None, Mild, Moderate, or Severe health issues?
* How does the health-issue distribution change across demographic and lifestyle filters?

### Demographics & Lifestyle

* How does coffee consumption vary across genders?
* How does caffeine intake vary across occupations?
* How do Smoking and Alcohol Consumption filters affect the dashboard?

---

# 🛠️ Tools & Technologies

The project was developed using:

* **Microsoft Excel**
* Excel Tables
* **Pivot Tables**
* **Pivot Charts**
* **Slicers**
* **KPI Cards**
* Data Aggregation
* Descriptive Analysis
* Data Visualization
* Dashboard Design
* Business Intelligence

---

# 🔄 Dashboard Development Workflow

The project follows a structured data-analysis workflow:

```text
Raw Coffee & Health Dataset
              ↓
       Data Preparation
              ↓
         Excel Table
              ↓
     Coffee Categorization
              ↓
        Pivot Tables
              ↓
         KPI Creation
              ↓
        Pivot Charts
              ↓
      Interactive Slicers
              ↓
  Global Coffee & Health Dashboard
              ↓
       Data Interpretation
```

---

# 🎨 Dashboard Design

The dashboard follows a **coffee-inspired professional theme** using warm brown, beige, cream, and neutral tones.

### Design Features

* Dark coffee-brown dashboard header
* Beige KPI cards
* White chart backgrounds
* Rounded dashboard sections
* Coffee-themed KPI icons
* Consistent typography
* Interactive slicers
* Clearly separated analytical sections
* Key Insights panel
* Clean and professional visual hierarchy

The design was created to make the dashboard visually appealing while keeping the analytical information easy to understand.

---

# 📁 Project Structure

```text
Global-Coffee-Health-Dashboard/
│
├── Global Coffee Health Dashboard.xlsx
├── README.md
│
├── images/
│   └── dashboard.png
│
└── LICENSE
```
# 🎓 Skills Demonstrated

This project demonstrates practical skills in:

* 📊 Microsoft Excel Dashboard Development
* 📋 Data Analysis
* 🔄 Pivot Table Creation
* 📈 Pivot Chart Development
* 🎛️ Interactive Slicer Integration
* 📌 KPI Development
* 🧹 Data Organization
* 📊 Data Visualization
* 🔍 Exploratory Data Analysis
* 💼 Business Intelligence
* 📑 Data Interpretation
* 📈 Analytical Thinking
* 🎨 Dashboard Design
* ☕ Lifestyle Data Analysis

---

# 🚀 Future Enhancements

Potential future improvements include:

* Power Query for automated data cleaning
* Power Pivot and Data Model integration
* Timeline-based filtering
* Advanced correlation analysis
* Statistical analysis of coffee, sleep, and lifestyle variables
* More demographic analysis
* Automated dashboard refresh
* Power BI implementation
* Interactive drill-down analysis
* Predictive analytics
* Advanced analysis of coffee consumption and lifestyle indicators

---

# ⭐ If You Like This Project

If you found this project useful or interesting, consider giving the repository a **Star ⭐**.

Your support helps others discover the project and encourages further development.

---

## 👩‍💻 Author

**Ruchika Verma**
---

## 📚 Disclaimer

This dashboard is created for **educational, analytical, and portfolio purposes**.

The insights presented are descriptive observations based on the dataset. They should not be interpreted as medical advice, clinical recommendations, or evidence of cause-and-effect relationships.

The dashboard is intended to demonstrate the application of **Excel-based data analysis, visualization, and business intelligence techniques**.
