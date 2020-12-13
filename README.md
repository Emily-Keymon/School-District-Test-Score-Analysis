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
1.  Created data series of scores by grade levels using conditionals (9th, 10th, 11th, 12th).
2.  Grouped each school by name.
3.  Combined 9th, 10th, 11th and 12th into single dataframe.
4.  Output calculated values to the math scores data frame.

## Reading scores by grade analysis
1.  Created data series of scores by grade levels using conditionals (9th, 10th, 11th, 12th).
2.  Grouped each school by name.
3.  Combined 9th, 10th, 11th and 12th into single dataframe.
4.  Output calculated values to the math scores data frame.

## Scores by school spending analysis
1.  Set up bins for spending - <584, 585-629, 630-644, 645-675.
2.  Created a copy of school summary since it contains "Per Student Budget" data.
3.  Categorized spending based on bins.
4.  Calculated the average math test score for all students in the schools within each spending range.
5.  Calculated the average reading test score for all students in the schools within each spending range.
6.  Calculated the percentage of all students in the schools within each spending range that have a passing math test score.
7.  Calculated the percentage of all students in the schools within each spending range that have a passing reading test score.
8.  Calculated the overall percentage of students in the schools within each spending range that are passing math and reading.
9.  Output calculated values for each spending range to the per student budget summary data frame.

## Scores by school size analysis
1.  Set up bins for school size - Small (<1000), Medium (1000-2000), Large (2000-5000).
2.  Created a copy of school summary since it contains "Per Student Budget" data.
3.  Categorized size based on bins.
4.  Calculated the average math test score for all students in the schools within each size range.
5.  Calculated the average reading test score for all students in the schools within each size range.
6.  Calculated the percentage of all students in the schools within each size range that have a passing math test score.
7.  Calculated the percentage of all students in the schools within each size range that have a passing reading test score.
8.  Calculated the overall percentage of students in the schools within each size range that are passing math and reading.
9.  Output calculated values for each size range to the per student budget summary data frame.

## Scores by school type analysis
1.  Created a copy of school summary since it contains "Per Student Budget" data.
2.  Calculated the average math test score for all students in the schools within each type category.
3.  Calculated the average reading test score for all students in the schools within each type category.
4.  Calculated the percentage of all students in the schools within each type category that have a passing math test score.
5.  Calculated the percentage of all students in the schools within each type category that have a passing reading test score.
6.  Calculated the overall percentage of students in the schools within each type category that are passing both math and reading.
7.  Output calculated values for each type category to the school type summary data frame. 

---
## Results
Observable trends based on data:
* The top 5 performing schools are all charter schools and the bottom 5 are all district schools.
* Spending had little to no effect on overall passing %.
* Large schools had lower reading and maths scores. Also, large schools had a significantly lower overall passing %.
* In all cities, the average reading scores are higher than the average math scores.

## District summary
![district_summary](https://user-images.githubusercontent.com/64673015/102021750-a8dd9b80-3d47-11eb-907d-706cd77f3810.PNG)

## School summary
![school_summary](https://user-images.githubusercontent.com/64673015/102021756-ba26a800-3d47-11eb-84a2-9dbb49aad013.PNG)

## Top 5 performing schools
![top_schools](https://user-images.githubusercontent.com/64673015/102021795-1be71200-3d48-11eb-9754-5f4c55663eb3.PNG)

## Bottom 5 performing schools
![bottom_schools](https://user-images.githubusercontent.com/64673015/102021809-31f4d280-3d48-11eb-84cb-235e9226c1b9.PNG)

## Math scores by grade
![math_scores_by_grade](https://user-images.githubusercontent.com/64673015/102021821-45a03900-3d48-11eb-8e68-5d2be3914ef8.PNG)

## Reading scores by grade
![reading_scores_by_grade](https://user-images.githubusercontent.com/64673015/102021833-551f8200-3d48-11eb-91df-5a4aecb2c5ee.PNG)

## Scores by school spending
![scores_by_school_spending](https://user-images.githubusercontent.com/64673015/102021850-69637f00-3d48-11eb-9006-978b4b289e01.PNG)

## Scores by school spending by range
![scores_by_school_spending_bins](https://user-images.githubusercontent.com/64673015/102021871-87c97a80-3d48-11eb-8537-5b12b5edcee4.PNG)

## Scores by school size
![scores_by_school_size](https://user-images.githubusercontent.com/64673015/102021878-9adc4a80-3d48-11eb-9537-f3e5ce5992d0.PNG)

## Scores by school size by range
![scores_by_school_size_bins](https://user-images.githubusercontent.com/64673015/102021885-af204780-3d48-11eb-9b07-0e3d93696516.PNG)

## Scores by school type
![scores_by_school_type](https://user-images.githubusercontent.com/64673015/102021899-cf500680-3d48-11eb-9f35-960603f32c34.PNG)


















