# School District Analysis
## Overview
A chief data scientist for a city school district has given tasks to analyze and report student funding and standardized test scores as below:
- A high-level snapshot of the district's key metrics, presented in a table format.
- An overview of the key metrics for each school, presented in a table format.
- Tables presenting each of the following metrics:
  - Top 5 and bottom 5 performing schools, based on the overall passing rate.
  - The average math score received by students in each grade level at each school.
  - The average reading score received by students in each grade level at each school.
  - School performance based on the budget per student.
  - School performance based on the school size.
  - School performance based on the type of school.
- Analyze and compare the above school metrics while excluding the ninth grade reading and math scores of Thomas High School.

## Resources
- Requirements from the client
- Anaconda3-2022.05 
- Conda 4.14.0
- Jupyter Notebook 6.4.8
- ipykernel 6.9.1
- Python 3.7.13
- Pandas 1.3.5
- Numpy 1.21.5

## School District Results
The district and school summary along with other metrics  were calculated for the school district initially. Later on, the reading and math scores of **461** students in the ninth grade of Thomas High School were turned into null data due to academic dishonesty. The school metrics were recalculated to observe the impact. 

### Effect on District Summary
<tr><td> Original District Summary:</td></tr>
<tr><td><img alt=“Original District Summary” src="Resources/Original_District_Summary_Compare.png" width="800"/></td></tr>
<tr><td> Adjusted District Summary:</td></tr>
<tr><td><td><img alt=“Adjusted_District_Summary” src="Resources/Adjusted_District_Summary.png" width="800"/> </td></tr>

- The total number of schools, students and total budget for the district remained the same. 
- There is less than 1% decrease on the district's average math, average reading, passing math and passing reading percentages and also the overall passing percentages after the adjustments. The whole number percentages remain the same, when rounded. So it can be concluded that there is little to no impact on the overall school district metrics post adjustment.


### Effect on School Summary
<tr><td> Original School Summary:</td></tr>
<tr><td><img alt=“Original School Summary” src="Resources/Original_School_Summary.png" width="800"/></td></tr>
<tr><td>Adjusted School Summary: </td></tr>
<tr><td><img alt=“Adjusted School Summary” src="Resources/Adjusted_School_Summary.png" width="800"/></td></tr>

### Effect on Thomas High School's Performance
<tr><td>Results from original School Performance</td></tr>
<tr><td></td></tr>
<tr><td>Results from adjusted School Performance</td></tr>
<tr><td></td></tr>

### Effect on Grade level Math and reading scores
The scores were calculated with 10, 11, 12 th grade students. Ninth grade were excluded.
<tr>
  <td>Results from original Grade level Scores </td>
  <td></td>
  <td>Results from adjusted Grade level Scores</td>
  <td></td>
</tr>

### Scores by school spending

### Scores by school size

### Scores by school type

## School District Summary  
### Below are four changes noticed in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs:
- 
-
-
-

