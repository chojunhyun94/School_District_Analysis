# School_District_Analysis
Analysis of Student Data and Funding

## Overview
I was tasked with using Python Pandas DataFrames to clean up code and run analysis on a school district. This is a school district with over 10,000 students and 15 schools. When I received this data, there was missing information and duplicates. This is quite common in large datasets like this and so I cleaned up the data. The analysis was focused on 4 big categories: reading_score, math_score, budget, and type of school.

## Analysis
The overall result of the analysis shows that there is a small difference in math grades from charter schools and public schools, but not much difference in reading grades.

Charter schools have an average reading score of 72.45 and an average math score of 66.76.
Public schools have an average reading score of 72.28 and an average math score of 62.95.

This doesn't imply much in my opinion as the 3-4 points can be margin of error. However, a deeper analysis of math scores by grade show that results for charter school decline over time while public schools remain at a typical 64. This shows that although math scores may be better for Charter Schools on average, they worsen in quality as student advances in grade. This still have many factors as the Charter Schools may be providing more difficult course work, but it is an interesting place to look.

There seems to be not much difference in the budget for the school, which is interesting because the number of students in these schools vary from 171 (Chang High School) to 2038 (Montgomery High School). It is notable that some data was removed, but assuming it wasn't from a particular school, this is difference in population while not much difference in budget is eyecatching.
