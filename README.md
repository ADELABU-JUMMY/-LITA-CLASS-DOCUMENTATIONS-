# -LITA-CLASS-DOCUMENTATIONS-
FIRST PROJECT WITH INCUBATOR HUB


[PROJECT OVERVIEW](#project-overview)

 [DATA SOURCE](#data-source)
 
 [TOOLS USED](#tools-used)

 [DATA CLEANING AND PREPARATIONS](data-cleaning-and-preparations) 

---
### ***PROJECT OVERVIEW***

 ***This data analysis project aims to provide comprehensive insights into the process of cleaning, analyzing, and visualizing data using tools such as Excel, SQL and Power BI. By leveraging these platforms I gained hand-on experience in manipulating datasets, performing advanced queries and creating interactive  visualizations, The project enabled a deeper understanding of data analysis techniques and tools, equipping me with the skills neccessary to derive meaningful insights and make data-driven decisions***

### ***DATA SOURCE***

 ***The primary source of data used in this project is obtained from an open-source platform, The data is publicly available and can be freely downloaded from reputable online repositories such as Kaggle [Download Here](https://www.kaggle.com) or other trusted data repositories. These platforms offer diverse datasets that are widely used for research, analysis and educational purposes***.

---
### ***TOOLS USED***
- **Microsoft Excel*** [dowload Here](https://www.microsoft.com) 
1. ***For data cleaning***
2. ***For Analysis***
3. ***For data visualization***
- ***SQL-STRUCTURE QUERY LANGUAGE for Querying Data***

---
 ### ***Data Cleaning and Preparations***
  ***In the inital phase of the data cleaning and preparations we performed the following actions***
  
1. ***Data Loading and Inspection***
- ***Imported datasets and examined them for quality and structure***.

2. ***Handling missing variables***
- ***Identified and addressed mising values to maintain data integrity***

3. ***Data cleaning and formatting***
- ***Applied formatting rules and standardized data entries to ensure consistency***.    
    
---
  ### ***Exploratory Data Analysis***
  ***This phase involved exploring of the data to answer some specific questions, including***:
  - ## ***calculating SUM and AVERAGE Values, using functions such as***:
```
 =sum(A1:A35)
 =AVERAGE(A1:A35)
```
    
- ### ***Identifying Top Ten Highest and Lowest Sallers,using functions like***:
```
 =MAXIFS(range, criteria_range, criteria)
 =MINIFS(range, criteria_range, criteria)
```

 ---

***Exploring With Excel***

 #### Analyzing Sales Data In Excel:

- ***Region and Market:*** Understanding the geographical and market contexts can help identify high-performing areas and potential growth opportunities.

- ***Store and Trade Date:*** Pinpoints the exact location and timing of each transaction, which is crucial for analyzing sales patterns and trends over time.

- ***Fiscal Period:*** Helps align the sales data with financial reporting periods, aiding in accurate financial analysis.

- ***Model:*** Identifies the product involved, which is essential for product-specific performance reviews.

- ***Line of Business:*** Shows the type of business activity, helping categorize the transactions and understand the nature of sales.
Day Category: Differentiates between sales on workdays and public holidays, useful for analyzing the impact of holidays on sales.

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



  
 ### Data Analysis
 This section we included basic lines of code or queries or even some of the Database expressions[DAX] used during data analysis;
 
 ---SQL Example---
    
 ```
  SELECT * FROM TABLE
 WHERE CONDITION =TRUE
```
    

---

### Data Visualization With Excel

1. #### ***Here I used IFS Function to analyze the Business transaction category with the unit sold for all stores***.

![WhatsApp Image 2024-10-09 at 15 16 54_05f65358](https://github.com/user-attachments/assets/535a2512-beef-466b-8035-bfafa04dc01f)

2. #### ***Here the LOOKUP Function was used to get salary payment for all staff based on their Grade level using the simply salary structure***.

![WhatsApp Image 2024-10-09 at 15 16 55_e2ffe7f6](https://github.com/user-attachments/assets/195e7913-2548-4386-9fe2-3ea8e3962c3a)

#### THE USE OF PIVOT TABLE IN EXCEL TO ANALYZE DATA

3. #### ***Here I got the Top five(5) market based on Revenue and the Bottom five(5) stores based on the unit sold***.
  
![WhatsApp Image 2024-10-09 at 15 16 57_f222d3fd](https://github.com/user-attachments/assets/892ac921-8035-4346-b919-307a2eb5b5cb)

4. #### ***Here the total Revenue for each year was analyzed***

![WhatsApp Image 2024-10-09 at 15 16 56_8e6ea251](https://github.com/user-attachments/assets/f63b5d19-75cd-472c-8683-ec6ced5ec5fa)

#### Analyzing the business performance using Pivot chart
5. ### ***Performance for 2014***

![WhatsApp Image 2024-10-09 at 15 16 58_3fd8df32](https://github.com/user-attachments/assets/f7ff625d-7a8a-4fad-ae06-f1485f9ce789)

6. ### ***Performance for 2015***

![WhatsApp Image 2024-10-09 at 15 16 59_1d97a46a](https://github.com/user-attachments/assets/d8347235-9c7d-4c86-ad42-ad820be4732f)

### Data Visualization Using SQL(Structured Query Language)

7. #### ***created a table for employees in an organisation***.
  
![WhatsApp Image 2024-10-09 at 15 16 54_d308a6b2](https://github.com/user-attachments/assets/b7d53fa4-2d6e-476e-a60a-20c22ecfcefc)

 ### ***using SQL statement to manipulate my table***.
![WhatsApp Image 2024-10-09 at 15 16 54_2362eef3](https://github.com/user-attachments/assets/11036980-ebe6-4084-8c09-57310a70de43)

#### ***Using aggregate functions***.
  
![WhatsApp Image 2024-10-09 at 15 16 54_4e0902fd](https://github.com/user-attachments/assets/bda860d1-09b3-4f1e-acc9-a160357b2141)
