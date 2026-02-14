# Yaba-college-of-technology-synthetic-Project

### Project overview
It contains Students Admission-to-Graduation Analysis and Performance Dashboard for Yaba college of technology

## Project objectives
- To clean, transform, and analyze Student Admission and Graduation data
- To uncover insights on admission trends, student demographics, graduation rates, and academic performance
- To gain insight on the students outcome from the year 2017-2023
- The goal is to equip decision makers with clear insights for strategic academic and institutional growth.


  ### Tools used
  - Microsoft excel (for data cleaning)
  - Microsoft power point (for project presentation)
  - Power BI ( For visualization)

  ## Datasets Description
  The datasets conatains the synthetic historical data of the college
  
 # Admission Record
  - Student_ID
  - Admission_Year, Admission_Date
  - Department, Program
  - Entry_Mode, Entry_Score
  - Qualification_Submitted
  - Nationality, State_of_Origin, Local_Government_Area
  - Religion
  - Phone_Number,Address
  - Guardian_Name,Guardian_Phone
  - Previous_School
  - Scholarship_Status
  - Hostel_Requested
  - Admission_Batch

# Graduation Record
  - Student_ID
  - Full_Name
  - Gender
  - Date_of_Birth, Age_at_Graduation
  - Nationality, State_of_Origin
  - Admission_Year, Graduation_Year, Graduation_Date
  - Department, Faculty, Program
  - Final_CGPA, Class_of_Degree
  - Graduation_Status
  - Honors_or_Awards

### Data Cleaning process
  data cleaning was done using M.S excel power query
  - Removed all duplicates and blanks
  - Converted all columns to correct data types (dates, numbers, text)
  - Standardized text casing (e.g., "ND Computer Science" vs "Nd Computer science")
  - Handled missing values appropriately
  - Created calculated columns: Age_at_Admission, Study_Duration (Graduation_Year – Admission_Year)
  - Validated phone number formats
  - Merged both Admission and graduation datasets based on the unique number (Student_ID) for combined analysis

### Visualization
  - KPI on the total students admitted and graduated, Average CGPA performance, Graduation Rate %
  - Comparison of CGPA across all Fculties
  - Admission trend analysis
  - Graduation rate among all departments under each faculty
  - Slicer to filter the Admission years, departments, gender, scholarship status

## Key Findings
  - Admission status from (2017-2023) Admission Peaked in 2020, sharp drop in 2021, with the students UTME performance
  - 10,001 did not graduate, attributed to withdrawals, finances, personal issues, academic failure
  - 49% (implying more than half did not complete within the period), with reasons aligned to non‑completion factors
  - Breakdown shown CGPA on a 4.0 scale:
    
    3.50–4.00 (Distinction): 2,461 students
    
    3.00–3.49 (Upper Credit): 2,517 students 
  
    2.50–2.99 (Lower Credit): 2,427 students
  
    2.00–2.49 (Pass): 2,594 students
  
    <2.00 (Fail): 10,001 students
  - Graduation rates vary by department;
      Highest: ND Electrical/Electronics with  and 
      Lowest: HND Computer Science

## Recommendation
  - The report recommends boosting Yabatech’s ability to attract students by Enhancing the institution’s brand visibility,
    Showcasing alumni who have excelled in the industries or academia,
  - Introducing modern, in‑demand courses such as data analytics, web design, AI, and machine learning
  - To sustain Yabatech legacy as a leading institution, immediate investments in renovation and expansion is necessary. Upgrading of lecture halls, laboratories, and hostels      Renovating yabatech is not just buildings, but creating an environment that improves learning and meets the needs of our growing population.

## PROJECT FILES
#### Admission unstuctured datasets
- <a href = https://github.com/akinboteemmanuel10-ux/Yaba-college-of-technology-synthetic-data-analysis/upload/main>datasets</a>

### Graduation unstructured datasets
- <a href = https://github.com/akinboteemmanuel10-ux/Yaba-college-of-technology-synthetic-data-analysis/upload/main>datasets </a>

### Merged and cleaned Adimission & graduation datasets
- <a href = https://github.com/akinboteemmanuel10-ux/Yaba-college-of-technology-synthetic-data-analysis/blob/main/Yabatech%20data%20cleaning.xlsx> datasets </a> 


    

    
