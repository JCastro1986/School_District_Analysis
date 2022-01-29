# School District Analysis
Callenge #4. Help Maria to repeat the school district analysis and write up a new report where the reading and math grades for the Thomas High School ninth graders are excluded. This new analysis will help he Educational Institutions better understand how these new changes affected the overall School District Analysis.

## Overview of the school district analysis
The main goal of this analysis is to obtain clean metrics. After doing some cleaning in our data such as:   
- Remove prefixes and suffixes.
- Do not considere for our analysis Thomas High School ninth graders.
After completing my review and ending up with clean data, I can provide insightfull metrics that can help Educational Institutions to take better desicions based on the this result.
The school board just realized that there is evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered.  I am asked to help in teh following:
- I need to replace the math and reading scores for Thomas High School and keep the rest of the data intact.
With this new update I will generate new metrics and analyze the affectations of Thomas High School after realiziing of the dishonesty information.

## Results
Using bulleted lists and images of DataFrames as support, address the following questions.

How is the district summary affected?
The main affectation on the district summary where the following:
1. The Average Math Score decreased by 0.1.
2. The Passing Math Percentage decreased by 0.2%.
3. The Passing Reading Percentage decreased by 0.1%.
4. The Overall Passing Percentage decreased by 0.3%.
* All of the changes from above are driven by having data removed, it seems the dihonest data had high values, that is why all of the above when down a bit.
* Data before removing reading and math socres from the Thomas High School ninth graders.   
Image #1 (Before)
* Data after removing reading and math socres from the Thomas High School ninth graders.
Image #2 (After)

How is the school summary affected?
The main affectation on the school summary where the following:
1. The Average Math Score decreased by (0.067412).
2. The Average Reading Score increased by 0.047152 
3. The Percentage Passing Math decreased by (26.360856)%
4. The Percentage Passing Reading decreased by (27.645260)%
5. The Percentage Overall Passing decreases by (25.871559)%
6. The number of students removed from Thomas High School were 461
* This decrease contributed to the changes in our previous data.
- Total Student Count before removing 9th graders from Thomas High School was 39,170 students, and after removing 9th graders from Thomas High School was 38,709 studends, a difference of 461 students.
* It is important to ensure that the only values affected where the on for the Thomas High School
* Data before removing reading and math socres from the Thomas High School ninth graders.   
Image #3 (Before)
* Data after removing reading and math socres from the Thomas High School ninth graders.
Image #4 (After)
* Student Count before removing 9th graders from Thomas High School
Image #5 (Before)
* Student Count after removing 9th graders from Thomas High School
Image #6 (After)

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
The affectation from replacing the ninth graders’ math and reading scores affect Thomas High School’s performance directly to others schools.
1. The Percentage Overall Passing of Thomas High School went from 90.948012 to 65.076453, a decreases of (25.871559)%.
2. After removing ninth graders The Thomas High School when from being in second place to eight place. 
* Data before removing reading and math socres from the Thomas High School ninth graders.   
Image #7 (Before)
* Data after removing reading and math socres from the Thomas High School ninth graders.
Image #8 (After)


How does replacing the ninth-grade scores affect the following:
1. Math and reading scores by grade
All values but ninth-grade in Thomas High School will remain the same.
New values for ninth-grade in Thomas High School will be nulls.
* Data before removing reading and math socres from the Thomas High School ninth graders.   
Image #9 (Before)
* Data after removing reading and math socres from the Thomas High School ninth graders.
Image #10 (After)

2. Scores by school spending
There are no affectations to the Scores by school spending since I only updated the scores for nine graders resulting in no affectation to the Scores by school spending.
* Data before & after removing reading and math socres from the Thomas High School ninth graders.
Image #11 (Before & After)

3. Scores by school size
There are no affectations to the Scores by school size since Thomas High School differences after the update might not have been material to change the final result.
* Data before & after removing reading and math socres from the Thomas High School ninth graders.
Image #12 (Before & After)


4. Scores by school type
There are no affectations to the Scores by school type since Thomas High School differences after the update might not have been material to change the final result.
* Data before & after removing reading and math socres from the Thomas High School ninth graders.
Image #13 (Before & After)


## Summary
There were only four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs. The values affected were:
- Average Math Score changed from 79.0 to 78.9.
- Passing Math Percentage changed from 75.0% to 74.8%. 
- Passing Reading Percentage changed from 85.8% to 85.7%.
- Overall Passing Percentage changed from 65.2% to 64.9%.
