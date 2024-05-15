# People Analytics:- Employee Turnover, Performance and Engagement Analysis
Analysis of People’s data using the PowerBI tool

![Demo 1](https://github.com/SmitaPinjan/People-Analytics--Employee-Turnover-Performance-Analysis/assets/152721562/2be762a7-4d58-4d5f-827f-2a533264c362)


### Table of Contents

- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Data Analysis](#data-analysis)
- [Insights](#insights)
- [Recommendations](#recommendations)
- [References](#references)

---

### Project Overview
---
This data analysis project aims to provide insight into the People’s Data analysis. By analyzing various aspects of the People data, I seek to identify the trends and patterns related to New Hires, Retention, Separation, and Turnover. Also, I am trying to gain a deeper understanding of metrics such as Employee Engagement, Satisfaction, and Performance rating using a Performance Tracker.

### Problem Statement
As per a European survey, "Publically traded European companies with mature people analytics, show an increase in 51% of return in equity and 48% higher operating margins than the average.”

People or employees are real assets of an organization. So, providing more attention to retaining talents than letting them turnover will save turnover costs and enhance productivity and efficiency. 
People analytics helps business leaders, HR partners, and stakeholders to make informed decisions.

- Task- Use the people data set provided for this project and analyze that to understand the data and terms and provide actionable insights.
- The primary goal of this project is to build a data model to monitor different KPIs, and metrics and determine what factors caused attrition.

### Data Sources 

- HR Data: The primary datasets used for this analysis are different Excel files containing employee information. One is the fact table and the other represents the dimension tables. This project was a capstone project of advanced skill development course. 

### Tools 
Tools used for Data Cleaning, Data Analysis, and Report generation :
- PowerBI

### Data Cleaning

In the initial data preparation phase, I performed the following tasks:
- Data loading and inspection,
- Changing data types,
- Optimizing the dataset by removing unnecessary and duplicate columns,
- Standardizing abbreviations used in the dataset,
- Handling missing values,
- Data cleaning and formatting,
- Managing Relationships between different tables.
- For this dataset, I have created a snowflake data model and created a new date table to help with using time functions efficiently throughout the analysis.

### Data Analysis

Data Analysis involved exploring the HR data to answer key questions, such as:

- Identify different trends and patterns
- Perform the demographic segmentation for further analysis and provide recommendations
- Develop a report indicating the KPI and metrics related to people’s data
- Do in-depth analysis and provide insights indicating which departments have high attrition rates and how we can reduce the attrition rates or improve retention rates.
- Customized dashboard.

### Insights

##### The Analysis results are summarized as follows: 
##### 1. The company had an almost equal number of males, females, and others from all ethnic groups. This indicates the company promoted and achieved a diverse, inclusive, and more balanced workforce. 
##### 2. Company showing turnover rate of 16%. It was high during 2016 & 2020. 
##### 3. The sales department followed by the HR department showed the highest turnover rates especially employees working as a Sales Representative and recruiter positions.
##### 4. The age group of 30 or less, male and single especially those working overtime and frequent travellers showed the highest turnover.
##### 5. Multiple & mixed groups showed the lowest salary which may be indicative of compensation bias.
##### 6. The performance tracker showed that the employees under the age group of 24 with the highest satisfaction in terms of “Job”, “Environment”, “Relationship” and “Work-life balance”  showed the highest performance over the year and the company was able to retain them.

Detailed analysis (with visualization) is explained in detail below:
#### Overview: 
-	The company had over 1470 total employees, 1233 were active and 237 employees left the company. 
-	The company had higher headcounts in technology (67%) than sales (29%) and HR (4%).
-	The sales department had the highest turnover rate of 21%, especially during 2013, 2018, & 2020. Then the HR department had a 19% turnover rate during the same period.  The technology department had a high number of new hires and a 14% turnover rate every year except 2015 & 2017.
-	Over the past few years, from 2012 to 2022, every year company hired new employees with the highest number of new hires in 2022, and most left the company during 2020 contributing to a 22% attrition rate. So, in 2020, the Covid-19 pandemic affected millions of people worldwide so that can be one of the reasons.
  
![Overview 1](https://github.com/SmitaPinjan/People-Analytics--Employee-Turnover-Performance-Analysis/assets/152721562/e4b5dfa2-9304-4b12-988d-a6cdd560c4a1)

-	The second highest attrition was in 2016, so need to check what happened during 2016 that caused 21% turnover. It can help the company to identify root causes, adding it to a risk register that will help the company prevent similar situations in the future.
-	Also, 2015 & 2017 had good retention rates so need to check those situations that influenced employee retention.

![Overview 2](https://github.com/SmitaPinjan/People-Analytics--Employee-Turnover-Performance-Analysis/assets/152721562/b5b22328-1b9d-4faa-9ba8-a2dcd5357e5b)

#### Demographic Segmentation Analysis :
-	The company had more employees in the Age group of 30 and less. Therefore the same age group contributed to a high (77%) turnover in the same age group especially those who were single and male.  
-	Females were more than males by 2.7%. Non-binary employees made up 8.5% of total employees. So Company had achieved its mission of creating a balanced, diverse, and inclusive workforce.
-	However, the company had more white-origin(59%) employees and had the highest average salary of $115K or more. Multiple or mixed groups had the lowest average salary of $106K. 

![Demo 1](https://github.com/SmitaPinjan/People-Analytics--Employee-Turnover-Performance-Analysis/assets/152721562/fc412b6f-6390-4c7f-b41f-8c3b238c1b00)

-	Interestingly, White employees who left the company had an average salary of $92K which was higher than the mixed group with the lowest average salary of $57K. So, this indicated that Multiple and mixed groups might feel underpaid. 
-	54% of Single Employees that left had the lowest salary of 45K within Multiple and mixed age groups and had the lowest salary of 84K in white ethnicity.

![Demo 2](https://github.com/SmitaPinjan/People-Analytics--Employee-Turnover-Performance-Analysis/assets/152721562/edee7fdd-598a-4560-a1e5-9eafa035c982)


#### Attrition Analysis:
-	The company had on average 16% attrition rate.
-	As analyzed previously, the Sales department had the highest 21% attrition rate. The Sales representatives, followed by the recruiter and data scientist were more likely to leave the company.
-	It is also notable that recent employees with less tenure than 2 years were more likely to leave.
-	Interestingly, the employees who needed to travel more frequently had the highest attrition rate despite only making 19% of new hires.

![Att 1](https://github.com/SmitaPinjan/People-Analytics--Employee-Turnover-Performance-Analysis/assets/152721562/0160395b-12f3-4b36-b7d9-e5b7af36eaf8)

-	Employees working overtime were showing a 31% turnover rate.
-	On average Highest attrition recorded during 2016 & 2020. 
-	However, those who worked overtime showing a 31% attrition rate, and were frequent travelers had the job title of Sales representatives, recruiters, and software engineers. The turnover was highest during 2013, 2016 & 2020 and lowest during 2017.

![Att 2](https://github.com/SmitaPinjan/People-Analytics--Employee-Turnover-Performance-Analysis/assets/152721562/74693529-59da-42c5-a414-aa2cc7f35e03)

#### Performance Analysis:

-	Performance analysis shows employee engagement, satisfaction, and performance ratings. 
-	For instance, Celestine joined the company in 2017 and was showing good job and relationship satisfaction. They were showing the highest job, environment, relationship, and work-life balance. Therefore showed better performance over the years and the company was able to retain them over the years.
  
![Performance 1](https://github.com/SmitaPinjan/People-Analytics--Employee-Turnover-Performance-Analysis/assets/152721562/9b3bee45-4a03-42b5-9bc9-887f18ac40ec)
 
-	Similar to them, employee Heywood joined in 2018 and continued to work as he was showing the highest job, environment, work-life, and relationship satisfaction which kept enhancing his performance over the years and the company was able to retain him.
  
![Performance 2](https://github.com/SmitaPinjan/People-Analytics--Employee-Turnover-Performance-Analysis/assets/152721562/e88a2684-77a1-4f08-b3d4-43c1a8672f69)

-	Now let's say another employee, Estele Chug joined in 2018 and showed decreased job, environment, and relationship satisfaction. It most likely affected her performance over time.
  
![Performance 3](https://github.com/SmitaPinjan/People-Analytics--Employee-Turnover-Performance-Analysis/assets/152721562/f7d39bc9-8dc7-46a1-b129-09c8fcb3f17e)

### Recommendations

Based on the analysis, I recommend the following actions:
-	The company must focus on employees under 30 working overtime and may need to travel frequently. 
- The company should check and provide fair compensation to all employees based on their job responsibilities, tenure, and performance irrespective of ethical groups, gender, or age.
-	The company should investigate the events that happened during 2013, 2016 & 2020 to analyze and improve the company environment for better retention. It may be reorganizing, downsizing, management change, the COVID-19 pandemic, or any such events that affect the company’s retention rate.
-	for employee retention, Management can look into deploying some new measures, programs, perks, or benefits for existing employees to ensure they will not leave the company.
-	The company should reward the well-performing employee. 
-	HR should review the travel and overtime policies for employees who travel more frequently and work overtime. Survey to understand how employees feel about travel frequency, working overtime, work settings, and need for learning plans. 
-	If any employee shows reduced performance or engagement and satisfaction then the team lead or HR manager should arrange a meeting and discuss their needs, and concerns, and develop a personalized improvement and career development plan. 
-	Monitor them for the next 6 months for increased engagement and performance. After 6 months again conduct a meeting and share the feedback.
-	Implement a strategy that provides quality work, job, and environment and offers a work-life balance to improve hiring and retain talented employees.

### References
- Microsoft guide for Power BI
