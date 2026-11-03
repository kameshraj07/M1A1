# 📊 Job Market Skill Analyzer

### Python Data Structures Project

---

## 📌 Project Overview

The **Job Market Skill Analyzer** is a Python-based project designed to analyze the skills required for different job roles in the data and analytics industry.

This project helps organize job postings, add new job information, clean skill data, identify frequently requested skills, search for specific skills, and export the processed data into a CSV file.

The main objective is to understand how Python data structures can be used for real-world data analysis.

---

## 🎯 Project Objectives

- Store job posting information using Python dictionaries.
- Add new job postings dynamically.
- Clean and normalize skill data.
- Extract individual skills from job postings.
- Calculate the frequency of each skill.
- Identify unique skills.
- Search job postings based on specific skills.
- Filter job roles using common skills.
- Export cleaned data into a CSV file.

---

## 📂 Dataset Description

The project uses a sample dataset containing five job postings.

| Job ID | Job Role | Company |
|--------|----------|---------|
| 1 | Data Analyst | ABC Corp |
| 2 | Data Scientist | XyZ Ltd |
| 3 | Business Analyst | DataWorks |
| 4 | Data Engineer | InfraTech |
| 5 | ML Engineer | AI Labs |

### Skills Included

- Excel
- SQL
- Python
- Machine Learning
- Statistics
- PowerBI
- Spark
- DeepLearning

---

## ⚙️ Project Implementation

### 1. Display Job Postings
Used a `for` loop to display job details in a readable format.

### 2. Add New Job Postings
Collected job role, company name, and skills through user input.

Automatically generated new Job IDs.

### 3. Clean and Normalize Skills
Created a `clean_skills()` function to:
- Convert text into lowercase.
- Replace commas with spaces.
- Remove unnecessary surrounding spaces.

### 4. Skill Extraction and Frequency
- Extracted individual skills.
- Created a consolidated skill list.
- Counted the frequency of each skill.
- Identified the top five frequently requested skills.

### 5. Basic Statistics and Insights
Calculated:
- Total number of job postings.
- Number of unique skills.
- Job postings mentioning Python.

### 6. Skill Search Function
Created a `find_jobs_by_skill()` function to search job postings using a specific skill.

### 7. Lambda Filtering and List Comprehension
Used:
- Lambda functions
- `filter()`
- `Counter()`

Identified job roles containing at least one commonly requested skill.

### 8. Unique Skill Set
Used Python sets to remove duplicate skills and displayed unique skills alphabetically.

### 9. Save Data to CSV
Used Python's CSV module to export cleaned job records into:

`job_skills.csv`

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming language |
| Jupyter Notebook | Development environment |
| Dictionaries | Store job information |
| Lists | Manage job records and skills |
| Sets | Identify unique skills |
| Functions | Reusable operations |
| Lambda | Filtering operations |
| Counter | Skill frequency analysis |
| CSV | Export structured data |

---

## 🧠 Python Concepts Learned

- Variables and Data Types
- Lists and Dictionaries
- Sets and Tuples
- For Loops
- Conditional Statements
- Functions
- String Manipulation
- List Comprehension
- Lambda Functions
- Filter Functions
- Collections Counter
- File Handling
- Exception Handling

---

## 📈 Expected Project Output

The project generates:

1. Job posting details.
2. Updated job records.
3. Cleaned skill information.
4. Skill frequency counts.
5. Total job statistics.
6. Unique skill information.
7. Job search results.
8. Filtered job roles.
9. CSV output file.

---

## 🚀 How to Run the Project

1. Clone or download this repository.

2. Open the Jupyter Notebook file.

3. Run the notebook cells sequentially.

4. Enter job posting details when requested.

5. Search for skills such as Python, SQL, or Excel.

6. Run the CSV export section.

7. Check the generated `job_skills.csv` file.

---

## 📁 Project Structure

```text
Job-Market-Skill-Analyzer/
│
├── Assignment 1_PythonDataStructures.ipynb
├── job_skills.csv
└── README.md
