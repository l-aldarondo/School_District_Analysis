# School_District_Analysis

## Background

Python School District Standardized Test Analysis

## Project Overview

The purpose of this project is to analyze a school district's standardized test and student funding to provide insight into performance trends and patterns. Due to the potentially dishonesty from one group of students, our client has requested to perform the analysis twice. One analysis included the entire set of data and the second analysis replaced or omitted  an specific grade scores. A complete assessment on implications and changes of replacing or omitting data is provided as part of this project.

## Resources

* Data source: students_complete.csv
* Software: Python 3.7.6, JupyterLab 3.4.3

## Schools Audit Results

### Analysis

* How is the district summary affected?

  * At the district level there was no major impact on the overall results when we removed the 9th grade scores from Thomas High School. When we compared Fig 1.1 and Fig 1.2, the overall passing percentage only changed by 0.1%. This could be because the grades for the ninth grade represent a small portion compared to the rest of the population in the district.

![Challenge_Distict_Summary](./Images/challenge_district_summary.png)

<sub>Figure 1.1 Challenge district symmary

![Pycity_District_Summary](./Images/Pycity_district_summary.png)

<sub>Figure 1.2 Original district summary

* How is the school summary affected?
  
  * Something similar happened when we compared the data per school in Fig 1.3 and Fig 1.4, there were no big changes on the results on the school summary DataFrame. The overall passing score for Thomas High School only changed by 0.32%.
  
![Challenge_Per_Schools_Summary](./Images/challenge_per_school_summary.png)

<sub>Figure 1.3 Challenge schools summary

![Pycity_Per_School_Summary](./Images/Pycity_per_school_summary.png)

<sub>Figure 1.4 Original school summary


* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  
  * When we compare Fig 1.5 - 1.8, the top 5 schools and the low 5 schools remain the same. Thomas High School remains in the 2nd position of the top 5 schools, before and after the change and the values remain almost the same. Therefore we can conclude that the change didn't affect THS in relation to the other schools.

![Challenge_Top_Schools](./Images/challenge_top_schools.png)

<sub>Figure 1.5 Challenge top schools

![Challene_Low_Schools](./Images/challenge_low_schools.png)

<sub>Figure 1.6 Challenge low schools

![Pycity_Top_Schools](./Images/Pycity_top_schools.png)

<sub>Figure 1.7 Original top schools

![Pycity_Low_Schools](./Images/Pycity_low_schools.png)

<sub>Figure 1.8 Original low schools


* How does replacing the ninth-grade scores affect the following:

* #### Math and reading scores by grade
  
    * Replacing the scores with n/a as shown in Fig 1.9 - 1.10, caused that the overall passing score for Thomas High School dropped to 65.1% (Fig 1.11). However when we recalculate the percentage of students who passed math, passed reading, and passed both math and reading for Thomas High School the school the overall passing rate was **90.63%** (Fig 1.12)

![Challenge_Math_Scores_by_Grade](./Images/challenge_math_score_by_grade.png)

<sub>Figure 1.9 Challenge math scores by grade

![Challenge_Reading_Scores_by_Grade](./Images/challenge_reading_score_by_grade.png)

<sub>Figure 1.10 Challenge reading scores by gade

![Pycity_Math_Scores_by_Grade](./Images/Pycity_math_score_by_grade.png)

<sub>Figure 1.11 Original math scores by grade

![Pycity_Reading_Scores_by_Grade](./Images/Pycity_reading_score_by_grade.png)

<sub>Figure 1.12 Original reading scores by grade


* #### Scores by school spending

  * Schools that spent less per student outperformed schools that spent more per student. As we can see in Fig 1.13 and 1.14, the schools that spended $646-665 per student had considerably lower scores compared to schools that spent <$586 which had the highest overall scores.

![Challenge_Scores_By_Spending](./Images/challenge_score_by_spending.png)

<sub>Figure 1.13 Challenge scores by spending

![Pycity_SCores_By_Spending](./Images/Pycity_score_by_spending.png)

<sub>Figure 1.14 Original scores by spending

* #### Scores by school size

  * Small and Medium size schools outperformed larger size schools in math scores, reading scores and in all % to include % Overall Passing. The larger schools percentage passing is very different and is pulling the overall passing percentage down for district schools. (Fig 1.15 - 1.16)

![Challenge_Scores_By_School_Size](./Images/challenge_score_by_school_size.png)

<sub>Figure 1.15 Challenge scores by school size

![Pycity_Scores_By_School_Size](./Images/Pycity_score_by_school_size.png)

<sub>Figure 1.16 Original scores by school size

* #### Scores by school type

  * Charter schools outperformed district schools in math scores, reading scores and in all % to include % Overall Passing. The percentage passing math is  very different and is pulling the overall passing percentage down for district schools.(Fig 1.17 -1.18)

![Challenge_Scores_By_School_Type](./Images/challenge_score_by_school_type.png)

<sub>Figure 1.17 Challenge scores by school type

![Pycity_Scores_By_School_Type](./Images/Pycity_score_by_school_type.png)

<sub>Figure 1.18 Original scores by school type

## Summary

* The overall district summary changed by **0.1%** for Thomas High school.

* The overall per school summary dropped by **0.32%** for Thomas High School.

* Replacing the scores with n/a caused that the overall passing score for Thomas High School dropped to 65%.. However when we recalculate the percentage of students who passed math, passed reading, and passed both math and reading for Thomas High School the school the overall passing rate was **90.63%**

* The replacement of the scores for Thomas High school had minimal effect on the school ranking. The school was dropped from the top 5 schools in the district. But when we recalculate the percentage of students who passed math, passed reading, and passed both math and reading for Thomas High School the school returned to the **second place**


## References

[Markdown 1](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

[Markdown 2](https://www.markdownguide.org/basic-syntax/)

