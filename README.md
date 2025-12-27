# Student Performance and Attendance Analysis

 Project Overview
This project focuses on analyzing student performance and attendance data using Python.  
The main goal is to understand how attendance and different assessments contribute to overall student performance and to present insights in a clear, visual manner.

The project is designed as a beginner-friendly, end-to-end analysis that covers data cleaning, calculations, classification, and visualization.

---

 Objectives
- Analyze student attendance and academic performance
- Calculate attendance percentage for each student
- Compute a weighted performance score using multiple assessments
- Classify students into performance categories
- Identify students with low attendance and top performers
- Present insights using clear and meaningful charts

---

 Dataset Description
The dataset is provided in Excel format and includes:
- Student names
- Daily attendance records
- Marks from:
  - Mini Test 1
  - Mini Test 2
  - Live Test
  - Assignment

The attendance data is converted into numerical form to calculate attendance percentages accurately.

---

 Analysis Workflow
1. Data loading and inspection  
2. Data cleaning (handling missing and invalid values)  
3. Attendance percentage calculation  
4. Weighted percentage calculation  
5. Performance classification  
6. Visualization and insight generation  

---

 Weighted Percentage Logic
The final performance score is calculated using the following weights:

- Attendance: 40%
- Mini Test 1: 10%
- Mini Test 2: 10%
- Live Test: 20%
- Assignment: 20%

This weighted score is used for all further analysis and classification.

---

 Performance Classification
Students are classified into four categories based on weighted percentage:

- Excellent: ≥ 85%
- Good: 71% – 84%
- Average: 50% – 70%
- Needs Improvement: < 50%

---

 Charts and Visualizations

# 1. Attendance Percentage Bar Chart
- Displays attendance percentage for each student
- Helps quickly identify students with low attendance
- Useful for monitoring attendance compliance

Insight:  
Students with consistently low attendance can be easily spotted and flagged for intervention.

---

# 2. Students with Attendance Below 50%
- Highlights only students whose attendance is below 50%
- Makes critical attendance issues visible at a glance

Insight:  
Low attendance strongly correlates with weaker academic performance.

---

# 3. Performance Category Distribution (Pie Chart)
- Shows the proportion of students in each performance category
- Helps understand overall class performance distribution

Insight:  
Most students fall into Average and Good categories, with fewer students at the extremes.

---

# 4. Assessment Score Comparison (Box Plot)
- Compares score distribution across:
  - Mini Test 1
  - Mini Test 2
  - Live Test
  - Assignment
- Helps identify variability and outliers in assessments

Insight:  
Some assessments show higher variability, indicating differences in student preparedness.

---

# 5. Top Performers Visualization
- Highlights top-performing students based on weighted percentage
- Useful for recognizing academic excellence

Insight:  
Top performers generally maintain both strong attendance and consistent assessment scores.

---

 Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Microsoft Excel

---

 How to Run the Project
1. Clone or download the repository
2. Ensure the Excel dataset is in the same directory as the notebook
3. Open the Jupyter Notebook file
4. Run cells sequentially from top to bottom

---

 Key Insights Summary
- Attendance has a significant impact on overall performance
- Consistent attendance often leads to higher weighted scores
- A small group of students consistently outperforms the class average
- Visual analysis makes performance gaps easier to identify

---

 Conclusion
This project demonstrates a complete data analysis workflow using Python, from raw data to actionable insights.  
It reflects a practical approach to academic performance evaluation and provides a strong foundation for further analytical projects.

---

 Author
Heramba Kakati
