# School_District_Analysis

## Overview of the School District Analysis
This analysis uses Pandas and numpy libraries in Python in Jupiter notebook to examine math and reading scores for students in a district of fifteen high schools. The data compares average  math, reading, and overall passing scores.  

The purpose of this analysis is to determine the effects of replacing the scores for all 9th graders at Thomas High School with NaNs while keeping the rest of the data intact. The goal is to conduct a second analysis with data removed in order to see if any changes occur. This may indicate evidence of academic dishonesty, such as if grades were altered. 

## Results
#### •	How is the district summary affected?

Comparing the district summaries in a data frame shows that the average math score and the percentage of students passing reading decreased, which also  affected the percentage of overall passing students. 

District Summary Before Cleanup
![District Summary Before Cleanup](https://github.com/stephperillo/School_District_Analysis/blob/main/Resources/District%20Summary%20Before%20Cleanup.png)

vs. After

![District Summary](https://github.com/stephperillo/School_District_Analysis/blob/main/Resources/District%20Summary.png)

#### •	How is the school summary affected?

  The school summary was also affected, with each change ocurring only among Thomas High School's scores:
  
1. The average math score for Thomas High School decreased from 83.42 to 83.35.
2. The average reading score for Thomas High School increased from 83.85 to 83.90.
3. The percentage of students passing math for Thomas High School decreased from 93.3% to 66.4%.
4. The percentage of students passing reading for Thomas High School decreased from 97.3% to 69.7%.
5. The percentage of overall passing students (with scores passing both math and reading) for Thomas High School decreased from 90.9% to 65.1%.

School Summary Before Cleanup
![School Summary Before Cleanup](https://github.com/stephperillo/School_District_Analysis/blob/main/Resources/Per%20School%20Summary%20Before%20Cleanup.png)

vs. After
![School Summary](https://github.com/stephperillo/School_District_Analysis/blob/main/Resources/Per%20School%20Summary.png)

#### •	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

  ◦	After replacing Thomas High School’s ninth grader scores, Thomas High School’s ranking remained the same relative to the other schools despite the slight decrease in scores compared to before the cleanup. 	

Top 5 Schools Before Cleanup

![Top Schools Before Cleanup](https://github.com/stephperillo/School_District_Analysis/blob/main/Resources/Top%20Schools%20Before%20Cleanup.png)

vs. Top 5 Schools After

![Top Schools](https://github.com/stephperillo/School_District_Analysis/blob/main/Resources/Top%20Schools.png)

####	How does replacing the ninth-grade scores affect the following:

◦ Math and reading scores by grade

  - Math and reading scores for Thomas High School 9th graders were removed. "nan" is displayed, showing that there is no number for 9th grade Thomas High School scores.

Math Scores Before Cleanup
![Math Scores Before Cleanup](https://github.com/stephperillo/School_District_Analysis/blob/main/Resources/Math%20Scores%20by%20Grade%20Before%20Cleanup.png)
vs. After ![Math Scores](https://github.com/stephperillo/School_District_Analysis/blob/main/Resources/Math%20Scores%20by%20Grade.png)

Reading Scores Before Cleanup
![Reading Scores Before Cleanup](https://github.com/stephperillo/School_District_Analysis/blob/main/Resources/Reading%20Scores%20by%20Grade%20Before%20Cleanup.png)
vs. After ![Reading Scores](https://github.com/stephperillo/School_District_Analysis/blob/main/Resources/Reading%20Scores%20by%20Grade.png)
    
◦ Scores by school spending
  
   - Looking at the scores categorized by spending range, the $630 to $644 range dropped across all series. The percentage of passing students in this spending range decreased from 62.86% to 62.78%, which makes sense because Thomas High School is in this spending range. 
 
 Spending Summary Before Cleanup
![Spending Summary Before Cleanup](https://github.com/stephperillo/School_District_Analysis/blob/main/Resources/Spending%20Range%20Summary%20Before%20Cleanup.png)
 
 vs. After
 
![Spending Summary](https://github.com/stephperillo/School_District_Analysis/blob/main/Resources/Spending%20Range%20Summary.png)
    
◦	Scores by school size 
	  ⁃	The cleanup had a small effect on the bin of medium schools (1000-2000 students). Average math scores dropped for medium schools.
    
Size Summary Before Cleanup

![Size Summary Before Cleanup](https://github.com/stephperillo/School_District_Analysis/blob/main/Resources/Size%20Summary%20Before%20Cleanup.png)

vs. After

![Size Summary](https://github.com/stephperillo/School_District_Analysis/blob/main/Resources/Size%20Summary.png)
    
◦ Scores by school type

⁃	All of the scores dropped very slightly for charter schools.

⁃	The overall passing percentage for charter schools dropped from 90.43% to 90.37%.

Type Summary Before Cleanup

![Type Summary Before Cleanup](https://github.com/stephperillo/School_District_Analysis/blob/main/Resources/Type%20Summary%20Before%20Cleanup.png)
    
vs. After

![Type Summary](https://github.com/stephperillo/School_District_Analysis/blob/main/Resources/Type%20Summary.png)

## Summary
Four changes in the updated analysis: 
  1. Compared to other charter schools, Thomas High School’s scores were not as high without the 9th grade scores.
  2. Overall, scores for 9th graders dropped without Thomas High School.
  3. Scores for medium-sized schools overall dropped without Thomas High School.
  4. Scores for schools in the $630 to $644 range dropped without Thomas High School.

This analysis shows that there were many effects of removing scores for all Thomas High School 9th graders. 
