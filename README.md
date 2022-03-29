# School District Analysis

## Project Overview
The school board has reviewed a previous study performed on the schools in the district. The results seem to suggest academic dishonesty in math and reading for Thomas High School ninth graders. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have requested the following analysis performed without data from the Thomas High School ninth grader’s math and reading results.

1. The district summary
2. The school summary
3. The top 5 and bottom 5 performing schools, based on the overall passing rate
4. The average math score for each grade level from each school
5. The average reading score for each grade level from each school
6. The scores by school spending per student, by school size, and by school type

## Resources
- Data Source: schools_complete.csv, students_complete.csv
- Software: Python 3.7, Jupyter Notebooks

## School District Analysis Results
The analysis of the School District Analysis show that:

How is the district summary affected?

- The district summary is affected in the following ways:
   -  The average math score decreased by 0.1 points to 78.9%
   -  The average reading score was unaffected.
   -  The percentatge of students passing math decreased by 0.2 points to 74.8%
   -  The percentatge of students passing reading decreased by 0.1 points to 85.7%
   -  The overall percentage of passing studends decreased by 0.3 points to 64.9%

This can be seen in Figures 1 & 2:
### Figure 1: Original School District Analysis
![Original](https://github.com/Jarney903/School_District_Analysis./blob/main/Resources/Original_School_District_summary.png)
<br />

### Figure 2: New School District Analysis
![New](https://github.com/Jarney903/School_District_Analysis./blob/main/Resources/New_School_District_Summary.png)
<br />

How is the school summary affected?
- The individual school summary was affected minimmaly. 
  -   The math average math, reading, and overall passing percentage changes are all less than 1%

This can be seen in Figures 3 & 4:
### Figure 3: Original School Summary
![Original](https://github.com/Jarney903/School_District_Analysis./blob/main/Resources/Original_School_Summary.png)
<br />

### Figure 4: New School Summary
![New](https://github.com/Jarney903/School_District_Analysis./blob/main/Resources/New_School_Summary.png)
<br />


How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- The individual school performance in relation to other schools was affected minimmaly. 
  -   In both studies, Thomas High School is #2 in the top performing schools.

This can be seen in Figures 5 & 6:
### Figure 5: Original Top 5 School
![Original](https://github.com/Jarney903/School_District_Analysis./blob/main/Resources/Original_Top_5_schools.png)
<br />

### Figure 6: New Top 5 Schools
![New](https://github.com/Jarney903/School_District_Analysis./blob/main/Resources/New_Top_5_Schools.png)
<br />

How does replacing the ninth-grade scores affect the following:
1. Math and reading scores by grade
    - Only 9th grade scores differ in that the new 9th grade scores are not in the data, reading NaN

2. Scores by school spending
    - The score by school spending was changed very little, all variable metrics changes by less than a percent. 

This can be seen in Figures 7 & 8:
### Figure 7: Original Schools by Spending
![Original](https://github.com/Jarney903/School_District_Analysis./blob/main/Resources/Original_Spending_Summary.png)
<br />

### Figure 8: New Schools by Spending
![New](https://github.com/Jarney903/School_District_Analysis./blob/main/Resources/New_Spending_Summary.png)
<br />

3. Scores by school size
    - The score by school size was changed very little, all variable metrics changes by less than a percent. 

This can be seen in Figures 9 & 10:
### Figure 9: Original Schools Size
![Original](https://github.com/Jarney903/School_District_Analysis./blob/main/Resources/Original_School_Size_Summary1.png)
<br />

### Figure 10: New Schools by Size
![New](https://github.com/Jarney903/School_District_Analysis./blob/main/Resources/NEW_School_Size_Summary.png)
<br />

4. Scores by school type
    - The score by school type was changed very little, all variable metrics changes by less than a percent. 

This can be seen in Figures 11 & 12:
### Figure 11: Original Schools by Type
![Original](https://github.com/Jarney903/School_District_Analysis./blob/main/Resources/Original_School_by_Type.png)
<br />

### Figure 12: New Schools by Type
![New](https://github.com/Jarney903/School_District_Analysis./blob/main/Resources/New_School_by_Type.png)
<br />

## School District Analysis Summary
Summarize changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs
   -  The math and reading scores for ninth graders are no longer in the analysis
   -  The school summary for Thomas High School is affected in the following ways:
         -  The average math score decreased by 0.07 points to 83.35%
         -  The average reading score increased by 0.05 points to 83.89%
         -  The percentatge of students passing math decreased by 0.1 points to 93.18%
         -  The percentatge of students passing reading decreased by 0.3 points to 97.02%
         -  The overall percentage of passing studends decreased by 0.3 points to 90.63%
   -  The district summary is affected in the following ways:
         -  The average math score decreased by 0.1 points to 78.9%
         -  The percentatge of students passing math decreased by 0.2 points to 74.8%
         -  The percentatge of students passing reading decreased by 0.1 points to 85.7%
         -  The overall percentage of passing studends decreased by 0.3 points to 64.9%
