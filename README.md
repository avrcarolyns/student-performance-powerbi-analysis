# 🎓 Socioeconomic Factors in Student Academic Success (Power BI Analysis)

An interactive Power BI dashboard analyzing how socioeconomic disparities—such as family income, parental education, device access, and geographic region—impact student academic performance and pass rates across 100,000+ student records.

---

## 📊 Dashboard Preview

![Dashboard Preview](dashboard_preview.png)

---

## 💡 Key Business & Educational Insights
- **The Income Gap:** Students from high-income families achieve an **83.62% pass rate** and an average score of **65.50**, compared to **71.71%** and **59.13** for low-income students (a **+6.37 point score gap**).
- **Attendance Disparity:** High-income students maintain an average attendance rate of **87.33%**, which is **4.78% higher** than students in lower-income brackets.
- **Digital Divide:** Ownership of dedicated personal devices correlates with higher consistency in securing higher performance grades (Grade A & B) compared to shared devices.
- **Regional Disparity:** Variations between urban, suburban, and rural performance are relatively narrow when basic school facility standards are met.

---

## 🛠️ Tech Stack & Methods
- **Tool:** Power BI Desktop
- **DAX Measures:**
  - `Pass Rate` (dynamic percentage calculation)
  - `Income Score Gap` (variance between High and Low income groups)
  - `Attendance Disparity`
  - `Avg Exam Score`
- **Visuals Used:** Card (New) for executive KPIs, Combo Line & Clustered Column Chart, 100% Stacked Bar Chart, Conditional Formatting Heatmap Matrix, Interactive Tile Slicers.

---

## 📂 Project Structure
- `student_performance_socioeconomic_analysis.pbix` : Complete Power BI report file with DAX calculations and themes.
- `student_exam_performance.csv` : Raw dataset used for analysis. (https://www.kaggle.com/datasets/mobeenfatimah/student-exam-performance-and-success-dataset)
- `dashboard_preview.png` : High-resolution preview of the completed dashboard.

---

## 🚀 How to View the Report
1. Clone this repository or download the `.pbix` file.
2. Open the file in **Power BI Desktop** (free version).
3. Interact with the filters (Gender and Private Tuition) to explore demographic insights.
