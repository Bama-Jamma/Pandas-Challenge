# Pandas-Challenge
Module 4 Challenge using Pandas

#School District Analysis
##Overview
The purpose of this project is to analyze school district data to provide insights into school performance and identify trends. The analysis includes a comparison of district and charter schools based on factors such as test scores and funding. The results of this analysis can be used to inform decision-making by school administrators and policymakers.

###Dependencies
This project uses the following Python libraries:

pandas
numpy
Data Sources
Written conclusion on docx file

###The analysis is based on two CSV files:

schools_complete.csv: contains information about each school in the district, including its name, type, size, and budget.

students_complete.csv: contains information about each student in the district, including their name, grade, and test scores.

###Code
The code for this project is written in Python with Jupyter Notebook. The code performs the following:

* Load the data from the CSV files into Pandas dataframes.
* Merge the dataframes into a single dataframe that contains all relevant data.
* Calculate various statistics, such as average test scores and passing rates, for the district and each school.
* Break down the data by school size, spending per student, and school type, and calculate statistics for each category.
* Format the output to display results in a readable format.

###Analysis Steps
####The analysis consists of the following steps:

* Data cleaning and merging: The two CSV files are read into Pandas dataframes and merged on the school name column.
* District summary: An overview of district-wide performance is provided, including the total number of schools and students, the total budget, and the average math and reading scores.
* School summary: A summary is provided for each school in the district, including its type, size, budget, and performance metrics such as the average math and reading scores and the percentage of students passing each subject.
* Top and bottom performing schools: The top and bottom five performing schools are identified based on overall passing rate.
* Math and reading scores by grade: The average math and reading scores are provided for each grade level (9th, 10th, 11th, and 12th) across all schools.
* Scores by school spending: The average math and reading scores and passing percentages are provided for different ranges of per-student spending.
* Scores by school size: The average math and reading scores and passing percentages are provided for different school size ranges.
* Scores by school type: The average math and reading scores and passing percentages are provided for district and charter schools.

###Conclusion
Based on the analysis, it is evident that charter schools outperform district schools across all metrics, while spending less per student. The analysis suggests that smaller class sizes in charter schools may be a contributing factor to their higher performance. Additionally, schools with smaller student populations tend to have higher overall passing rates. These findings can be used to inform decision-making in the district, such as the allocation of resources and policies to improve student outcomes.