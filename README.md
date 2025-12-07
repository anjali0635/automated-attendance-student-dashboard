📊 Automated Attendance Student Dashboard — Power BI (CSV-Based)

This project is a Power BI dashboard designed to automate and visualize student attendance using CSV data files. It helps teachers, administrators, and academic teams track attendance patterns, identify low attendance students, and monitor overall class performance with interactive charts, KPIs, and filters.

🚀 Key Features

✔ Automated Attendance Insights

   Auto-calculated attendance percentage
   Daily, monthly & subject-wise attendance patterns
   Trend analysis using line charts
   Class-wise attendance distribution

✔ Interactive Power BI Dashboard

   Slicers for Class, Section, Subject & Date
   Drill-down charts
   Attendance status visualization (Present, Absent, Late)

KPIs for:

  Total students
  Average class attendance
  At-risk students (below threshold)

✔ CSV-Based Data Pipeline

   Attendance records stored in .csv format
   Easily refreshable dataset
   Suitable for large student datasets

📁 Project Files
Automated-Attendance-Dashboard/
│── attendance_data.csv
│── student_list.csv
│── subject_list.csv
│── attendance_dashboard.pbix
│── README.md

🧠 Power BI Transformations (Power Query)

The dashboard performs the following transformations:

 1.  Convert Status column to numeric flags (Present = 1, Absent = 0)
 2.  Add Attendance % = Present Days / Total Working Days
 3.  Merge student & attendance tables
 4.  Clean null or duplicate records
 5.  Create date hierarchy (Year, Month, Day)

📊 Dashboard Insights
✔ KPIs

 > Attendance %
 > Total Classes Conducted
 > Total Present Days
 > Students Below Required Attendance

✔ Visuals Used

 > Bar chart → Subject-wise attendance
 > Pie chart → Present vs Absent ratio
 > Line chart → Daily trend
 > Matrix → Student-wise attendance
 > Card visuals → Summary metrics


▶ How to Use the Dashboard

1. Open the file:

     attendance_dashboard.pbix


2. Load the dataset from CSV files

3. Click Refresh in Power BI to update attendance

4. Use filters/slicers to explore insights by:

   Class
   Student
   Subject
   Date


🔮 Future Enhancements

Integration with biometric/QR attendance system

Automated email alerts for low attendance

Power Automate flow for scheduled updates

AI-based prediction model for absenteeism

👩‍💻 Author

Anjali Gupta
BCA | Power BI Enthusiast | Dashboard Developer
