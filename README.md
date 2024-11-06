# -LITA-CLASS-DOCUMENTATIONS-
FIRST PROJECT WITH INCUBATOR HUB


[PROJECT OVERVIEW](#project-overview)

 [DATA SOURCE](#data-source)
 
 [TOOLS USED](#tools-used) 



---


### ***PROJECT OVERVIEW***

 ***This data analysis project aims to provide comprehensive insights into the process of cleaning, analyzing, and visualizing data using tools such as Excel, SQL and Power BI. By leveraging these platforms I gained hand-on experience in manipulating datasets,performing advanced queries and creating interactive  visualizations, The project enabled a deeper understanding of data analysis techniques and tools, equipping me with the skills neccessary to derive meaningful insights and make data-driven decisions***

### ***DATA SOURCE***

 ***The primary source of data used in this project is obtained from an open-source platform, The data is publicly available and can be freely downloaded from reputable online repositories such as Kaggle [Download Here](https://www.kaggle.com) or other trusted data repositories. These platforms offer diverse datasets that are widely used for research, analysis and educational purposes***.

---
### ***TOOLS USED***
- **Microsoft Excel*** [dowload Here](https://www.microsoft.com) 
1. ***For data cleaning***
2. ***For Analysis***
3. ***For data visualization***
   
- ***SQL-STRUCTURE QUERY LANGUAGE for Querying Data***
  
  
- ***PowerBI***

---
 #### ***Data Cleaning and Preparations***
  ***In the inital phase of the data cleaning and preparations we performed the following actions***
  
1. ***Data Loading and Inspection***
- ***Imported datasets and examined them for quality and structure***.

2. ***Handling missing variables***
- ***Identified and addressed missing values to maintain data integrity***

3. ***Data cleaning and formatting***
- ***Applied formatting rules and standardized data entries to ensure consistency***.    
    
---
  #### ***Exploratory Data Analysis***
  ***This phase involved exploring of the data to answer some specific questions, including***:
  -  ***calculating SUM and AVERAGE Values, using functions such as***:
```
 =sum(A1:A35)
 =AVERAGE(A1:A35)
```
    
-  ***Identifying Top Ten Highest and Lowest Sallers,using functions like***:
```
 =MAXIFS(range, criteria_range, criteria)
 =MINIFS(range, criteria_range, criteria)
```

 ---



 #### Analyzing Sales Data In Excel:

- ***Region and Market:*** Understanding the geographical and market contexts can help identify high-performing areas and potential growth opportunities.

- ***Store and Trade Date:*** Pinpoints the exact location and timing of each transaction, which is crucial for analyzing sales patterns and trends over time.

- ***Fiscal Period:*** Helps align the sales data with financial reporting periods, aiding in accurate financial analysis.

- ***Model:*** Identifies the product involved, which is essential for product-specific performance reviews.

- ***Line of Business:*** Shows the type of business activity, helping categorize the transactions and understand the nature of sales.
  
- ***Day Category:*** Differentiates between sales on workdays and public holidays, useful for analyzing the impact of holidays on sales.

- ***Revenue:*** Provides the financial outcome of each transaction, critical for assessing the overall financial health and profitability.

- ***Units Sold:*** Offers insights into the volume of sales, which is important for inventory management and demand forecasting.

- ***Transaction Category:*** Categorizes transactions, which can be used to prioritize sales efforts and tailor strategies based on transaction types.

***By examining these details,I gained a deeper understanding of sales performance, identify trends, and make data-driven decisions to optimize business operations.***


#### Analysing Sales Data Using The Pivot Table.

***1. TOTAL REVENUE BY REGION***


**Analysis**
- ***Key Insight:*** The North East region leads with the highest revenue, suggesting it’s a major market for the business.

- ***Strategic Implication:*** Focusing marketing and resources here could be advantageous.

- ***Contrast:*** The North Central region has the lowest revenue, indicating a need for strategy reassessment or growth initiatives.


***2. UNIT BY THE LINE OF BUSINESS*** 

***Analysis***
- ***Key Insight:*** Parts sales dominate, showing a high demand for replacement parts or components.

- ***Strategic Implication:*** Ensuring a robust supply chain and inventory for parts could sustain and grow this segment.

- ***Contrast:*** Copier sales are the lowest, which might point to a declining product category or market saturation.

**3. BOTTOM FIVE STORES BY UNIT SOLD**

***Analysis***

- ***Key Insight:*** Boki and Kwali have the lowest sales units.

- ***Strategic Implication:*** These stores might need more localized marketing, promotions, or an assessment of product relevance to boost sales.

- ***Contrast:*** Akinyele, while still low, has significantly higher units sold compared to the others on this list, indicating a potential for growth.

**4. REGION BY UNIT SOLD**

***Analysis***
- ***Key Insight:*** The North East region not only leads in revenue but also in the number of units sold.

- ***Strategic Implication:*** It could be worth investigating what drives such high performance in this region—product preference, population demographics, economic factors, etc.

- ***Contrast:*** North Central has the lowest units sold, aligning with its lower revenue.

**5. TOP 10 STORE BY REVENUE**

***Analysis***

- ***Key Insight:*** Ankpa is the top-performing store by revenue.

- ***Strategic Implication:*** Investigating successful strategies used by Ankpa could help replicate success in other stores.

- ***Contrast:*** Each of the top 10 stores has significant revenue, showcasing their importance in the overall business performance.

**6. REGION BY AVERAGE REVENUE**

**Analysis**

- ***Key Insight:*** North Central has the highest average revenue per unit sold, indicating high-value sales despite lower overall revenue.

- ***Strategic Implication:*** This suggests that North Central customers might prefer higher-end products or services.

- ***Contrast:*** North West, while having lower average revenue, still contributes significantly to overall sales, indicating a more volume-based sales strategy.

***Analysis of Revenue by Year***

***Overview***
The table provides a monthly breakdown of revenue for the years 2014 and 2015. This helps identify patterns and trends over these two years, offering insights into peak and low revenue periods. 

***Analysis for 2014***

- ***Highest Revenue Month:*** **October (₦4,163,860,480)** Indicates a peak in sales, possibly due to a successful marketing campaign or seasonal demand.

- ***Lowest Revenue Month:*** **August (₦3,958,927,680)** Suggests a period of lower activity, which may be typical for the business cycle or due to external factors.

- ***Steady Performance:*** The revenue figures show relatively stable performance throughout the year, with minor fluctuations.

#### Analysis for 2015 Data

- ***Consistency:*** The revenue figures for the first six months of 2015 demonstrate consistent sales performance, with each month achieving over ₦4 billion in revenue.

- ***Trends:*** March saw the highest revenue within this period, possibly indicating a successful campaign or an uptick in demand during that month.

- ***Performance:*** The consistent high revenue suggests that the business maintained strong performance and effective strategies throughout the first half of the year.


#### Yearly Comparison and Trend Analysis
***2014 vs. 2015:*** 

Comparing the revenue data for the available months of 2015 to the corresponding months in 2014, there seems to be a consistent trend of high performance, suggesting successful business strategies and a strong market presence.

 - ***Growth Potential:*** The consistent and high revenue in the early months of 2015 indicates potential for growth and sustained high performance if similar trends continue throughout the rest of the year.

***Conclusion
This table provides a clear view of monthly and yearly revenue performance, highlighting peak periods and stable trends. By analyzing these patterns, the business can make informed decisions on inventory, marketing strategies, and resource allocation to capitalize on high-demand periods and address lower revenue months.***



#### Analysis of the Pivot Chart


***Revenue by Region Chart***

***Type:*** Vertical Bar Chart

***Regions:*** North Central, North East, North West, South East, South South, South West


***Key Insights:***

- North East generates the highest revenue, suggesting a dominant market in that region.

- North Central shows the lowest revenue, highlighting a potential area for growth or re-evaluation of strategies.

***Visualization Impact:***

- Bar heights visually represent the revenue contributions, making it easy to compare the performance of different regions at a glance.

- Units Sold by Region Chart
Type: Horizontal Bar Chart

-Regions: North Central, North East, North West, South East, South South, South West


***Key Insights:***

- South West leads in units sold, indicating high consumer engagement or product popularity in that region.

- North Central lags in units sold, mirroring its revenue performance.

***Visualization Impact:***

Bar lengths show the number of units sold, providing a clear comparison across regions. This helps identify where products are moving fast and where they are not.

***Slicer Analysis***
- Trade Date Slicer
Location: Right-hand side of the pivot charts.

***Function:***

**Controls Both Charts:** This slicer filters the data displayed in both the "Revenue by Region" and "Units Sold by Region" charts based on selected trade dates.

**Interactive Filtering:** Dates range from 28-Feb-14 to 07-Mar-14. Users can click on specific dates to view data for those periods, allowing for detailed temporal analysis.

***Impact:***

- Dynamic Insights: Enables users to slice the data by date, providing a focused view of performance for specific periods. This helps in understanding daily sales trends and the impact of short-term events or promotions.

- Strategic Analysis: By examining sales on different dates, users can identify peak sales days, evaluate the effectiveness of marketing campaigns, and make data-driven decisions.

***Conclusion
The combination of these pivot charts and the interactive slicer offers a comprehensive and flexible tool for analyzing sales performance across different regions and time periods. It allows for quick visual comparisons and in-depth temporal analysis, aiding in strategic planning and decision-making.***




#### Visualization Image:
![9c4750b3-266f-4cc1-abdc-63d044e50159](https://github.com/user-attachments/assets/73a5997e-cb15-4aaf-ac43-59079a5724c9)



![d21453ec-84e5-47f9-b7a7-bd28064e3375](https://github.com/user-attachments/assets/f7e47611-af54-469c-a447-9028dc0012cf)



![e48919d6-e1bd-408b-825d-26c5d12ba546](https://github.com/user-attachments/assets/ea1b74fc-f105-493e-9561-1a44c6709a74)



  
 ### Data Analysis With SQL And Power BI.
 
 This section we included basic lines of code or queries using ***SQL*** and some of the Database expressions[DAX] used during data analysis with ***POWER BI***
 
 ---SQL Example---
    
 ```
  SELECT * FROM TABLE
 WHERE CONDITION =TRUE
```
    

---

***QUERIES USED IN SQL TO CREATE,MANIPULATE AND ANALYZE EMPLOYEE TABLE.***

 Here I starting with the creation of a table called EMPLOYEE. This foundational step involved defining various columns to store employee-related data. Once the table was set up, I began experimenting with different SQL operations. using aggregate functions like ***SUM(), AVG(), COUNT(),*** and more to perform arithmetic operations on the data. To further enhance my skills, I explored SQL operational functions to ***join tables, unite datasets,*** and analyze the information. These operations allowed me to combine data from multiple sources,***Like joining the employee table to salary table*** create unions of datasets, and draw meaningful insights from the table. Through this approach, I built a solid understanding of SQL and its powerful data manipulation capabilities.

 ***IMAGE OF QURIES USED TO MANIPUALATE THE DATABASE***

 
![Screenshot 2024-11-04 114844](https://github.com/user-attachments/assets/d6486ce8-6c83-44fd-ab6a-52107a7a1fa9)



![Screenshot 2024-11-04 115030](https://github.com/user-attachments/assets/8300752e-7271-405e-96bf-e76e5d7c0e02)


![Screenshot 2024-11-04 115207](https://github.com/user-attachments/assets/a2cdb230-1026-488c-bdca-714620387948)




### ***POWER BI (Power Business Intelligence)***

Here the aim to understand data better and to create meaningful visualizations. I installed Power BI Desktop and began exploring its interface, learning the basics by navigating through its various panes and views.

#### Exploring Basic Concepts

***First Dataset:*** I started with a simple Excel file containing sales data. Importing this into Power BI, I learned how to connect to data sources and bring data into the Power BI environment.

***Power Query Editor:*** Next, I delved into Power Query Editor, a powerful tool within Power BI for cleaning and transforming data. I practiced removing duplicates, filtering rows, and creating new columns, which was essential for preparing my data for analysis.

#### Building Basic Visualizations

***Creating Visuals:*** With my cleaned data, I began creating basic visualizations. I experimented with bar charts, line charts, and pie charts, using my sales data to understand how different visuals could represent the data effectively.

***Using Different Datasets:*** To broaden my skills, I imported various datasets, such as stock prices and weather data. This exposed me to different data structures and helped me learn to create visualizations tailored to each dataset.

***Advanced Visualizations and Features***
Relationships: I then explored creating relationships between different tables. For example, I linked sales data with customer demographics, allowing me to perform more complex analyses and visualize interconnected data.

***Calculated Columns and Measures:*** Using calculated columns and measures, I learned to perform advanced calculations. For instance, calculating total sales per region helped me understand the power of DAX (Data Analysis Expressions).

#### Interactive Dashboards

***Creating Dashboards:*** Combining multiple visuals, I created interactive dashboards that provided comprehensive insights. I added slicers and filters to make the dashboards dynamic and user-friendly.

***Publishing to Power BI Service:*** I published my dashboards to the Power BI service, enabling me to access them from anywhere and share them with others.

#### Advanced Techniques

***Real-Time Data:*** Integrating real-time data feeds, such as social media metrics, showed me how Power BI handles live data, making my dashboards even more relevant and timely.

***Custom Visuals:*** I explored the Power BI marketplace for custom visuals, adding unique charts and maps to my reports, enhancing the overall appeal and functionality of my dashboards.

#### Analysis Of The HR Data: 

***Overview***
The table provides detailed information about employees, including their attrition status, travel frequency, age band, attrition label, department, education field, employee number, gender, job role, and marital status. I used this data to understanding employee demographics, attrition rates, and various HR-related metrics.

***DASHBOARD EXPLANATION:***

The dashboard titled "LADIES IN TECH HR DATA ANALYSIS TRACKER" provides a comprehensive overview of employee attrition in the company. Here are the key highlights:

Key Metrics:
Total Number of Employees: 1,470

Total Number of Attrition Count: 237

Total Number of Current Employees: 1,233

Attrition Rate: 16%

Average Age: 37

Attrition Count by Department:
HR: 12

Sales: 92

R&D: 133

Attrition Count by Education Field:



Attrition Count by Education Field:
Life Sciences: 89

Medical: 63

Marketing: 35

Technical Degree: 32

Other: 11

Human Resources: 7

Count of Attrition by Gender:
Male: 588 (40%)

Female: 882 (60%)

Attrition Based on Age Group and Gender:
Under 25:

Female: 20

Male: 38

25-34:

Female: 69

Male: 112

35-44:

Female: 37

Male: 51

45-54:

Female: 16

Male: 25

Over 55:

Female: 8

Male: 9

Key Insights:
The attrition rate stands at 16%, with a total of 237 employees having left the company.

Sales and R&D departments have the highest attrition counts, indicating possible areas needing attention in terms of employee retention strategies.

Life Sciences and Medical are the education fields with the most attrition
suggesting a trend worth investigating further.

Females constitute 60% of the total employees, but the overall attrition count shows more males leaving compared to females.

The 25-34 age group has the highest attrition, particularly among males, highlighting a critical demographic for retention efforts.

This visualization helps the company understand the distribution and trends in employee attrition, guiding strategic decisions to improve retention and address specific areas of concern.



***Conclusion:***
Impact of Attrition and Recommended Actions
Impact of Attrition on the Company

***Operational Disruption:***

High attrition rates, particularly in key departments like Sales and R&D, can disrupt daily operations and impact project timelines and sales targets.

***Increased Costs:***

Recruiting and training new employees to replace those who leave is costly. These expenses can strain the company's budget and divert funds from other critical areas.

***Loss of Expertise:***

The departure of experienced employees means a loss of valuable knowledge and skills. This can affect the quality of work and slow down innovation and growth.

***Employee Morale:***

High attrition can lead to lower morale among remaining employees. Seeing colleagues leave frequently may cause stress and uncertainty, affecting overall productivity and workplace satisfaction.

***Customer Satisfaction:***

Inconsistent staffing, especially in customer-facing roles, can lead to lower service quality and negatively impact customer relationships and satisfaction.


***Recommended Actions to Address Attrition***


- ***Improve Employee Engagement:**

Develop programs that foster employee engagement and satisfaction. Regular surveys to gather feedback can help identify issues early. Recognition programs, team-building activities, and opportunities for career growth can boost morale and retention.

- ***Competitive Compensation:***

Ensure that compensation and benefits packages are competitive within the industry. Regularly reviewing and adjusting salaries, bonuses, and benefits can help retain talent.

- ***Career Development Opportunities:***

Offer clear career paths and professional development opportunities. Providing training, mentorship programs, and promoting from within can motivate employees to stay with the company.

- ***Work-Life Balance:***

Promote a healthy work-life balance by offering flexible working hours, remote work options, and ensuring reasonable workload expectations. This helps reduce burnout and increases job satisfaction.

- ***Improve Onboarding Processes:***

Enhance the onboarding process to ensure new hires are well-integrated and feel welcomed. A strong onboarding process helps new employees acclimate faster and more effectively.

- ***Monitor and Analyze Attrition Data:***

Continuously monitor attrition rates and analyze data to identify trends and underlying causes. This proactive approach can help address issues before they become significant problems.

By implementing these strategies, the company can reduce attrition, retain valuable talent, and create a more stable and productive workforce. This, in turn, will lead to improved operational efficiency, lower costs, and higher employee and customer satisfaction.


***EXPLANATION OF DASHBOARD TWO***

**Overview**

The dashboard provides an extensive analysis of employee demographics, attrition rates, job roles, education fields, job satisfaction levels, and marital status. It's designed to offer a comprehensive view of the workforce to support HR analytics and decision-making.

***Sections and Visualizations***

1. Count of Current Employees by Age Band and Gender
Type: Bar Chart

***Description:*** This chart displays the number of current employees categorized by age bands and gender. The age bands include Under 25, 25-34, 35-44, 45-54, and Over 55. Gender is represented by different colors (Female and Male).

***Key Insight:*** Helps identify the distribution of employees across different age groups and gender, highlighting potential diversity and age demographic trends within the workforce.

2. Job Roles
Type: Buttons/Filters

Description: This section contains buttons for different job roles, such as Healthcare Representative, Human Resources, Laboratory Technician, Manager, Manufacturing Director, Research Director, Research Scientist, Sales Executive, and Sales Representative.

Key Insight: Allows users to filter and view data specific to each job role, making it easier to analyze job-specific trends and metrics.

3. Education Field and Job Satisfaction and Attrition
Type: Table

***Description:*** This table shows the distribution of employees across different education fields (Human Resources, Life Sciences, Marketing, Medical, Other, Technical Degree) and their job satisfaction levels (Dissatisfied, Satisfied, Unsatisfied, Very Satisfied).

***Key Insight:*** Provides a detailed view of the educational background of employees and their job satisfaction, which can be used to identify any correlations between education, job satisfaction, and attrition.

***4. Sum of Attrition Count by Age Band***

- ***Type:*** Bar Chart

***Description:*** This chart displays the total count of employee attrition categorized by age bands (Under 25, 25-34, 35-44, 45-54, Over 55).

***Key Insight:*** Helps to understand which age groups are experiencing the highest rates of attrition, indicating potential issues or areas for improvement in employee retention strategies for specific age demographics.

***5. Sum of Employee Count by Marital Status and Gender***

- ***Type:*** Table

***Description:*** This table shows the sum of employee counts categorized by marital status (Divorced, Married, Single) and gender (Female, Male).

***Key Insight:*** Highlights the marital status distribution of employees, providing additional demographic insights that could be relevant for employee engagement and retention strategies.

***6. Total Employee Count***

Description: Displays the total number of employees in the organization, which is 1,470.

Key Insight: Provides a quick snapshot of the overall size of the workforce.

Slicer
Location: Right-hand side of the dashboard.

Functionality: The slicer allows users to dynamically filter the data displayed on the dashboard based on selected criteria, such as job roles, education fields, or specific demographics.

Impact: Enhances interactivity by enabling users to view specific subsets of data, thus providing more focused insights and personalized analysis.

***Conclusion***

This dashboard offers a detailed and interactive analysis of various HR metrics. 
 ***Key insights include:***

- Operational Disruption: High attrition in key departments like Sales and R&D can impact operations.

- Increased Costs: Recruiting and training replacements are costly.

- Loss of Expertise: Experienced employees leaving affect quality and innovation.

- Employee Morale: High attrition can lower morale and productivity.

- Customer Satisfaction: Inconsistent staffing affects service quality.

***Recommended Actions:***

- Improve Employee Engagement: Implement programs to boost satisfaction and recognition.

- Competitive Compensation: Regularly review and adjust salaries and benefits.

- Career Development: Provide clear career paths and training opportunities.

- Work-Life Balance: Offer flexible working hours and manage workloads.

- Onboarding: Enhance onboarding to ensure new hires feel integrated.


***By implementing these strategies, the company can reduce attrition, retain talent, and create a stable, productive workforce, ultimately leading to improved operational efficiency and higher satisfaction among both employees and customers.***




#### VISUALIZATION

**DASHBOARD ONE**


![72c85b5f-52b1-4ac0-8563-1ee35eb33cd2](https://github.com/user-attachments/assets/7546b71d-1d53-497d-9e3d-5fd90cedec9b)


**DASHBOARD TWO**


![c08bb02e-719f-4d16-a089-0427651145a5](https://github.com/user-attachments/assets/a379a199-1781-4ab5-a6a0-4fce3df15472)


