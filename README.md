# HR Analytics Dashboard


## Problem Statement

This HR analytics dashboard was developed to help the HR department identify key factors influencing employee attrition.Built an overview report of employee performance based on the attrition correlating it with job satisfaction and performance rating gaining insights about employee performance in particular age group and correlating it with attrition. Used SQL for data cleaning and data modeling and DAX for measures & visualization with charts, cards, table & filter.


### Steps followed 

- Step 1 : Load data into MYSQL, dataset is a Excel file, created database hr_analytics.

- Step 2 : Done cleaning in SQL i.e.:

          1] Remove any Duplicates.
          2] Remove the NULL values.
          3] Standardize the data.
          4] Remove unused Columns.

- Step 3 : After doing all the above cleaning process, done Exploratory Data Analysis and found out important business entities.

- Step 4 : Created Fact and Dimension tables using SQL.

- Step 5 : Later imported data from SQL database in Power BI for visualization.

- Step 6 : Created relationships with fact and dimension tables.
    
- Step 7 : Built multiple visualizations:

            KPI Cards: Total Employees, Avg. Job Satisfaction, Attrition Rate, Avg. Performance Rating.
            
            Donut Charts: Attrition by Education & OverTime.
            
            Bar Charts: Attrition by Age Group, Job Satisfaction vs Marital Status.
            
            Line Chart: Experience Years vs Promotion Timeline.
            
            Tree Map : Gender-wise attrition breakdown.
- Step 8 : Added department filter (slicer) for detailed role-level analysis.

     ![Image](https://github.com/user-attachments/assets/1fc19c47-48e0-4233-bd7a-d373e3a43d47)


        
- Step 9 : Conditional formatted the KPI's and overrall formatted the dashboard for better visualization.

 Snap of dashboard
 
  ![Image](https://github.com/user-attachments/assets/0d35de68-1d0e-48cc-a18c-89030eca140e)

 


# Insights

A single page report was created on Power BI.

Following inferences can be drawn from the dashboard;

### [1] Overall Attrition Metrics
     a) Attrition Rate: 15% of total workforce.
      
     b) Most attrition (74%) is observed in employees working overtime.
      
     c) Average job satisfaction is 2.73 on a scale of 5.

           
### [2] Age Group & Gender Analysis

     a) Employees aged 26-35 have the highest attrition.
      
     b) Male employees make up a slightly larger share of the workforce (60%).
         
  
### [3] Job Satisfaction & Marital Status

     a) Single employees with low satisfaction tend to leave more often.
        
     b) Married and divorced employees show relatively stable retention. 
        ### [3] Customer Analysis 





     
 
 
