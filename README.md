# School_District_Analysis
Python Code for PyCitySchools Project
## Overview of School District Analysis Project
In the initial project, I helped Maria analyze district-level and school-level academic data. For the district-level analysis, I created a dataframe that lists district-level statistics such as the total number of schools in the district, number of students, total budget, average math/reading score, the percent of math/reading scores that passed, and the percent of students that passed on both the math and reading exam combined.

For the school-level analysis, I created a dataframe that listed, for each school, their corresponding type (district/charter), student population, budget, budget per student, average math/reading score, the percent of students passing math, the percent passing reading, and the percent passing both math and reading. 

Furthermore, I also determined the top and bottom 5 schools based on their overall passing rate, the average math/reading score for each grade level from each school, and the scores by schools spending per student, school size, and school type. 

In the Challenge Assignment, I adjusted the code to disclude all 9th graders from Thomas High School because there were concerns over academic dishonesty. After these scores were removed from the dataset by setting their values to be NaN (not a number), I re-analyzed the dataset and found different results. In the results section below, I will address a number of different questions on how my statistics were affected by the removal of Thomas High School's ninth grade students.

## Results
- District Summary

The original district-level analysis is included below, followed by the adjusted analysis after discluding the ninth graders' scores.

Original District-Level Analysis:

![Original District-Level Analysis](https://github.com/SethBoswell/School_District_Analysis/blob/main/Resources/original_district_analysis.png)

Adjusted District-Level Analysis:

![Adjusted District-Level Analysis](https://github.com/SethBoswell/School_District_Analysis/blob/main/Resources/adjusted_district_analysis.png)

As you can see, removing the ninth graders from Thomas High School decreased the average math score by 0.01, the percentage of students passing math by 0.02%, the percent passing reading by 0.03%, and the overall passing percentage by 0.1%. Thus, the disclusion of the ninth graders brought down most of the statistics by a slight amount, indicating they were doing better than average on their tests. However, they had only a small affect on the district-level statistics because these statistics are an aggregation of all schoools, so a small grouper of students is not going to cause drastic changes. 

- School Summary

The original school-level analysis is included below, followed by the adjusted analysis after disclusing then ninth grader's scores.

Original School-Level Analysis:

![Original School-Level Analysis](https://github.com/SethBoswell/School_District_Analysis/blob/main/Resources/original_school_analysis_2.png)

Adjusted School-Level Analysis

![Adjusted School-Level Analysis](https://github.com/SethBoswell/School_District_Analysis/blob/main/Resources/adjusted_school_level_analysis.png)


- Perforamce of Thomas High School
- Math and Reading Scores by Grade
- Scores by School Spending
- Scores by School Size
- Scores by School Type
## Summary 
