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

As you can see, the average math score decreased slightly; however, the average reading score increased slightly. More importantly, it appears that the percent of students passing the math score, the reading score, and both scores combined dropped heavily, by 20-30%. This tells me that although the average score did not change by much, the percent of students that passed at Thomas High School was significantly lowered by excluding the ninth grade students. 

- Performance of Thomas High School

In the original dataset, Thomas High School was ranked 2nd in terms of overall passing percentage; however, it fell to 8th after adjusting for the ninth grader scores, so it's placement fell by a lot.

- Math and Reading Scores by Grade

For Thomas High School, the 9th grade statistics now show up as NaN instead of as values since they were removed. See below image as an example. 

![Adjusted Score by Grade](https://github.com/SethBoswell/School_District_Analysis/blob/main/Resources/adjusted_score_by_grade.png)


- Scores by School Spending

I did not see a change for these.
- Scores by School Size

I did not see a change for these.
- Scores by School Type

I did not see a change for these.

## Summary 
Four changes to the statistics as a result of removing Thomas High School's scores for Ninth graders are as follows:

1.) The district-level statistics did not change much, which makes sense to me since these are an aggregation of 15 different schools and the adjustment of one grade from an individual school is unlikely to have a large impact on the results.

2.)Thomas High School's average math/reading scores did not change drastically, but the percent passing did. This result surprised me as I thought the average scores may have decreased signficantly as a result of any cheating. However, it does make sense that the percent passing would decrease signficantly as the 9th graders may have been more likely to pass if they were cheating.

3.) The performance of Thomas High School dropped significantly, which makes sense because, if the ninth graders were cheating, then removing their scores should decrease their ranking.

4.) Interestingly, I did not see any changes in scores by category such as school spending, size, and type. This surprised me to not see any small changes to the category that Thomas High School falls into. Nevertheless, the fact that Thomas High School is only one out of 15 schools leads to me believe that removing one grade from Thomas would not have a signifanct impact on these statistics. 
