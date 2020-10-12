# School_District_Analysis

## Project Overview
A city school district asked I assist in analyzing standardized test scores and student funding to display trends and academic performance. I was given the following tasks:

	-Present an overview of the district's key metrics.
	-Present an overview if the individual school's key metrics.
	-Display the 5 top and bottom performing schools based on passing rate. 
	-Map the average math score of each student in each grade at each school.
	-Map the average reading score for each student in each grade at each school.
	-Show the school performance based on budget.
	-Show the school performance based on school size. 
	-Show the school performance based on the type of school.
	-Check for academic dishonesty by isolating and replacing certain scores. 
	
## Resources
- Data Source: students_complete.csv, schools_complete.csv, missing_grades.csv
- Software: Jupyter Notebook 6.1.4

## Results
The district summary wasn't changed aggressively after removing the ninth grade scores. Thomas High School is a small charter school whose funding student population is already in the lower half. 

The school summary wasn't massively changed by removing the Thomas High School ninth  grade scores in most areas, however, their overall passing score dropped significantly due to the fact that the freshman class (at 461) makes up over a quarter of the small to medium sized school.

Replacing the ninth grader's math and reading scores dropped Thomas High School's overall performance. They went from having one of the highest passing percentages to near the middle, dropping over 20%.  

	-Replacing the ninth grade scores affects:
	-Math and reading scores: 
	Very small, the score for reading stayed 81% while the math  score changed from 78.98% to 78.93% after the ninth graders marks 	were removed.  
	-Scores by School spending: 
	Thomas High school stayed in the $630-644 per student spending amount, the 3rd smallest amount allotment of all 15 schools. 
	-Scored by School size:
	THS has the 2nd highest overall passing score at 91% before, despite being the 4th smallest school. They dropped to 65% after losing the ninth grade 		scores and ended up in the middle of the 15 schools. 
	-Scored by School type: 
	After removing the scores, THS went from being one of the highest overall passing percentages to below average.   
	
## Summary
After cleaning up the data and removing the ninth grade scores, it was clear that while Thomas High School freshman didn't have a large impact on the majprity of the data, the one they did impact (overall passing scores) they did so aggressively. 
