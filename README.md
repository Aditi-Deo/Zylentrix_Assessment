# Zylentrix_Assessment

This project is a comprehensive analysis of user engagement and satisfaction on an online learning platform (Zylentrix), performed as part of a Data Analyst Internship assignment.

---

## 🗂️ Project Structure

 ZylentrixAssessment/ │ 
 ├── Zylentrix_Assessment.pbix # Power BI dashboard file 
 ├── ZylentrixAssessment.ipynb # Jupyter Notebook (data cleaning + EDA in Python) 
 ├── students.csv # Student demographic and enrolment data 
 ├── course_activity.csv # Course engagement metrics 
 ├── feedback.csv # Course feedback and ratings
 ├── README.md # Project overview and guide (this file)


 
---

## 🧾 Problem Statement

Zylentrix runs an online training platform offering various courses (e.g., Python, UI/UX, Digital Marketing). The goal is to analyze how users interact with the platform by studying:

- Student engagement (time spent, completion %)
- Feedback ratings
- Demographic insights (age, location, etc.)

---

## ✅ Tasks Completed

### 🔍 Data Cleaning (Python)
- Removed duplicates and checked for missing values
- Converted date columns to datetime format
- Created age groups for analysis

### 📊 Exploratory Data Analysis (EDA)
- Calculated average course completion rates
- Identified top and bottom performing courses
- Analyzed engagement by age group and location
- Correlated feedback rating with course completion

### 📈 Visualizations & Dashboards (Power BI)
- Bar charts: Engagement by course, age group, location , Average rating per course
- KPI cards: Avg. completion %, avg time spend per course, and feedback rating
- Scatter plot: Completion % vs Feedback
- Interactive slicers: Filter by course, age group, or city

---

## 📌 Key Insights

- Students aged 21 - 25 were the most engaged
- Course DM101 had the highest average time spent
- Positive correlation observed between course completion and feedback rating
- Kolkata students showed higher engagement than others
- PY202 has the highest ratings 

---

## 💡 Recommendations

1. Improve course structure/content in lower-rated courses
2. Target low-engagement locations with incentives
3. Use reminders or gamification to increase course completion rates

---

## 🚀 How to Run This Project

### 🔧 Requirements
- Python (with pandas, seaborn, matplotlib for the notebook)
- Power BI Desktop (for dashboard viewing)




