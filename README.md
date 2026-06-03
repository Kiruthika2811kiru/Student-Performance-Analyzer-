Student Performance Analyzer
Overview
The Student Performance Analyzer is a Python-based data analysis project developed to analyze student academic performance and attendance records. The project demonstrates a complete data analysis workflow, including data generation, data cleaning, data validation, performance analysis, report generation, and insight extraction.
The primary goal of this project is to identify data quality issues, evaluate student performance, classify students based on academic results, and flag students who may require additional attention due to low attendance.
Project Objectives
* Generate a realistic student dataset containing marks and attendance information.
* Identify and handle missing, invalid, and inconsistent data.
* Calculate student totals, averages, grades, and academic status.
* Generate useful class-level insights.
* Export the final cleaned report for further analysis.

Dataset Information

The dataset contains the following fields:

* Student Name
* Mathematics Marks
* Science Marks
* English Marks
* History Marks
* Computer Science Marks
* Attendance Percentage

The dataset intentionally includes data quality issues such as:

* Missing values
* Invalid marks
* Attendance values greater than 100%
* Formatting inconsistencies in names

These issues simulate real-world datasets that often require cleaning before analysis.

Technologies Used

* Python
* Pandas
* NumPy

Project Workflow

1. Data Generation

   * Created a sample student dataset using NumPy.
   * Added realistic data quality issues intentionally.

2. Data Inspection

   * Loaded the dataset using Pandas.
   * Checked dataset dimensions, missing values, data types, and summary statistics.

3. Data Cleaning

   * Removed unnecessary whitespace from names.
   * Standardized name formatting.
   * Replaced impossible attendance values with missing values.
   * Replaced invalid marks with missing values.
   * Filled missing values using median imputation.

4. Data Analysis

   * Calculated total marks for each student.
   * Calculated average marks.
   * Assigned grades based on performance.
   * Identified students who are at risk due to low attendance.

5. Report Generation

   * Generated class-level statistics.
   * Identified the top-performing student.
   * Determined the weakest-performing subject.
   * Exported the final report as a CSV file.

Features

* Automatic data cleaning and validation
* Grade assignment system
* Student performance analysis
* Attendance-based risk detection
* Class summary generation
* CSV report export

Sample Insights Generated

* Class Average
* Pass Rate
* Number of At-Risk Students
* Top Scorer
* Weakest Subject

Learning Outcomes

Through this project, I gained practical experience in:

* Data Cleaning
* Data Validation
* Exploratory Data Analysis
* Pandas DataFrames
* NumPy Operations
* Statistical Analysis
* Report Generation
* Real-world Data Handling

Future Improvements

* Data visualization using Matplotlib and Seaborn
* Interactive dashboard development
* Subject-wise performance analysis
* Student ranking system
* Automated PDF report generation

Conclusion

This project demonstrates the complete workflow of a beginner-level Data Science project, from handling raw and messy data to generating meaningful insights. It highlights the importance of data cleaning, analysis, and reporting in making informed educational decisions.
