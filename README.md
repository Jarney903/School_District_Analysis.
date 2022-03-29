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
![Original]()
<br />

### Figure 2: New School District Analysis
![New]()
<br />

How is the school summary affected?
- The individual school summary was affected minimmaly. 
  -   The math average math, reading, and overall passing percentage changes are all less than 1%

This can be seen in Figures 3 & 4:
### Figure 3: Original School Summary
![Original]()
<br />

### Figure 4: New School Summary
![New]()
<br />


How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- The individual school performance in relation to other schools was affected minimmaly. 
  -   In both studies, Thomas High School is #2 in the top performing schools.

This can be seen in Figures 5 & 6:
### Figure 5: Original Top 5 School
![Original]()
<br />

### Figure 6: New Top 5 Schools
![New]()
<br />

How does replacing the ninth-grade scores affect the following:
1. Math and reading scores by grade
    - Only 9th grade scores differ in that the new 9th grade scores are not in the data, reading NaN

2. Scores by school spending
    - The score by school spending was changed very little, all variable metrics changes by less than a percent. 

This can be seen in Figures 7 & 8:
### Figure 7: Original Schools by Spending
![Original]()
<br />

### Figure 6: New Schools by Spending
![New]()
<br />

3. Scores by school size
    - The score by school size was changed very little, all variable metrics changes by less than a percent. 

This can be seen in Figures 9 & 10:
### Figure 9: Original Schools Size
![Original]()
<br />

### Figure 10: New Schools by Size
![New]()
<br />

4. Scores by school type
    - The score by school type was changed very little, all variable metrics changes by less than a percent. 

This can be seen in Figures 11 & 12:
### Figure 11: Original Schools by Type
![Original]()
<br />

### Figure 12: New Schools by Type
![New]()
<br />


 

## School District Analysis Summary
The "PyPol_Challenge.py" script provided in the Git Hub Election_Analysis repository can be used to audit any election with some modification.
- Overview of modifications required are:
  - For future loading of results to the script provided, ensure in line #9: file_to_load = os.path.join("Resources", "election_results.csv") that the subfolder containing the election results CSV file are correctly input using the correct file path, folder name, and file name. In this instance, the “Resources” folder was a direct subfolder within the main folder holding the "PyPol_Challenge.py" 

