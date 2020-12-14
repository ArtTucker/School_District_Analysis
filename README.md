# School District Analysis
School District performance analysis with Pandas, using Jupyter

## Overview
The main purpose of this project was to review the performance of high schools in a given school district, based on the math and reading scores of their students on standardized tests. Two separate CSVs, one recording information about the various high schools, and another about all of the high school students in the district, were reviewed, cleaned, and then combined prior to being subject to various analyses.

![Per School Overview](resources/per_school_summary_module.png)
The initial analysis consisted of a per-school overview of student population, budget, per-student budget, average math & reading scores, and percentage of students with passing grades. This was also accompanied by a rating of the top-five and bottom-five performing schools, determined by the overall passing percentage of students at these schools.

![Per Grade Math Averages](resources/per_grade_math_module.png)![Per Grade Reading Averages](resources/per_grade_reading_module.png)
The next level of analysis looked at average Math & Reading scores at each high school, by grade level.

[Per Student spending and grades](resources/per_student_spending_bins_grades.png)
This was followed by an examination of how budgetary spending per-student related to average test scores.

Following this were analyses of how/if school size...
[School size and grade summary](resources/size_summary_scores_module.png)
... or type...
[School type and performance summary](resources/school_type_summary_module.png)
... reflected on test scores.

The challenge consisted of the introduction (or rather removal of some information). The scenario presented was that evidence of academic dishonesty necessitated the voiding of test scores for all 9th grade students at Thomas High School. This necessitated the recalculation of student population totals and average test scores. Beyond that, the operations were largely the same.

## Results

What can we tell from these tables?
In reviewing the top-five/bottom-five data, based on overall percent of students with passing test scores, a cursory review could suggest that Charter schools perform better than the District schools, or that student success is inversely correlated to the size of the total student population (smaller schools seem to have better test scores).
![Per School top five](resources/per_school_top_five_module.png)
![Per School bottom five](resources/per_school_bottom_five_module.png)
In looking at how spending per-student relates to average test scores, or percent of students with passing grades, one could also jump to the conclusion that increased funding has a negative effects on performance. However this relation probably has more to do with school population size (spending per-student).
[School size and grade summary](resources/size_summary_scores_module.png)
If we look again at the comparison between school size and performance we see this conclusion reinforced. In face, we can see a precipitous drop-off in student performance in high schools that have more than 2000 students.
Lastly, if we review the scores by school type, we see that even though the numbers for Charter schools were higher than for District schools, we can't eliminate the possibility that this was largely because the District schools tended to have larger student populations.

## Summary
In conclusion I think it's safe to say that student performance is less directly affected by funding or the type of school the student is enrolled in. The dominant predictor, as demonstrated by this analysis, seems to show that school size, and the ability for students to receive more one-on-one time and attention from trained staff, if the leading factor in student success.