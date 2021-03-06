# School District Analysis

## Overview of School District Analysis
The purpose of this analysis is to describe how the academic dishonesty in Thomas High School has affected the overall performance. 


## Results
* How is the district summary affected?

<ul>
    There is a tiny change in the district summary, so small that we can conclude that removing the 9th grade scores for math and reading from Thomas High School has not affect in the district summary.
</ul>

<img src="https://github.com/juliomeza/School_District_Analysis/blob/main/Resources/District%20Before.png">
<img src="https://github.com/juliomeza/School_District_Analysis/blob/main/Resources/District%20After.png">


* How is the school summary affected?
<ul>
    All the schools kept the same average scores and the same passing percentage except for of 'Thomas High School'.
</ul>

<img src="https://github.com/juliomeza/School_District_Analysis/blob/main/Resources/School%20Before.png">
<img src="https://github.com/juliomeza/School_District_Analysis/blob/main/Resources/School%20After.png">

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
<ul>
    After replacing all the ninth graders' math and reading scores for 'Thomas High School' with NaN, the math, reading, and the overall passing percentage for THS have decreased around 28%, but the average math and reading scores remain very similar.
</ul>

| Thomas High School | BEFORE | AFTER |
| ------------- | ------------- | ------------- |
| % Passing Math | 93.3% | 66.9% |
| % Passing Reading | 97.3% | 69.7% |
| % Overall Passing | 90.9% | 65.1% |

* How does replacing the ninth-grade scores affect the following
  * Math scores by grade
<ul>
    <ul>
        Replacing the ninth grade only affected the 'Thomas High School' 9th grade. Everything else remains the same.
    </ul>
</ul>

<img src="https://github.com/juliomeza/School_District_Analysis/blob/main/Resources/Math%20Grade%20Before.png">
<img src="https://github.com/juliomeza/School_District_Analysis/blob/main/Resources/Math%20Grade%20After.png">
  
  * Reading scores by grade
<ul>
    <ul>
        Replacing the ninth grade only affected the 'Thomas High School' 9th grade. Everything else remains the same.
    </ul>
</ul>

<img src="https://github.com/juliomeza/School_District_Analysis/blob/main/Resources/Reading%20Grade%20Before.png">
<img src="https://github.com/juliomeza/School_District_Analysis/blob/main/Resources/Reading%20Grade%20After.png">
  
  * Scores by school spending
<ul>
    <ul>
        Replacing the ninth grade affected only the $630-644 spending per student range, but can only be noticed at the decimal level, not when displaying whole numbers.
    </ul>
</ul>

<img src="https://github.com/juliomeza/School_District_Analysis/blob/main/Resources/Spending%20Before.png">
<img src="https://github.com/juliomeza/School_District_Analysis/blob/main/Resources/Spending%20After.png">

  * Scores by school size
<ul>
    <ul>
        Replacing the ninth grade has not affected the scores by school size.
    </ul>
</ul>

<img src="https://github.com/juliomeza/School_District_Analysis/blob/main/Resources/Size%20Before.png">
<img src="https://github.com/juliomeza/School_District_Analysis/blob/main/Resources/Size%20After.png">

  * Scores by school type
<ul>
    <ul>
        Replacing the ninth grade has not affected the scores by school type.
    </ul>
</ul>

<img src="https://github.com/juliomeza/School_District_Analysis/blob/main/Resources/Type%20Before.png">
<img src="https://github.com/juliomeza/School_District_Analysis/blob/main/Resources/Type%20After.png">


## Summary
1. The 9th grade was removed from the THS passing percentage analysis.
2. The THS summary values were manually updated to reflect more accurate results.
3. The differences can only be noticed after the decimal point.
4. There is not a notable difference between the average scores after removing the THS ninth grade.