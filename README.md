# School_District_Analysis_Challenge

Working with Anaconda, Pandas and Jupyter

# Overview of the school district analysis: 

## Purpose.
This analysis a python-pandas evaluation of courses and grades in schools, where the presented data can help understand if spending and budgeting were contributary factors in aiding schools and/or students improve performance. This data is designed to help the school board in the district set priorities and make strategic decisions as to where and how funds and resources can be allocated to schools moving forward.

## Resources
Pandas & NumPy libraries Jupyter Notebook (Python Data environment created using Python 3.10 and Anaconda)
This project utilized two datasets in csv format, 1. schools_complete.csv file which includes the following information’s in columns Student ID, school name, type, size, budget and 2. students_complete.csv file which includes the following information in columns Student ID, student_ name, gender, grade, school name, reading and math scores. In the analysis both datasets are imported, merged and the data is displayed in to python pandas data frame. The project is conducted in Jupyter notebook to view the report.

## Analysis
The grades of the ninth graders at Thomas High School have been changed. While administrators do not know the full extent of this academic dishonesty, they want to uphold the standards of state testing and have turned to you for help.
Actions requested to be performed
•	Replace the 9th grade math and reading scores from Thomas High School.
•	Keep all other data associated with the 9th grade students and Thomas High School intact.
•	Compare data obtained with original dataset

### How is District Summary affected?
When the Thomas High School 9th grade reading and math scores are removed from the data we see the following impact-
1.	It did not affect the total students in the school district
2.	The average math score for the district decreases from 79.0 to 78.9
3.	The average reading score remains the same (81.9). 
4.	The percentage of students passing math, reading, and both (overall) is reduced by approximately 1% because there are 461 ninth grade students at Thomas High School, which is about 1.1% of the total 39,170 students in the district.

### District Summary prior to removing Thomas High School 9th grade scores
 
### District Summary after removing Thomas High School 9th grade scores
 
### How is School Summary affected?

The School Summary data changes for Thomas High School it originally started with a 91% overall passing rate, landing a spot in top 5 schools. After eliminating the 9th graders scores and calculating the total number of 10th - 12th grade students as the new denominator, the rest of the testing data was adjusted accordingly. 
- Average Math at Thomas decreased from 83.42 to 83.35.
- Average Reading at Thomas increased from 83.84 to 83.89.
- Average Percent Passing Math at Thomas decreased from 93.3% to 66.9%.
- Percent Passing Reading at Thomas decreased from 97.3% to 69.7%.
- Average Percent Overall passing both Math and Reading decreased from 90.9% to 65.1%

### How is Thomas High School’s performance affected when 9th grade scores are removed?

The original data set landed Thomas High School a Top 5 schools spot in the district with an overall passing percentage of 90.9. When the 9th grade scores are removed from the data, Thomas High School rank drops to the 8th position as now it has an overall passing percentage of 60.1.
Top 5 Schools prior to removing Thomas High School 9th grade scores
 
Top 10 Schools after removing Thomas High School 9th grade scores
 
## How does replacing the ninth-grade scores affect the following:


## Math & Reading scores by grade
In the original analysis, Thomas High School had 83.6 math average and 83.7 reading average for the 9th grade tests. Now the scores have been replaced with as NaN

### Math Scores - 9th grade for Thomas High School
Before removing on Left; After removing on Right
   
### Reading Scores -9th grade scores for Thomas High School
Before removing on Left; After removing on Right



## Scores by school spending
Thomas High School is a charter school and falls in the $630-$644/student spending range bin. Thomas High School’s per student budget is $638. The average math & reading scores stayed the same but the total number of students included the 9th graders with no scores, the percentage of students passing math, reading, and overall passing % dropped.

### School Spending 
1.	Before removing 9th grade scores at Thomas High School
 
2.	After removing 9th grade scores at Thomas High School



## Scores by school size
Thomas High School has a total student population size of 1,635 so it is categorized in the Medium School Size. Here we see a decrease of approximately 6 points in the percentage of students passing math, reading, and overall passing %.

### School Size 
1.	Before removing 9th grade scores at Thomas High School  

2.	After removing 9th grade scores at Thomas High School  



## Scores by school type
Thomas High School is a Charter School and there is a drop in the percentage of students passing math, reading, and overall passing %.

### School Type 
### 1. Before removing 9th grade scores at Thomas High School  
![image](https://user-images.githubusercontent.com/96351897/151655047-6e019bd0-8082-4a4c-86af-2842673e79c3.png)


### 2. After removing 9th grade scores at Thomas High School  
![image](https://user-images.githubusercontent.com/96351897/151655043-c8b1b78c-b78b-455d-85a3-308cff0e2901.png)



## Summary: 
1.	The overall passing rate for Thomas High School changed from 91% to 65%.
2.	Thomas High School's ranking dropped from 2nd to 8th in the district of 15 campuses.
3.	 Math and reading scores for 9th grade students will have Nan in their data set for Thomas High School
4.	The overall passing rate, math and reading scores are all modified as a result of Nan values for 9th grade students at Thomas High School.
5.	Drops in the overall passing % for Thomas High School could impacts their funding in future from the district and may be beneficial to allocate math and reading resources for freshmen 9th graders.



