# 🎓 Student Performance Dashboard — Academic & Behavioral Insights

🔗 **Live Dashboard:** https://deepvejpara.github.io/PowerBi_Student_Performance/

This project is an **interactive Power BI dashboard** designed to analyze **student academic performance, attendance, and behavioral patterns** across grades, subjects, and terms. It demonstrates strong skills in **data modeling, DAX, visualization, and storytelling**.


---

## 🎯 Project Objective
To build an interactive Power BI dashboard that:
- Evaluates academic performance across subjects and terms
- Tracks student attendance trends
- Analyzes behavioral incidents
- Enables drill-down analysis at the individual student level

---

## 📁 Dataset Used
The dashboard is built using the following datasets:

- **Students.xlsx**  
  `StudentID, Name, Gender, Class, Section`

- **Scores.xlsx**  
  `StudentID, Subject, ExamType, Score, MaxScore, Term`

- **Attendance.xlsx**  
  `StudentID, Date, Status (Present/Absent), Reason`

- **Behavior.xlsx**  
  `StudentID, Date, BehaviorType, Notes`

---

## 🧩 Data Modeling & Cleaning
- Loaded all datasets into Power BI
- Created relationships using **StudentID** as the key
- Cleaned column names and fixed data types
- Handled missing and null values appropriately

---

## 🧮 DAX Measures Created
Key calculated fields and measures include:
- **% Score** = Score / MaxScore
- **Average Score per Subject**
- **Attendance %**
- **Behavior Count per Type**
- **Performance Category** (High / Medium / Low using `SWITCH` or `IF`)

---

## 📊 Visualizations Included
The dashboard contains the following visuals:
- **Bar Chart:** Average scores by Subject and Class
- **Line Chart:** Performance trends by Term
- **Donut Chart:** Distribution of behavior types
- **Table:** Student-wise scores with conditional formatting
- **Card KPIs:** Total Students, Average Attendance, Average Score

---

## 🎛 Interactivity Features
- Slicers for **Class, Section, Subject, Term**
- **Drillthrough page** for individual student profiles
- **Tooltips** with mini charts and metrics
- **Bookmark navigation** to switch between Academic and Behavioral views

---

## 📱 Optional Enhancements
- Mobile layout optimized for Power BI Mobile App

---

## 📦 Deliverables
- **Student_Dashboard.pbix** — Power BI report file
- Optional documentation describing insights derived

---

## 🧠 Skills Demonstrated
- Power BI data modeling
- DAX calculations
- KPI design
- Interactive dashboard development
- Data storytelling & analysis

---

## ⭐ Final Note
This project is ideal for demonstrating **end-to-end Power BI dashboard development** and is suitable for **portfolio, academic, and interview preparation**.

Feedback and suggestions are welcome 🚀

