# Python Data Cleaning Project

## 📌 Project Overview
This capstone project, part of the SkilloVilla Python Fundamentals course, applies data cleaning and manipulation techniques using Python, Pandas, and NumPy. It uses three related datasets (Project, Employee, and Seniority Level) to simulate a real-world project management scenario.

The work includes handling missing values, splitting and merging data, calculating bonuses, updating designation levels, and filtering records.

## 🎯 Objectives
- Create DataFrames and save them as CSV files
- Fill missing project costs using a running average
- Split the Name column into First Name and Last Name
- Merge all three DataFrames into one `Final` DataFrame
- Calculate a 5% bonus for finished projects
- Promote or demote designation levels based on project status and age
- Calculate the total project cost per employee
- Filter employees by city name
- 
## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Jupyter Notebook



- ## 📁 Dataset
- **Source:** Capstone Project – Python Fundamentals (SkilloVilla). Three tables (Project, Employee, Seniority Level) given in the project PDF and recreated manually as DataFrames, then saved as CSV files.
- **Size:** 
  - `project.csv` – 14 rows × 4 columns
  - `employee.csv` – 5 rows × 5 columns
  - `seniority.csv` – 5 rows × 2 columns
- The dataset is small, so it is included directly in this repository (no external download needed).

## 🧹 Data Cleaning Steps
1. Removed null and missing values
2. Handled duplicate records
3. Converted data types (for example, date and numeric columns)
4. Standardized column names
5. Filtered irrelevant data

## 📸 Project Preview
![Data cleaning preview](<img width="974" height="520" alt="Capture 2" src="https://github.com/user-attachments/assets/e21d8426-d04b-48fb-a77f-43ba4b3e6160" />
)

## 📈 Key Outcomes

- Created three DataFrames (Project, Employee, Seniority) and saved them as CSV files
- Filled 2 missing `Cost` values (Project 5 and Project 9) with the average cost of ₹1,744,333.33 using a `for` loop
- Split `Name` into `First Name` and `Last Name`
- Merged all three DataFrames into one `Final` DataFrame (14 rows)
- Added a `Bonus` column giving 5% of cost on finished projects
- Demoted designation level by 1 for failed projects and removed records above level 4
- Added "Mr."/"Mrs." titles to first names and dropped the `Gender` column
- Promoted designation level by 1 for employees older than 29
- Calculated total project cost per employee (`TotalProjCost`)
- Filtered employees whose city contains "o" (London and Newyork)
- Before cleaning: 14 rows, 2 nulls, 0 duplicates. After cleaning: 14 rows, 0 nulls, 0 duplicates.

## 🚀 Future Improvements
- Automate the cleaning pipeline
- Add data validation checks
- Integrate with visualization tools

## 👨‍💻 Author
**Lonali Ray**
[LinkedIn](https://www.linkedin.com/in/lonali-ray-48786b233/?isSelfProfile=true) | [GitHub](https://github.com/LonaliRay)
