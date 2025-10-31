🧠 Student Performance Analysis using Hive
📌 Project Overview

This project analyzes student academic performance using Apache Hive on a dataset containing marks in multiple subjects such as SQL, Excel, Python, Power BI, and English.
The goal is to derive meaningful insights about students’ performance patterns based on age, location, and subject proficiency.

🎯 Objectives

Identify top-performing students by total marks.

Calculate average marks by location and age group.

Find students scoring above 90 in all subjects.

Determine the most scoring subject overall.

Analyze subject-wise maximum and minimum performance.

⚙️ Technologies Used

Apache Hive – for querying and data analysis

Hadoop (HDFS) – for distributed data storage

Cloudera Environment – to run Hive commands

Python (optional) – for initial data cleaning

🧩 Dataset Description

The dataset (data_science_student_marks.csv) contains 497 records with the following columns:
student_id, location, age, sql_marks, excel_marks, python_marks, power_bi_marks, and english_marks.

Each record represents a student’s scores in data science–related subjects and demographic details.

📊 Insights

Python and Excel are the strongest subjects overall.

Students aged 22–25 perform slightly better than others.

Tokyo and London show the highest average scores.

Only a few students scored above 90 in all subjects.

English marks vary widely compared to technical subjects.

🏁 Conclusion

Hive efficiently handles and analyzes large datasets, offering quick insights through SQL-like queries.
This project demonstrates how big data tools can be used to evaluate academic trends and support data-driven educational improvements.
