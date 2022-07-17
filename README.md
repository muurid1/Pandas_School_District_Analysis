# Pandas_School_District_Analysis

## Project Overview
In this project, we are going to analyse data from fifteen schools by replacing the score for reading and math for the ninth graders at Thomas High School, using the loc method with conditional statements and comparison  or logical operators. A report will be written to describe the method used to replace the reading and math scores and how they affected the school district analysis.
We will be analysing these following, after replacing the score using the loc method:
 1) The district summary
 2) The school summary
 3) The top five and bottom five performing schools, based on the overall passing rate.
 4) The average math score for each grade level from each school.
 5) The average reading score for each grade level from each school.
 6) The scores by school spending per student, by school size, and by school type.


## Purpose of this analysis
The main purpose of this challenge is to help Maria analyse the data for ninth graders at Thomas High School because some academic dishonesty was discovered.

## Resources

Software:

 • Python

 • Jupyter Lab

 • Terminal 

 • Pandas

 • Anaconda

Data Source:

[schools_complete.csv](https://github.com/muurid1/Pandas_School_District_Analysis/files/9127017/schools_complete.csv)


[students_complete.csv](https://github.com/muurid1/Pandas_School_District_Analysis/files/9127018/students_complete.csv)


## Results of the analysis

After analysing the data and replacing the scores for math and reading, Maria has discovered:

1) A change of the percentage of Math on the district summary and at Thomas High School
3) A change of the percentage of Reading at Thomas High School
4) The replacement of the data for the ninth graders in math and reading scores(replace with "NaN") has no impacts on the other schools as shown below.

<img width="678" alt="Screen Shot 2022-07-16 at 9 05 23 PM" src="https://user-images.githubusercontent.com/107282754/179384406-b106a27a-53ae-40ca-881a-6d7ddd47c5dd.png">
 
#### District Summary DataFrame

There is no change affecting the district summary dataframe.

<img width="1119" alt="Screen Shot 2022-07-16 at 9 47 32 PM" src="https://user-images.githubusercontent.com/107282754/179384589-efa98d42-343c-4cbc-9967-44f94c003e3a.png">

#### School Summary Dataframe

##### Thomas High School Metrics

<img width="1096" alt="Screen Shot 2022-07-17 at 12 43 44 AM" src="https://user-images.githubusercontent.com/107282754/179385618-88347e40-f643-419d-88b8-10cf8ea5b998.png">


The School Summary changes, since we are still using the total number of students in each school to calculate the percentage of students that pass math, reading, and "overall" at each school. The percentages will drop for Thomas High School knowing that a group of students will have "Nan" as score  yet they will be included in the denominator of total students.

###### Ninth grade math score before and after removing Thomas High School 9th grade scores
 
<img width="317" alt="ninthgradebefore" src="https://user-images.githubusercontent.com/107282754/179385076-c38cd76c-6623-4dd7-9bdc-df7a40435335.png">
<img width="310" alt="ninthgradeafter" src="https://user-images.githubusercontent.com/107282754/179385080-4d27f10d-aa82-4f21-9295-455bf42f05b7.png">

###### Ninth grade reading score before and after removing Thomas High School 9th grade scores

<img width="310" alt="ninthgradereadingbefore" src="https://user-images.githubusercontent.com/107282754/179385122-3addfa37-6cbd-47d4-8814-5125e1e09c72.png">

<img width="319" alt="ninthgradereadingafter" src="https://user-images.githubusercontent.com/107282754/179385130-3d20c26c-ed89-4e51-9147-2e2aafd5e9f8.png">

###### Top 5 schools

<img width="834" alt="top5schools" src="https://user-images.githubusercontent.com/107282754/179386585-dd80dce6-9b0d-4110-be80-084b4ccc40ff.png">


###### Bottom 5 schools

<img width="824" alt="bottom5schools" src="https://user-images.githubusercontent.com/107282754/179385878-a7281f41-d90a-4de7-98c1-765f71850a97.png">

###### Scores by School Spending

<img width="774" alt="scorebyschoolspending" src="https://user-images.githubusercontent.com/107282754/179386036-ca1e863d-37d4-4329-9d2b-4040087ec8ea.png">

###### Scores by School type

<img width="809" alt="Screen Shot 2022-07-17 at 1 02 13 AM" src="https://user-images.githubusercontent.com/107282754/179386115-bfbd4006-4db5-4dc4-b984-e569b228c361.png">

###### Scores by School size

<img width="762" alt="Screen Shot 2022-07-17 at 1 04 32 AM" src="https://user-images.githubusercontent.com/107282754/179386171-759ddf47-9fc5-4d2c-b7bf-f9d818c351d0.png">


## Summary 

- Over all replacing the math and reading scores by "NaN" has  removed Thomas High School from the top 5 (because its percentge has dropped) on list for the district and did not affect the others schools grade. 

- It has also change the percentage of Math on the district summary and at Thomas High School as well as its Reading scores.


