# Pandas Project - Analysing District School Board Data and Results 
In this project, I have created and manipulated Pandas DataFrames to analyze school and test scores data.


## Background

As a Chief Data Scientist for the city's school district, am helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, have analyzed the district-wide standardized test results based on  every student's math and reading scores, as well as various information on the schools they attend. Data has been aggregated to showcase trends in school performance.

## Summary and some trends are as follows
The district school board has 39,170 students across 15 schools with a total budget of $$24,649,428.00. Results show that the overall passing percentage in standardised tests is 65% of which individually, 85% of students passed in Reading, but only 75% passed in Mathematics. It can be concluded that mathematics is a subject in which students score meaningfully lower than reading. Either the testing standards are too high for this subject or the level of academic support required is not meeting student needs.  

Per student budget for each of the 15 schools is not highly variable and ranges from $578 to $655. 

Charter schools were amongst the top 5 schools in terms of overall passing percentage which exceeded 90% for top 5 of these schools. While all the schools with worst academic performance were District type schools with higher students per school.    

Most schools display the same passing percentages across that school for both subjects individually across grades 9th to 12th. 

Based on the reports created below, we can observe some trends like:
    -- Size of the school seems to be correlated to overall passing percentages after the 2000 students per school threshold, as passing percentage really drops meaningfully for these schools.
     
    -- Per student budget doesnt have the required effect on eductional results, we can see that the schools with the highest per student spending had the lowest pass percentages, even as this relation is not meaningful for the remaining categories as schools with lowest per student spend seem to perform better in academics. This observation cannot be fully conclusive without additional data on which schools focus more or acdemics or extra-curriculars etc.  
    
    -- It is quite clear that the Charter type schools have much higher pass percentages and a better overall academic record. 
    
    
### District Summary

Created a high-level snapshot, in a DataFrame, of the district's key metrics, including the following:

* Total schools
* Total students
* Total budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### School Summary

Created a DataFrame that summarizes key metrics about each school, including the following:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Highest-Performing Schools (by % Overall Passing)

Created a DataFrame that highlights the top 5 performing schools based on % Overall Passing. Includes the following metrics:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)


### Lowest-Performing Schools (by % Overall Passing)

Created a DataFrame that highlights the bottom 5 performing schools based on % Overall Passing. Includes the following metrics:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Math Scores by Grade

Create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Reading Scores by Grade

Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Scores by School Spending

Created a table that breaks down school performance based on average spending ranges (per student). Resultant metrics in the table:

* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Scores by School Size

Created a table that breaks down school performance based on school size (small, medium, or large).
### Scores by School Type

Created a table that breaks down school performance based on type of school (district or charter).


## References

Data generated by Mockaroo, LLC. (2021) Realistic Data Generator. [https://www.mockaroo.com/](https://mockaroo.com/). Modified by Trilogy Education Services, LLC.

- - -

© 2022 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.

