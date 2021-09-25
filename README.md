# School_District_Analysis

# Overview of analysis

In this analysis, we are helping Maria to provide insights on several schools' performance trends and patterns. We analyse fundings for different schools
and student performances. We have also been given data on two subjects i.e. Math and Reading. We analyse students' grades in each school and overall school performance. All these insights will help in making strategic decisions on school and district level. Additionally, the school board informs about academic dishonesty at a particular school. To uphold testing standards, school board asked to conduct another analysis where we ommitted Math and Reading scores for 9th graders. With modifications, we look at the outcome of overall analysis and and its implications.

# Results :

After some modifications we compare analysis results and found following information,

# How is district summary affected.

In initial analysis, we see average reading score is better than average math score and same reflects on passing percentages. We see overall passing percentage of 65.17% in the district

<img width="695" alt="District_analysis_PyCitySchools" src="https://user-images.githubusercontent.com/86980240/134455979-a32322e6-d146-4c3e-9c4e-a52b3d0a0132.png">

After a second review, ie. after ommitting grade 9th students from our dataframe, we see overall passing percentage slightly declines to 64.9% so as Maths and Reading scores. 

<img width="709" alt="District_analysis_PyCity_challenge" src="https://user-images.githubusercontent.com/86980240/134456118-0cc492f6-2d9f-4794-b44c-fbf75e383d35.png">


# How is the school summary affected?

With including tampered data, the summary for Thomas High School looks impressive. After modifications, we see that school summary is affected especially with Math, Reading and Overall percentage drastically declined from 90%, 97%, 91% to 67%, 69% and 65% respectively. It did not affect the school budget and there were slight changes in average reading and math score.

<img width="723" alt="Per_school_summary_PyCity" src="https://user-images.githubusercontent.com/86980240/134456624-5881edb2-9590-4ee6-93b3-0fd63de8e9dc.png">


<img width="702" alt="Per_school_summary_challenge" src="https://user-images.githubusercontent.com/86980240/134456642-8dd31884-b04f-4816-8d52-49d49fdb1dc5.png">


# How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Overall, it does not affect average scores in two subjects however, there is significant decline in passing percentages. It does not affect other schools' or graders' performances. 


# How does replacing the ninth-grade scores affect the following:
# Math and reading scores by grade:

The Math and Reading scores changed to NaN since we ommitted grade 9th students. It did not affect other graders' scores.

<img width="324" alt="Math Scores_challenge" src="https://user-images.githubusercontent.com/86980240/134458039-e03756ba-e06d-4c6d-bfac-92886363d2b2.png">


<img width="346" alt="Reading_challenge" src="https://user-images.githubusercontent.com/86980240/134458050-d7749d8e-cfc9-459e-9d0a-78b996551c61.png">


# Scores by school spending:

<img width="612" alt="Pycity_schools_spending_summary" src="https://user-images.githubusercontent.com/86980240/134458198-47f85748-fc5e-41c9-92d1-f90f543904bd.png">

And after ommitting grade 9th, we see a decline in Math, Reading and Overall percentages in $630-$644 spending ranges.

<img width="616" alt="Spending summary_challenge" src="https://user-images.githubusercontent.com/86980240/134460957-eb8a19dc-75a8-4eaf-bc3b-c5bb073b9600.png">



# Scores by school size:

We see changes in range (Medium (1000-2000) ) school size again in math, reading and overall percentage

<img width="566" alt="Size_pyCity_schools" src="https://user-images.githubusercontent.com/86980240/134458441-8ebcd06a-c7e6-46d3-be3e-cfc3ea30c44a.png">


<img width="654" alt="Size_challenge" src="https://user-images.githubusercontent.com/86980240/134461207-63da67db-c001-4fef-8b9c-aad81ec53a35.png">



# Scores by school type:

As it can be seen that tampering of data caused around 3% decline in math, reading and overall percentages in Charter schools 

<img width="527" alt="Type_summary_PyCity_school" src="https://user-images.githubusercontent.com/86980240/134458546-214901d3-e21f-464a-8483-5dd0506c532e.png">


<img width="604" alt="Type_challenge" src="https://user-images.githubusercontent.com/86980240/134461486-6131c152-868c-4919-b08d-441569520d94.png">


# Summary: 

Thomas High school's performance was good initially. But after ommitting few datas due to dishonesty, Thomas High school lost the overall percentages, math and reading percentages. Charter schools' performances are far better than District schools. It did not affect overall Charter school performance though as there was around 3% decline in percentages. However, average scores were not affected may be because different school sizes. Also, with spending and size summaries, it can be seen that schools with small to medium sizes and with spending range of under $630 per student fared better than those of bigger sizes and spending ranges.


