# Student-Performance-Analyzer

PROBLEM STATEMENT:
    Educational institutions often lack simple, explainable systems to quickly identify students who are academically at risk. Existing systems may rely on raw scores without actionable insights.
This project addresses that gap by building a transparent, rule-based evaluation system that not only assesses performance but also explains why a student is underperforming and how they can improve.

PROJECT GOAL:
To design and implement a data-driven, rule-based system that evaluates student academic performance using key parameters and provides explainable insights to identify at-risk students and suggest improvements.

PROJECT OBJECTIVES:

> To preprocess and analyze student academic data
> To design a custom rule-based scoring mechanism for performance evaluation
> To classify students into performance risk categories
> To generate human-readable insights and recommendations
> To visualize overall performance distribution


# Dataset Description:

| Column Name           | Description                            |
| --------------------- | -------------------------------------- |
| student_id            | Unique student identifier              |
| attendance_percentage | Attendance consistency                 |
| internal_marks        | Average of core theory subject scores  |
| assignment_score      | Practical/assignment performance score |

# Technology Stack:

* Programming Language: Python
* Libraries: Pandas, NumPy, Matplotlib
* Data Format: CSV
* Tools: VS Code, GitHub

# System Architecture:
Student Data (CSV)
        ↓
Data Preprocessing
        ↓
Rule-Based Scoring Logic
        ↓
Risk Classification
        ↓
Insight & Recommendation Engine
        ↓
Visualization & Output

# Performance Evaluation Logic: 
Each student is evaluated using a weighted scoring mechanism

* Attendance: 30%
* Internal Marks: 40%
* Assignment Score: 30%

# Risk Categories:
* Low Risk: Score ≥ 75
* Medium Risk: 50 ≤ Score < 75
* High Risk: Score < 50

# Insight Generation:
For each student, the system identifies weak performance factors and generates:

* Reason for underperformance
* Suggested improvement areas

# Visualization:
The project includes visual representations of

* Distribution of students across risk categories
* Overall academic performance trends

# Project Structure:

student-performance-system/
│
├── data/
│   └── student_performance_dataset.csv
│
├── src/
│   ├── load_data.py
│   ├── performance_logic.py
│   ├── insights.py
│   └── visualization.py
│
├── README.md
└── requirements.txt

# Future Enhancements:

* Integrating machine learning-based predictions
* Adding a web-based dashboard
* Automating data ingestion
* Adaptive scoring mechanisms


