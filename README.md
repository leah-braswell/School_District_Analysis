#PyCitySchools District Analysis

## Purpose
The School District has been given the standardized test scores for Grades 9-12.  Test scores are used to identify areas of strength and areas for improvement in schools.  In order to determine how to allocate funds, resources, and personell for the coming year they would like an analysis performed based on the following key metrics:
- Total Number of Students
- Total Number of Schools
- Total Budget (as well as spending per student)
- Average Math Scores
- Average Reading Scores
- Percentage of Students Who Passed Math
- Percentage of Students Who Passed Reading
- Overall Passing Percentage

After receiving the original analysis, the District was informed of testing violations resulting in the invalidation of the 9th grade Math and Reading Scores from Thomas High School.  After removing the scores, the analysis was repeated and new metrics were presented.



## Results

### Original Findings
- District Summary
		There are 15 high schools in the district with a total of 39,170 students, and an overall budget of $24,649,428.00. The District is comprised of 7 traditional District schools and 8 Charter Schools.   Schools range in size from 427 students to 4761 students.  School budgets vary from $248,087 to $3,124,928.  Refer to the links below for more details.

[District Summary](School_District_Resources/School_Data_Snip.PNG)

[School Summary](School_District_Resources/school_summary_df.PNG)

- Top 5 Performing Schools (based on overall passing rate) (School_District_Resources/top_five)
	The top five performing schools based on overall passing rate are Cabrera High School, Thomas High School Griffin High School, Wilson High School, Pena High School.  All of these schools are Charter schools and had an overall passing rate of over 90%. All of these schools spend over $575 per student.
		
- [Bottom 5 Performing Schools(based on overall passing rate)](School_District_Resources/bottom_five.PNG)
	The five lowest performing schools based on overall passing rate are Rodriquez High School, Figueroa High School, Huang High School, Hernandez High School, and Johnson High School.  The schools are all District schools and had an overall passing rate of about 53%.  These schools spend between $637 and $655 per student.
		
- [Average Math Scores by Grade Level](School_District_Resources/math_scores_by_grade.PNG)
	Math scores varied by very little from one grade level to the next when looking at the District as a whole.  The lowest average is about 76% and the highest at about 84%.  When looking across grades at a school level, the same can be seen.  At every school the average across grade levels only varied by anobout one point.
		
- [Average Reading Scores by Grade Level](School_District_Resources/reading_scores_by_grade.PNG)
	The Reading scores followed the same pattern as the Math scores.  The lower average for each grade level across the District was about 80% and the highest average was about 84%.  It was interesting to see that the lower average Reading score was around four points higher than the lower average Math scores.
	
- [Analysis of Spending per Student](School_District_Resources/spending_ranges_per_student.PNG)
	When looking at the spending per student in relation to the performance of the school, the data shows that as per student spending increases, student performance decreases.  This is something I would investigate further.  It would be useful to know how each school is allocating its funds.  Does spending in one category or another (technology, personnel,  seem to have an effect on student performace?

- [Analysis of School Size](School_District_Resources/size_summary.PNG)
	The analysis of the influence of school size on student performance there was a clear area for improvement.  The Overall passing rate at large schools was significanly lower than the other schools.  Math stands out as the area for more investigation and problem solving.  The percentage of students passing Math (70%) was seven points lower than the percentage of students passing Reading (83%).  The average Math score (77.7) was almost four points lower than the average Reading score (81.3) in Large Schools.  This is not the case in Small and Medium scores where the average Math score is with in half of a point of the average Reading score.

- [Analysis of School Type](School_District_Resources/school_type.PNG)
	When comparing Charter schools to District schools, Charter schools performed better overall.  In this analysis we again see a need for improvement in Math.  Average Math scores in District schools (77.0) were four points lower than average Reading scores in District schools (81.0).  Charter schools' average Reading and Math scores were within half a point of one another.  Charter schools' average Math Score was six points higher than the District schools' average.

### Findings after removing Thomas High School 9th Grade Scores:
- [The District Summary](School_District_Resources/district_summary_new.PNG) showed a 1% higher Math passing percentage and Overall passing percentage.
- Thomas High School's performance significanly dropped.  The percentage of students passing Math went from 93.3% to 66.9%.  The percentage of students passing Reading went from 97.3% to 69.7%.  The overall passing percentage fell from 90.9% to 65.7%.  
- This dropped Thomas High School's standing as compared to other schools. This school is no longer in the [top five performing schools.](School_District_Resources/new_top_five.PNG)  The invalidation of the 9th Grade scores did not affect the bottom five performing schools.
- The trend of lower [spending per student](School_District_Resources/new_spending_ranges.PNG) correlting with higher overall passing was not affected by the change, however the overall performance of schools in the $645-675 range dropped.
- The overall passing percentage of [Medium sized schools](School_District_Resources/new_size_summary.PNG) dropped by four points. 
- [Charter schools'] (School_District_Resources/new_school_type.PNG) overall passing percentage decreased by three points.  



## Summary
The invalidation of the 9th Grade scores from Thomas High School did not affect the overall picture of the District, however when the data was drilled down, there were some noteable changes.  Thomas High School was once in the top 5 performing schools, however they dropped from their place moving Wright High School into the top five.  The trends from each analysis were not greatly affected, but one category or another suffered greatly from the removal of the 9th Grade scores.  The overall passing percentage of Medium sized schools dropped by four points. Charter schools' overall passing percentage decreased by three points. The overall performance of schools spending $645-675 per student fell 7%.




