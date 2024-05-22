
# HR Analytics
Dashboard link: https://app.powerbi.com/groups/me/reports/6a7a5f5f-3fc9-4a8c-bcb6-0443f0c49ac7/ReportSection?experience=power-bi

### Overview
HR Analytics involves collecting, analyzing, and interpreting data to gain insights and inform strategic decision-making about personnel. This process is crucial for organizations aiming for growth, as retaining top talent is essential for sustained success. Understanding employee satisfaction within the organization is equally important. Employees drive profit, which is vital for any business. HR Analytics enables organizations to make well-informed decisions about their workforce, ultimately contributing to overall profitability and success.
### KPI
•	% and count of employee attrition

•	Count of active employees

•	Attrition categorized by job role

•	Average monthly income of both attrition and active employees

•	Average monthly income by job role

•	Performance ratings for each department

•	Job satisfaction ratings for attrition and active employees

### Data Preparation and Analysis
The raw data was downloaded in CSV format from Kaggle and imported into Power Query within Power BI for transformation and analysis. Upon thorough inspection, the data was found to be properly formatted, with no need for additional cleaning.

To facilitate the analysis, a new column named "attrition count" was created based on the existing "attrition" column, which contained "yes" or "no" responses. In this new column, "yes" was coded as "1" and "no" as "0," and the column was formatted as a whole number to enable accurate analysis.

Additionally, for the department column, "Human Resources" was abbreviated to "HR" and "Research and Development" to "R&D" to reduce word count and improve visualization clarity.

To explore the key performance indicators (KPIs) highlighted for this HR analytics project, the data was transformed into visualizations for effective communication. Data Analysis Expressions (DAX) were used to create two measures: "Attrition Rate" and "Active Employees." These calculations were then used to compare attrition and active employee metrics against other variables to uncover correlations and insights.

![HR Analytics Dashboard](https://github.com/estherwonder/HR-Analytics-/assets/145384641/91bb6e30-214b-4a04-91fc-e30b6a0b29d1)

### Insights
This analysis provides a comprehensive overview of employee attrition, performance, and job satisfaction, highlighting key areas for potential improvement in employee retention and engagement strategies.

•	Overall Attrition: Out of a total of 1,480 employees, 238 have left the company, resulting in a significant attrition rate of 16.1%. The remaining 1,242 employees are currently active.

•	Departmental Attrition: The Research and Development (R&D) team has the highest number of both attrition and active employees, with 133 and 834 respectively, translating to an attrition rate of 19%. Meanwhile, the Sales department has the highest attrition rate at 20.7%.

•	Role-specific Attrition: The roles with the highest attrition counts are Laboratory Technician (62), Sales Executive (58), Research Scientist (47), and Sales Representative (33).

•	Income Comparison: Employees who left the company had an average monthly income of $4,812.58, which is notably lower than the $6,829.29 average monthly income of active employees. This suggests that income level may be a factor in employee retention

•	Roles with Lowest Attrition: The job roles with the least attrition—Manufacturing Director, Manager, Healthcare Representative, and Research Director—also have the highest average monthly incomes. Conversely, roles with the highest attrition tend to have lower average monthly incomes.

•	Performance Ratings: The Research and Development department boasts the highest performance ratings, with 65.52% of employees rating their performance highly.

•	Job Satisfaction among Attrition: Among employees who left, job satisfaction ratings of 1 and 3 are the most common, with 67 employees rating 1 and 73 rating 3. This indicates a significant portion of attrition may be due to dissatisfaction with job conditions.

•	Overall Job Satisfaction: The roles of Sales Executive, Research Scientist, Manufacturing Director, Laboratory Technician, and Healthcare Representative show the highest and lowest job satisfaction ratings, likely because these roles have the highest numbers of employees. Among the 1,242 active employees, 409 rated their job satisfaction as 4, while 226 rated theirs as 1.

These insights highlight the importance of addressing department-specific issues, improving compensation where feasible, and focusing on job satisfaction to enhance retention rates. By understanding the factors contributing to attrition, the company can implement more effective retention strategies and improve overall employee satisfaction and performance.
