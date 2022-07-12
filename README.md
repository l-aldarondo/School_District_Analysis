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


 At the district level there was no major impact on the overall results when we replaced the 9th grade scores from Thomas High School. When we compared Fig 1.1 and Fig 1.2, the overall passing percentage only changed by 0.1%. This could be because the grades for the ninth grade represent a small portion compared to the rest of the population in the district.

![Challenge_Distict_Summary](./Images/challenge_district_summary.png)

<sub>Figure 1.1 Challenge district symmary

![Pycity_District_Summary](./Images/Pycity_district_summary.png)

<sub>Figure 1.2 Original district summary


 Something similar happened when we compared the data in the school summary in Fig 1.3 and Fig 1.4. There were no big changes on the results on the school summary DataFrame. The overall passing score for Thomas High School only changed by 0.32%, again this could e because the "9th" grade population is a small portion of the whole district as we stated above.
  
![Challenge_Per_Schools_Summary](./Images/challenge_per_school_summary.png)

<sub>Figure 1.3 Challenge schools summary

![Pycity_Per_School_Summary](./Images/Pycity_per_school_summary.png)

<sub>Figure 1.4 Original school summary

  
 Replacing the scores with "nan" as shown in Fig 1.6, caused the overall passing score for Thomas High School to drop to **65.1%** (Fig 1.6). However when we recalculate the percentage of students who passed math, passed reading, and passed both math and reading for Thomas High School the school overall passing rate was **90.63%** (Fig 1.7). 

 When we compared (Fig 1.5 - 1.7), Thomas High School was dropped from the top 5 schools however after we recalculated the values THS returned to the top 5 schools. Thomas High School remains in the *2nd position** of the top 5 schools. Therefore we can conclude that the change after we recalculated the % passing didn't affect THS in relation to the other schools.


![Pycity_Top_Schools](./Images/Pycity_top_schools.png)
<sub>Figure 1.5 Original top schools

![Pycity_Math_Scores_by_Grade](./Images/per_school_without%20_replacment.png)
<sub>Figure 1.6 Thomas High School %Passing after replacement


![Pycity_Reading_Scores_by_Grade](./Images/per_school_after_replacement.png)
<sub>Figure 1.7 Thomas High School %Passing recalculated


#### Math and reading scores by grade
  
 Repacing the ninth grade score with "nan" (Fig 1.8) caused the omition of the entire 9th grade population, therefore this specific group didnt have individuals or collective scores or percentages to count against the school Overall scores. The math and reading scores for Thomas High school increased by **0.06%** and **0.1%** (Figure 1.8 - 1.11) respectively after we replaced the score for th ninth grade.

![Challenge_Math_Scores_by_Grade](./Images/challenge_math_score_by_grade.png)

<sub>Figure 1.8 Challenge math scores by grade

![Challenge_Reading_Scores_by_Grade](./Images/challenge_reading_score_by_grade.png)

<sub>Figure 1.9 Challenge reading scores by gade

![Pycity_Reading_Scores_by_Grade](./Images/Pycity_math_score_by_grade.png)

<sub>Figure 1.10 Original math scores by grade

![Pycity_Reading_Scores_by_Grade](./Images/Pycity_reading_score_by_grade.png)

<sub>Figure 1.11 Original reading scores by grade


#### Scores by school spending

 The % passing and average scores did not increased as spending per student increased. Schools that spent less per student outperformed schools that spent more per student. As we can see in Fig 1.12 and 1.13, the schools that spended $645 - 660 per student had considerably lower scores compared to schools that spent <$586 which had the highest overall scores.

![Challenge_Scores_By_Spending](./Images/challenge_score_by_spending.png)

<sub>Figure 1.12 Challenge scores by spending

![Pycity_SCores_By_Spending](./Images/Pycity_score_by_spending.png)

<sub>Figure 1.13 Original scores by spending

#### Scores by school size

Small and Medium size schools outperformed larger size schools in math scores, reading scores and in all % to include % Overall Passing. The larger schools percentage passing is very different and is pulling the overall passing percentage down for district schools. (Fig 1.14 - 1.15)

![Challenge_Scores_By_School_Size](./Images/challenge_score_by_school_size.png)

<sub>Figure 1.14 Challenge scores by school size

![Pycity_Scores_By_School_Size](./Images/Pycity_score_by_school_size.png)

<sub>Figure 1.15 Original scores by school size

#### Scores by school type

 Charter schools outperformed district schools in math scores, reading scores and in all % to include % Overall Passing. The percentage passing math is  very different and is pulling the overall passing percentage down for district schools.(Fig 1.16 -1.17)

![Challenge_Scores_By_School_Type](./Images/challenge_score_by_school_type.png)

<sub>Figure 1.16 Challenge scores by school type

![Pycity_Scores_By_School_Type](./Images/Pycity_score_by_school_type.png)

<sub>Figure 1.17 Original scores by school type

## Summary

The replacement of the scores for Thomas High school had minimal effect on the school ranking. The school was dropped from the top 5 schools in the district. But when we recalculate the percentage of students who passed math, passed reading, and passed both math and reading for Thomas High School the school returned to the **second place**.
    
* The overall district summary changed by **0.1%** for Thomas High school.

* The overall per school summary dropped by **0.32%** for Thomas High School.

* Thomas High school math and reading scores increased by 0.06% and 0.1% respectively after we replaced the score for th ninth grade.

* Replacing the scores with n/a caused that the overall passing score for Thomas High School dropped to 65%.. However when we recalculate the percentage of students who passed math, passed reading, and passed both math and reading for Thomas High School the school the overall passing rate was **90.63%**



## References

[Markdown 1](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

[Markdown 2](https://www.markdownguide.org/basic-syntax/)
