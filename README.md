# Student Performance Analysis

## Project Overview

This project analyzes student performance using various academic and personal factors. The analysis was performed using Python, Pandas, and Matplotlib to identify patterns and relationships affecting exam scores.

## Objectives

* Clean and preprocess the student dataset.
* Analyze student marks, attendance, and study hours.
* Identify relationships between different factors and exam scores.
* Create meaningful visualizations.
* Generate insights and recommendations based on the analysis.

## Dataset

The project uses the **Student Performance Factors** dataset.

The dataset contains **6,607 student records and 20 columns**, including:

* Hours Studied
* Attendance
* Previous Scores
* Parental Involvement
* Access to Resources
* Motivation Level
* Tutoring Sessions
* Sleep Hours
* Physical Activity
* Exam Score
* Other student-related factors

## Technologies Used

* Python
* Pandas
* Matplotlib
* Jupyter Notebook
* Excel

## Data Preprocessing

The following preprocessing steps were performed:

* Checked the dataset structure.
* Checked for missing values.
* Checked for duplicate records.
* Filled missing categorical values using the mode.
* Generated descriptive statistics.
* Saved the cleaned dataset separately.

## Analysis Performed

The project analyzed:

* Attendance vs Exam Score
* Hours Studied vs Exam Score
* Previous Scores vs Exam Score
* Motivation Level vs Average Exam Score
* Parental Involvement vs Average Exam Score
* Access to Resources vs Average Exam Score
* Attendance Groups vs Average Exam Score
* Study Hours Groups vs Average Exam Score
* Exam Score Distribution

## Key Findings

* Attendance showed the strongest relationship with Exam Score, with a correlation of approximately **0.581**.
* Hours Studied showed a positive relationship with Exam Score, with a correlation of approximately **0.445**.
* Previous Scores showed a weaker relationship with Exam Score, with a correlation of approximately **0.175**.
* Students with higher attendance generally had higher average exam scores.
* Students with more study hours generally achieved higher average exam scores.
* Access to resources and parental involvement showed smaller positive differences in average scores.

## Project Structure

```text
cognevance_studentPerformance
│
├── dataset
│   ├── student_performance_factors.csv
│   └── student_performance_cleaned.csv
│
├── notebooks
│   └── student_performance_analysis.ipynb
│
├── visualizations
│   ├── attendance_vs_exam_score.png
│   ├── hours_studied_vs_exam_score.png
│   ├── exam_score_distribution.png
│   ├── attendance_group_vs_exam_score.png
│   ├── study_hours_group_vs_exam_score.png
│   └── access_to_resources_vs_exam_score.png
│
├── report
│
└── README.md
```

## Recommendations

* Encourage regular attendance.
* Encourage consistent study habits.
* Provide students with adequate learning resources.
* Encourage parental academic support.
* Analyze multiple factors together when evaluating student performance.

## Conclusion

This project demonstrates how data analysis can be used to understand student performance and identify important patterns. The analysis indicates that attendance and study hours have notable positive relationships with exam scores.

The project helped in gaining practical experience with data cleaning, exploratory data analysis, visualization, and interpretation using Python.

**Note:** Correlation shows a relationship between variables but does not necessarily prove causation.
