# School-Data-Analysis-with-Anaconda
Perform analysis of school district data using Anaconda and Python

## Overview of the School District Analysis

**To perform this project, we used Python to code the analysis we want to perform. In addition to used two open-source packages within Python called Pandas and Numpy. Finally we used the computational noebook Jupyter Notebook to write, edit and manipulate our code for Python.** 

In this project, we were provided with two data sets and asked to perform analysis on a School District and then on a per School Level. This first data set contained data on fifteen (15) schools. The second data sat contained data on approximately thirty nine thousand students (~39,000) on an individual level. Using the two data sets, we prepared several DataFrames and performed anlaysis to provide summary data on the District Level and then on each individual School Level. After our analysis was done, we were notified that the data provided to us could have been compromised. As a result we had to separate 9th Grade Math and Reading Scores for Thomas High School and reperform our anlaysis. 

We have summerized the changes to our results due to this change below. 

## Results of our changes to Thomas High School

### District Level 
On a district level, we have included two screenshots: Summary Datab before and after replacing Thomas High School 9th School Grades. The screenshots are included below. 

**District Level Summary before replacing Thomas High School 9h Grade Marks**
![](https://github.com/shahkibria/School-Data-Analysis-with-Anaconda/blob/main/Resources/District%20Summary.png)
**District Level Summary after replacing Thomas High School 9h Grade Marks**
![](https://github.com/shahkibria/School-Data-Analysis-with-Anaconda/blob/main/Resources/District%20Summary%20-%20Edited.png)
 - There was no change in Total Students, Average Reading Scores and Total Budget. 
 - Average Math scores decreased from 79.0 to 78.9
 - % of students passing Math decreased from 75.0 to 74.8
 - % of students passing Reading decreased from 85.8 to 85.7
 - % of students passing both Math and Reading decreased from 65.2 to 64.9

### School Level 
On a school level, we first compared the performance of Thomas High School by replacing 9th Grade Math and Reading Scores with null values. The screenshots of our Panda output are included below: 

**Thomas High School Summary before replacing 9h Grade Marks**
![](https://github.com/shahkibria/School-Data-Analysis-with-Anaconda/blob/main/Resources/School%20Summary.png)
**Thomas High School Summary after replacing 9h Grade Marks with null values**
![](https://github.com/shahkibria/School-Data-Analysis-with-Anaconda/blob/main/Resources/School%20Summary%20without%20Thomas%209th.png)
 - There is no change in Total School Budget and Per School Budget. 
 - There is slight change in Average Math and Average Reading scores. Average Math Score decreased from 83.42 to 83.35 and Average Reading Score incrceaseed from 83.85 to 83.90.
 - There was significant changes in the percentages of students passing Math or Reading or both Math and Reading. % of Students passing Math decreased from 93.27 to 66.91 and % of students passing Reading decreased from 97.31 to 69.66. 
 - Overall passing percentage dropped from 90.95 to 65.08. 

This drop in percentages was expected since a full class was excluded from the passing population but was included in the population of total students. As a result, there was an artifical drop in percentages. In order to fix this, we reperformed our analysis by calculating percentages of students passing Math, Reading and Both of only 10th to 12th grades. We then compared the performance with the orginal data set. The results are included below:

**Thomas High School Summary with percentages only for students from 10th to 12th Grade**
![](https://github.com/shahkibria/School-Data-Analysis-with-Anaconda/blob/main/Resources/School%20Summary%20replacing%20Thomas.png)
 - There is no change in Total School Budget and Per School Budget. 
 - There is slight change in Average Math and Average Reading scores. Average Math Score decreased from 83.42 to 83.35 and Average Reading Score incrceaseed from 83.85 to 83.90.
 - There are only slight changes in percentages of students passing Math or Reading. Percentage of students passing Math decreased slightly from 93.27 to 93.18 and Percentage of students passing Reading decreased slightly from 97.31 to 97.02. 
 - The percentage of students passing both Math and Reading had a small increase from 90.95 to 90.63. 

## Analysis and Summary

 - In regards to average Math and Reading scores by grade, there was no impact on the averages for 10th to 12th grade for both Math and Reading. This was expected as we only excluded 9th Grade Data. 
 - In regards to Scores by School Spending, there was also no impact due to the change. This is also impacted as the total number of students and total budget for the school remained unchanged. 
 - Dropping the 9th grade for one school did not impact the averge math and reading scores and passing percentages for Chartered Schools. We believe the impact was not large enough to materially change the overall scores and passing grades of the whole district. Passing Percentages for Math, Reading and Both remained at 94, 97 and 90 respectively. 
 - Similarly the average scores and passing percentages for Small, Medium and Large schools (based on student population) remained unchanged. 




