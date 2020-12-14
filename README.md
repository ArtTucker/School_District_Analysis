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
In looking at how spending per-student relates to average test scores, or percent of students with passing grades, one could also jump to the conclusion that increased funding has poor effects on 


## Summary