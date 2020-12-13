# School District Test Score Analysis
The goal of this project was to analyze the standardized test results for a school district.  Using the math and reading scores, aggregate the data and showcase obvious trends in school performance.

---
## Datasets
* https://github.com/Emily-Keymon/School-District-Test-Score-Analysis/blob/master/PyCitySchools/schools_complete.csv
* https://github.com/Emily-Keymon/School-District-Test-Score-Analysis/blob/master/PyCitySchools/students_complete.csv

---
## Tools Used
* Jupyter Notebook
* Python - Pandas

---
## Tasks
### Data exploration
1.  Imported school data and student data .csv files as individual dataframes.
2.  Merged the individual dataframes into a combined dataframe based on school name.

## District summary analysis
1.  Calculated total number of schools in the district.
2.  Calculated the total number of students in the district.
3.  Calculated the total budget for the schools.
4.  Calculated the average math test score of students.
5.  Calculated the average reading test score of students.
6.  Calculated the percentage of students that had a passing math score.
7.  Calculated the percentage of students that had a passing reading score.
8.  Calculated the overall percentage of students that had a passing math and reading score.
9.  Output calculated values to a district summary dataframe.

## School summary analysis
1.  Determined school types using school data to create a dataframe.
2.  Calculated total student count per school.
3.  Calculated total school budget and per capita spending per school.
4.  Calculated average test scores for reading per school.
5.  Calculated average test scores for math per school.
6.  Calculated the percentage of all students in each school that have a passing math test score.
7.  Calculate the percentage of all students in each school that have a passing reading test score.
8.  Calculated overall percentage of students in each school that are passing either the math and reading tests.
9.  Output calculated values to a school summary dataframe.

## Top performing schools analysis
1.  Sorted school summary data frame by best overall passing percentage.
2.  Output summary data for top five performing schools in the top performing schools data frame.

## Bottom performing schools analysis
1.  Sorted school summary data frame by worst overall passing percentage.
2.  Output summary data for top bottom performing schools in the top performing schools data frame.  

## Math scores by grade analysis
1.  
 

---
## Results
Observable trends based on data:
* The top 5 performing schools are all charter schools and the bottom 5 are all district schools.
* Spending had little to no effect on overall passing %.
* Large schools had lower reading and maths scores. Also, large schools had a significantly lower overall passing %.
* In all cities, the average reading scores are higher than the average math scores.¶



### School Summary

* Create an overview table that summarizes key metrics about each school, including:
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)

### Top Performing Schools (By % Overall Passing)

* Create a table that highlights the top 5 performing schools based on % Overall Passing. Include:
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)

### Bottom Performing Schools (By % Overall Passing)

* Create a table that highlights the bottom 5 performing schools based on % Overall Passing. Include all of the same metrics as above.

### Math Scores by Grade\*\*

* Create a table that lists the average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Reading Scores by Grade

* Create a table that lists the average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Scores by School Spending

* Create a table that breaks down school performances based on average Spending Ranges (Per Student). Use 4 reasonable bins to group school spending. Include in the table each of the following:
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)

### Scores by School Size

* Repeat the above breakdown, but this time group schools based on a reasonable approximation of school size (Small, Medium, Large).

### Scores by School Type

* Repeat the above breakdown, but this time group schools based on school type (Charter vs. District).



