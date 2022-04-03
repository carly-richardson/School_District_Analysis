# School_District_Analysis
Analyzing data on student funding and students' standardized test scores to provide insights on performance trends and patterns.

## Overview of the School District Analysis
1. A high-level snapshot of the district's key metrics, presented in a table format
2. An overview of the key metrics for each school, presented in a table format
3. Tables presenting each of the following metrics:
    - Top 5 and bottom 5 performing schools, based on the overall passing rate
    - The average math score received by students in each grade level at each school
    - The average reading score received by students in each grade level at each school
    - School performance based on the budget per student
    - School performance based on the school size 
    - School performance based on the type of school

## Resources
- Data Source: clean_students_complete.csv
- Software: Python 3.9.10, Jupyter Notebook 6.4.5

## School Distrtict Analysis Results
This is how the following metrics were affected by replacing the ninth-grade scores at Thomas High School:

- The district summary was not significantly impacted.
![image](https://user-images.githubusercontent.com/100643519/161439007-6d8519af-1406-4f4c-b004-59b1f2f7acd6.png)
![image](https://user-images.githubusercontent.com/100643519/161439021-7ee74764-1105-43c6-9571-611e7c80eec4.png)

- The school summary only changed for Thomas High School.
![image](https://user-images.githubusercontent.com/100643519/161439054-02e914ba-fa6c-4bd9-9c0d-798d688981b0.png)
![image](https://user-images.githubusercontent.com/100643519/161439080-090c1add-a98c-4577-9c48-68255f1fdf2a.png)

- Replacing the ninth graders' math and reading scores made Thomas High School's overall passing percentage go from 65.076453 to 90.630324. Thomas High School had the second highest overall passing percentage once the grades were replaced.

- Math and reading scores by grade remained the same for all schools except Thomas High School. The average scores were based on each school's average math and reading scores, so they were not impacted by changing the scores at Thomas High School. The average math and reading scores for 9th grade at Thomas High School are now "NaN".
![image](https://user-images.githubusercontent.com/100643519/161439134-b3eb4e57-15ea-4759-b6d6-57759a8b8f04.png)
![image](https://user-images.githubusercontent.com/100643519/161439146-cafc4ca5-ff2f-4950-bc25-9c238ce5d20e.png)

- Scores by school spending remained the same.
![image](https://user-images.githubusercontent.com/100643519/161439158-7318c59d-c29d-4949-b430-b7ae89720b9b.png)

- Scores by school size remained the same.
![image](https://user-images.githubusercontent.com/100643519/161439178-27d7fe2b-486a-4dd3-b73d-4463a6424f3e.png)

- Scores by school type remained the same.
![image](https://user-images.githubusercontent.com/100643519/161439192-beeb7718-9029-4e8f-934c-d9785efd8d2d.png)

## Summary
Removing the Thomas High School ninth graders' math and reading scores did not significantly impact the school district analysis. All the other schools' results remained the same, because they were based on their own students' performances. The total number of students and total budget remained the same. The student count was only changed to determine the district math and reading scores, because we were no longer using those students' test scores. That still did not significantly impact the analysis, because we only removed 461 out of 39,170 students.
