# HR-analytics.ipynb

# Introduction
This project focuses on HR analytics to understand employee attrition and the factors contributing to it. By analyzing employee data, we aim to identify patterns and provide suggestions to reduce employee turnover.

# Table of Contents
Introduction
About the Dataset
Data Preprocessing
Data Visualization
Key Insights and Recommendations
Conclusion

# About the Dataset
The dataset used in this analysis contains various features related to employees, such as their projects, average monthly hours, time spent in the company, work accidents, promotions, department, and salary. The key features include:

satisfaction_level: Employee satisfaction level
last_evaluation: Last evaluation score
numberOfProjects: Number of projects handled by the employee
avgMonthlyHours: Average monthly working hours
timeSpent.company: Time spent in the company (years)
workAccident: Whether the employee had a work accident
left: Whether the employee left the company
promotionInLast5years: Whether the employee was promoted in the last 5 years
dept: Department of the employee
salary: Salary level (low, medium, high)

# Data Preprocessing

# Loading Data:
The dataset was loaded into a pandas DataFrame for inspection.

# Cleaning Data:
Checked for missing values and handled them.
Reviewed the data types and ensured they were appropriate.
Identified and removed duplicate records to ensure data quality.

# Data Visualization

# Correlation Matrix and Heatmap:
Generated a correlation matrix to understand the relationships between different features.
Visualized the correlation matrix using a heatmap.

# Count Plots:
Created count plots to visualize the distribution of various features and their relationship with employee attrition.

# Key Insights and Recommendations

# Number of Projects:
Employees handling very few (2 projects) or too many projects (7 projects) are more likely to leave.
Recommendation: Redistribute projects from overloaded employees to those handling fewer projects.

# Average Monthly Hours:
No clear inference could be made from the distribution of average monthly hours.

# Time Spent in Company:
Employees tend to leave after 3-5 years of experience.
Recommendation: Provide supervisory roles and incentives for employees who complete 4-5 years to retain them.

# Work Accidents:
Work accidents do not appear to be a significant factor in employee attrition.

# Promotions in the Last 5 Years:

Employees who haven't been promoted in the last 5 years are more likely to leave.
Recommendation: Implement a regular promotion cycle to retain employees.

# Department:
Employees in the sales, technical, and support departments have higher attrition rates.
Recommendation: Offer opportunities to move to other departments, provide incentives, and organize team-building activities to reduce stress.

# Salary:
Employees with low or medium salaries are more likely to leave.
Recommendation: Implement regular salary hikes based on experience, promotions, and incentives.

# Conclusion
The analysis provided valuable insights into the factors contributing to employee attrition. By addressing these factors with targeted recommendations, companies can improve employee retention. Key strategies include redistributing workloads, providing regular promotions and salary hikes, offering career development opportunities, and organizing team-building activities to reduce stress. These measures can help create a more satisfying and supportive work environment, reducing turnover rates and improving overall organizational performance.
