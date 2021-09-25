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

With including tampered data, the summary for Thomas High School looks impressive. After modifications, we see that school summary is affected especially with Math, Reading and Overall percentage drastically declined from 93%, 97% and 91% to 67%, 69% and 65% respectively. It did not affect the school budget and there were slight changes in average reading and math score.

<img width="723" alt="Per_school_summary_PyCity" src="https://user-images.githubusercontent.com/86980240/134456624-5881edb2-9590-4ee6-93b3-0fd63de8e9dc.png">


<img width="702" alt="Per_school_summary_challenge" src="https://user-images.githubusercontent.com/86980240/134456642-8dd31884-b04f-4816-8d52-49d49fdb1dc5.png">


# How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Overall, it does not affect average scores in two subjects however, there is significant decline in passing percentages. It does not affect other schools' or graders' performances. 


# How does replacing the ninth-grade scores affect the following:
# Math and reading scores by grade:

The Math and Reading scores changed to NaN since we ommitted grade 9th students. It did not affect other graders' scores.

<img width="282" alt="math_scores" src="https://user-images.githubusercontent.com/86980240/134776440-ce0527b2-4884-4855-8a84-fcb9ea0a535c.png">


<img width="279" alt="reading_scores" src="https://user-images.githubusercontent.com/86980240/134776446-af889b0f-dad1-41ee-a782-ba813125394d.png">



# Scores by school spending:

<img width="612" alt="Pycity_schools_spending_summary" src="https://user-images.githubusercontent.com/86980240/134458198-47f85748-fc5e-41c9-92d1-f90f543904bd.png">



<img width="674" alt="spending_summ" src="https://user-images.githubusercontent.com/86980240/134776533-f03f117d-0c81-49fc-b2cc-84b470bb1a72.png">




# Scores by school size:

We see slight changes in range (Medium (1000-2000) ) school size again in math, reading and overall percentage

<img width="566" alt="Size_pyCity_schools" src="https://user-images.githubusercontent.com/86980240/134458441-8ebcd06a-c7e6-46d3-be3e-cfc3ea30c44a.png">


<img width="617" alt="size_summ" src="https://user-images.githubusercontent.com/86980240/134776566-5f48e0f7-a509-49a3-8df3-a753279206f7.png">




# Scores by school type:



<img width="527" alt="Type_summary_PyCity_school" src="https://user-images.githubusercontent.com/86980240/134458546-214901d3-e21f-464a-8483-5dd0506c532e.png">


<img width="585" alt="type_summ" src="https://user-images.githubusercontent.com/86980240/134776589-08921aa1-1cdd-4293-90ad-783c3bc82d1b.png">



# Summary: 

Thomas High school's performance was good initially. But after ommitting few datas due to dishonesty, Thomas High school lost the math, reading and overall passing percentages. Charter schools' performances are far better than District schools. Modifications did not affect overall Charter school performances though. Also, with spending and size summaries, it can be seen that schools with small to medium sizes and with spending range of under $630 per student fared better than those of bigger sizes and spending ranges.


