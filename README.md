# student-exam-analysis
🎓 Student Performance Analytics — Python + Power BI

This project analyzes student exam performance across Math, Reading, and Writing using Python (EDA) and visualizes insights through an interactive Power BI dashboard.

📂 Project Workflow
1. Data Cleaning & Preparation
Handled missing values

Standardized categorical values

Added new fields:

  .total_score (Math + Reading + Writing)

  .Target comparison measures

  .Study hour impact columns

📊 Exploratory Data Analysis (EDA)

Performed in Jupyter Notebook using:
✔ pandas
✔ numpy
✔ seaborn
✔ matplotlib

Key steps:

Score distribution analysis

Gender-wise score comparison

Parent education & income influence

Test preparation impact

Weekly study hours correlation

Outlier detection

Relationship heatmap

Notebook: student exam EDA.ipynb

📈 Power BI Dashboard
Dashboard Pages
🟣 1. Summary of Student Performance

Includes KPIs:

Total Math Score vs Target

Total Reading Score vs Target

Total Writing Score vs Target

Donut Chart: Parent Education Distribution

Clustered Column Chart: Avg score by Gender

Bar Chart: Sum of Math score by Gender

🔵 2. Impact Analysis

Avg Math/Reading/Writing scores by Test Preparation

Sum of MathScore by Number of Siblings

Score impact by Parent Marital Status

Influence of Sports Practice Frequency

🟡 3. Detailed Student Analysis

Interactive Table with:

Gender

Ethnic Group

Parent Education

Test Prep

Score breakdown (Math, Reading, Writing)

Total Score

Slicer for Gender filtering

🛠 Tools & Technologies

Python: Data Cleaning & EDA

Power BI: KPIs, DAX, Data Modeling & Visualization

Excel: Raw data

DAX: Custom measures & target KPIs

📌 Key Insights

Students completing TestPrep show highest improvement

Parent education level strongly correlates with performance

Regular sports practice positively affects scores

Weekly study hours impact Math & Reading significantly

Female students slightly outperform males in Reading & Writing

📤 Files Included

Power BI File: [student_performance.pbix](https://github.com/DK116-star/student-exam-analysis/blob/main/student%20exam%20performance.pbix)



Python EDA Notebook: [student exam EDA.ipynb](https://github.com/DK116-star/student-exam-analysis/blob/main/student%20exam%20EDA.ipynb)

Screenshots of dashboards
