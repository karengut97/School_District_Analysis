# School District Analysis

## Project Overview
Anomolies have been discovered in the math and reading scores for Thomas High School. This project compares the original results from our district analysis to the revised analysis of Thomas High School to determine if the dishonest reporting from Thomas High School has an impact on the overall district summaries:

* Math and Reading scores by grade
* Scores by school spending
* Scores by school size
* Scores by school type

## Resources
The following resources were used to analyize the results:
* Data Sources: PyCitySchools_Challenge_starter_code.ipynb
* Original analysis: PyCitySchools.ipynb


## School District Analysis Results
The implications of academic dishonesty in Thomas High School for ninth grade math and reading scores do not have a significant impact on the original school district assessment. 

### District Summary Impacts
This is the District Summary **BEFORE** Thomas High School 9th grade score changes:
![District_Summary_Original.png](Resources/District_Summary_Original.png)

This is the District Summary **AFTER** Thomas High School 9th grade score changes:
![District_Summary_Revised.png](Resources/District_Summary_Revised.png)

At the District Summary Assessment, the following impacts exist:
* Average Math Scores: -0.1%
* Average Reading Scores: +0.1%
* Overall Passing Math: -0.2%
* All other measures are unchanged

The difference after removing Thomas High School 9th grade scores does not alter this summary. Once rounding is incorported, the scores looks the same.

### School Summary Impacts
This is the School Summary **BEFORE** Thomas High School 9th grade score changes: 
![School_Summary_Original.png](Resources/School_Summary_Original.png)

This is the School Summary **AFTER** Thomas High School 9th grade score changes: 
![School_Summary_Revised.png](Resources/School_Summary_Revised.png)

Thomas High School's Summary Impacts:
* Average Math Score: -0.06
* Average Reading Score: +0.05
* % Passing Math: -0.09%
* % Passing Reading: -0.29%
* % Overall Passing: -0.32%

No statistical relevance is present for the overall school score summary changes.

### How does replacing the ninth-grade scores affect THS peformance relative to other schools
The impact of replacing the 9th grade students' math and reading scored with "NaN" is minimal. It is not enough to invalidate the overall scores of the school or district. Thomas High School remains in the Top 5 Schools for the district.

This is the Top 5 Summary **BEFORE** Thomas High School 9th grade score changes: 
![Top_5_Schools_Original.png](Resources/Top_5_Schools_Original.png)

This is the School Summary **AFTER** Thomas High School 9th grade score changes: 
![Top_5_Schools_Revised.png](Resources/Top_5_Schools_Revised.png)

### Math and reading scores by grade
A comparison for the math and reading grade demonstrates the scores for all schools and grades are not impacted by removing THS 9th graders from the summary.
#### Math Scores by Grade:
Side by Side Comparison of Original Math Scores and Revised Math Scores with THS 9th Graders Removed:
<img  src="Resources/Math_Scores_By_Grade_Original.png" width="400" height="450"/> <img src="Resources/Math_Scores_By_Grade_Revised.png" width="400" height="450"/> 

#### Reading Scores by Grade:
Side by Side Comparison of Original Reading Scores and Revised Reading Scores with THS 9th Graders Removed:
<img  src="Resources/Reading_Scores_By_Grade_Original.png" width="400" height="450"/> <img src="Resources/Reading_Scores_By_Grade_Revised.png" width="400" height="450"/> 


### School Spending
School Spending is not impacted by the changes to Thomas High School. All measures remaing the same. 

**BEFORE** Thomas High School Changes:
![Scores_By_School_Spending_Original.png](Resources/Scores_By_School_Spending_Original.png)

**AFTER** Thomas High School Changes:
![Scores_By_School_Spending_Revised.png](Resources/Scores_By_School_Spending_Revised.png)

### School Size
School size results remains the same as students were not removed, only the scores were removed for Thomas High School 9th graders.

**BEFORE** Thomas High School Changes:
![Scores_By_School_Size_Original.png](Resources/Scores_By_School_Size_Original.png)

**AFTER** Thomas High School Changes:
![Scores_By_School_Size_Revised.png](Resources/Scores_By_School_Size_Revised.png)


### School Type
School type results remains the same as students were not removed, only the scores were removed for Thomas High School 9th graders.

**BEFORE** Thomas High School Changes:
![Scores_By_School_Type_Original.png](Resources/Scores_By_School_Type_Original.png)

**AFTER** Thomas High School Changes:
![Scores_By_School_Type_Revised.png](Resources/Scores_By_School_Type_Revised.png)

## Summary
