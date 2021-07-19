# School_District_Analysis

## Overview

##### Using data encompassing 15 schools I calculated:
*	The total students in each school.
*	The total budget for each school.
*	The average reading and math scores of their students.
*	The percent of students who passed reading and math and the overall passing percentage.
*	How these scores varied based on the school type of district or charter school.

##### After calculating and summarizing these points it was discovered that one school, Thomas High School, may have inaccurate data reported.  I removed these in an updated version of these summaries.  


## School District Results

##### After running through the data it does not appear that there is a correlation between school spending per student but there does appear to be one based on whether or not the school type is district or charter.
* District Results Summary
	*	Average Math Score: 78.9
	*	Average Reading Score: 81.9
	*	Percentage that passed math: 73.9%
	*	Percentage that passed reading: 84.6%
	*	Percentage overall that passed: 79.3%
*  The schools can be summarized as all being within 10 points of each other on average. 
  * Replacing the grades for Thomas High School 9th graders changes:
	*	Math and readings scores by grade do not change except for the removal of the 9th grade scores.
	*	Scores by school spending does not change.
	*	Scores by school size does not change.
	*	Scores by school type does change by about 12%, however.
## School District Summary

##### After replacing the Thomas High School 9th grade scores with NaNs there were 4 main changes:
*	The percentage of math passing for Thomas high school dropped slightly.
*	The percentage of reading passing for Thomas high school dropped slightly.
*	The overall passing of students for Thomas high school dropped slightly.
*	The district scores also dropped while the charter schools remained the same.
##### Below you will see an example of what the school grades look like after replacing the scores with NaNs: 

![Alt text](https://github.com/GaryG484/School_District_Analysis/blob/main/Resources/NaN_Example.PNG)

