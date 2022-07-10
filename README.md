# School_District_Analysis

# Overview of the school district analysis :

The purpose of the project is to analyze the results of fifteen high schools results of state testing math and reading scores. The task is to prepare all test data for analysis, reporting and presentation in order to provide insights about performance trends and patterns.

The data did uncover anomalies or possible evidence of academic dishonesty in regards to the ninth grade of Thomas High School. The ninth grade data for Thomas High School data needed to be removed from the analysis in order to continue with the analysis of the districts. Both math and reading scores for Thomas High School ninth grade have been replaced with no values (NaNs) while keeping the rest of the data intact.

The data will be analyzed before and after making the changes.

- The School and district summary.

- The top 5 and bottom 5 performing schools, based on the overall passing rate.

- The average math and Reading scores for each grade level from each school.

- School performance based on the budget per student

- The scores by school spending per student, by school size, and by school type.

# Resources :

- Data Source: schools_complete.csv, students_complete.csv

- Software: Python, Anaconda, Jupyter Notebook, Pandas


# Results :

- It was determined that the best course was to islolate the scores for Thomas High School 9th graders and replace their math and reading scores while keeping all other data associated with this student group intact.

- And output shows as below
![Thomas High 9th Grade NaN](https://github.com/acegal1/School_District_Analysis/blob/main/Resources/ninth_na.jpg)

- Both math and reading scores were replaced with "NaN", which represents a "Not-a-Number" value, for 461 student records. Although this may seem like a significant number, these score replacements did not alter data summaries tremendously overall

## District Summary :

![district_summary](https://github.com/acegal1/School_District_Analysis/blob/main/Resources/district_summary.jpg)

- The data remains unaffected in terms of Total Schools, Total Students and Total Budget as per above analysis.
- The data replacement did not change the math and reading scores by grade.
- The average math and reading score summaries were stratisfied by school and grade level. 

## School Summary :

- The calculation Per School Budget & Per Student Budget output is below and inlcudes the metrics for Thomas High School:

![perschool_perstudent_budget.jpg](https://github.com/acegal1/School_District_Analysis/blob/main/Resources/perschool_perstudent_budget.jpg)

- Average Math Score and Average Reading scores for Thomas High School changed drastically from 83.42 to 59.85 and 83.85 to 60.24 respectively after the change of Data.

## Replacing the ninth graders’ math and reading scores affected Thomas High School’s performance drastically when compared to other schools.

Ninth Grader Maths scores

![Ninth_Grade_Math](https://github.com/acegal1/School_District_Analysis/blob/main/Resources/Ninth_Grade_Math.jpg)

Ninth Grader Reading scores

![Ninth_Grade_Read](https://github.com/acegal1/School_District_Analysis/blob/main/Resources/Ninth_Grade_Read.jpg)


- As per above anylysis we can conclude that average math 83.6% and reading scores 83.7% of Thomas High School are now zero. 


## Replacing the ninth-grade scores affect the following:

### Math and reading scores by grade
- Here are our Top 5 Schools as per math and reading scores and avereage percentage 

![top5shools](https://github.com/acegal1/School_District_Analysis/blob/main/Resources/top5schools.jpg)

- Here are our Bottom 5 Schools as per math and reading scores and avereage percentage 

![bottom5shools](https://github.com/acegal1/School_District_Analysis/blob/main/Resources/bottom5schools.jpg)

### Scores by school spending summary

![school_spending](/Resources/school_spending.jpg)

![student_spending](/Resources/student_spending.jpg)

- The data suggests that the above output, schools that spent between <$584 appear to have the best-performing students in math and reading. So the schools which spent the lowest are the highest performing shcool in Math & Reading.

### Scores by school size

![scores_schoolsize.jpg](/Resources/scores_schoolsize.jpg)

- Scores by school size were calculated by determining size ranges for all 15 schools in the district:

- Small (<1000) -Medium (1000-2000) -Large (2000-5000)

- When considering School Sizes, "Large" Schools (Over 2,000 Students) have the lowest average scores and passing percentages. The difference in performance between "Small" and "Medium" Size Schools is negligible (approximately 1%). Interestingly, all District schools in this dataset are characterized as "Large" schools. This may be an indication that students in this district learn and perform better in smaller, more intimate settings.

### Scores by school type (Charter vs District Schools)

![charter_v_district.jpg](/Resources/charter_v_district.jpg)


- Charter schools performed better than District schools in this analysis. The top five schools with the highest overall passing percentages are all Charter schools, whereas the bottom five are all District Schools. Charter schools in this dataset were typically characterized as "Small" and "Medium" size schools. As seen in the DataFrame below, Charter schools have a 36% higher overall passing percentage than District schools.

# Summary :

- Replacing the ninth graders scores with NaN caused Thomas High School's overall passing percentages and average scores to dropped.
-The district also had its average math and reading scores decrease, as well as the overall passing percentage for students. And Thomas High School lost its placement as a top five school within this District.
- However, when th total student counts excluded the Thomas High School ninth graders and by omitting their scores from the dataset, Thomas High School regained its high average scores and retained its position as the number two school in the District.


