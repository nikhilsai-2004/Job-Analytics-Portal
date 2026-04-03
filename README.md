# Job-Analytics-Portal

# 📊 Job Analytics Dashboard (Tableau Project)

## 🔹 Project Overview
This project focuses on analyzing job-related data using Tableau. The goal was to create multiple visualizations by applying specific conditions, filters, and calculated fields to extract meaningful insights from the dataset.

---

## 🔹 Tools Used
- Tableau Public  
- Excel Dataset  

## 🔹 Files Included 
- Tableau Workbook with .tub extension
- Project Report
- Index.html
- Read me file.
  
---

## 🔹 Tasks Implemented

### ✔ Task 1 – Bar Chart (Preference vs Work Type – Intern)
Developed a bar chart between Preference and Work Type with filters such as:
- Work Type = Intern
- Latitude < 10
- Country must not start with A, B, C, or D
- Job Title must be a single word
- Job Title length < 10 characters
- Company Size < 50,000
- Salary > $9,000
- Experience must be an even number
- Job Posting Date must be in odd-numbered months
- Chart is displayed only between 3 PM and 5 PM IST (time-based filter)
- Bars are sorted in descending order by count of job postings

---

### ✔ Task 2 – Scatter Plot (Company Size vs Company Name)
Developed a scatter plot between Company Size and Company Name with filters such as:
- Company Size < 50,000  
- Job Title = Mechanical Engineer  
- Experience > 5 years  
- Salary > $50,000  
- Work Type = Full-Time / Part-Time  
- Preference = Male  
- Job Portal = Idealist  
- Country in Asia excluding countries starting with “I”  
- Company Name must contain at least 2 vowels  

---

### ✔ Task 3 – Tree Map
Created a tree map to display top companies based on multiple conditions. Due to strict filtering, no records satisfied all conditions, resulting in a blank output.

---

### ✔ Task 4 – Drilldown Map
Developed a map visualization using latitude and longitude with drilldown functionality. Output is limited due to strict filtering conditions.

---

### ✔ Task 5 – Stacked Bar Chart (India vs Germany Comparison)
Developed a stacked bar chart comparing job postings between India and Germany with filters such as:
- Country = India and Germany
- Qualification = B.Tech
- Work Type = Full-Time
- Job Title = Data Scientist / Art Teacher / Aerospace Engineer
- Salary > $10,000
- Experience > 2 years
- Job Portal = Indeed
- Preference = Female
- Job Posting Date before 08/01/2023
- Location must not be blank
- Company Name length > 8 characters
- Chart is displayed only between 3 PM and 5 PM IST (time-based filter)
- India is represented in Orange and Germany in Green

---

### ✔ Task 6 – Box Plot (Salary Distribution)
Created a box-and-whisker plot to analyze salary distribution for Intern roles with several conditions such as:
- Latitude < 10  
- Country not starting with A, B, C, or D  
- Job Title constraints (single word and less than 10 characters)  
- Company Size < 50,000  
- Salary > $8,000  
- Even Experience  
- Contact Person contains “e”  
- Time-based condition implemented using parameter logic  

---

## 🔹 Features
- Interactive Dashboard  
- Multiple Filters and Conditions  
- Calculated Fields  
- Data Transformation and Analysis  

---

## 🔹 Live Dashboard
https://public.tableau.com/app/profile/nikhil.sai3719/viz/Book1_17707965414680/Job_Analytics_Portal_Dashboard?publish=yes 
---

## 🔹 Project Report
https://drive.google.com/file/d/1WX37xsntWhMZHpOjjBObDRCuNsqvxTCR/view?usp=drive_link
---

## 🔹 Notes
- The project uses strict filtering conditions; therefore, some visualizations may show limited or no data.
- Time-based conditions were implemented using calculated fields, and parameter-based logic was used to ensure correct visualization in Tableau Public.

---

## 🔹 Author
Lagisetty Nikhil Sai
