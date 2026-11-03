Job Market Skill Analyzer
Project Overview
The Job Market Skill Analyzer is a Python project that explores the skills requested across data and analytics job postings. It stores job-posting information, allows users to add new postings, cleans and processes skill data, analyzes skill frequency, searches for jobs by skill, and exports structured records to a CSV file.

This project demonstrates how Python data structures and basic data-processing techniques can be used to turn unstructured skill text into useful insights about the job market.
Problem Statement
A recruitment analytics team needs a compact Python tool to analyze skills requested across job postings for data and analytics roles. Each posting contains a job ID, role, company, and a text field listing the required skills.

The project uses Python to manage these records, normalize skill text, identify frequently requested skills, and save cleaned data for further analysis.
Dataset
The notebook starts with a sample dataset containing five job postings:
Job ID	Role	Company	Skills
1	Data Analyst	ABC Corp	Excel, SQL, Python
2	Data Scientist	XyZ Ltd	Python, ML, Statistics
3	Business Analyst	DataWorks	Excel, SQL, PowerBI
4	Data Engineer	InfraTech	Python, SQL, Spark
5	ML Engineer	AI Labs	Python, ML, DeepLearning


New job postings can also be entered interactively while the notebook is running.
Project Features
1. Display job postings – Uses a for loop to print each job record in a readable format.
2. Add new job postings – Collects role, company, and skills from the user and automatically generates the next job ID.
3. Clean and normalize skills – Converts skill text to lowercase, replaces commas with spaces, and removes surrounding or extra whitespace where applied.
4. Extract and count skills – Splits skill strings into individual tokens and calculates how frequently skills appear.
5. Basic statistics and insights – Calculates the total number of job postings and unique skills, and examines job postings mentioning Python.
6. Search jobs by skill – Provides a function to search job records for a requested skill.
7. Filter roles using common skills – Uses Counter, filter(), and a lambda function to identify roles containing at least one skill that appears two or more times.
8. Find unique skills – Uses a Python set to remove duplicate skills and displays the results alphabetically.
9. Export cleaned data – Writes structured job records to job_skills.csv using Python's CSV module and exception handling.
Python Concepts Used
- Variables and data types
- Dictionaries and lists
- Sets and tuples
- for loops and conditional statements
- User input with input()
- Functions and return values
- String methods and text processing
- List comprehensions
- Lambda functions and filter()
- collections.Counter for frequency counting
- File handling with open()
- CSV file operations using the csv module
- Exception handling with try and except
Technologies and Tools
- Language: Python
- Environment: Jupyter Notebook / Google Colab
- Libraries: Python standard library (csv, collections.Counter)
No external Python packages are required for the operations shown in this notebook.
