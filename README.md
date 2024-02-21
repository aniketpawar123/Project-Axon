
# Axon



### Problem Statement

Axon Company, a distinguished retailer specializing in classic cars, trains, ships, motorcycles, planes, vintage cars, 
trucks, and buses, has established a formidable global presence with headquarters strategically located in the 
USA, France, UK, Japan, and Australia. Under the astute leadership of President Murphy Diane, Vice President 
Patterson Mary, and VP of Marketing Firrelli Jeff, the company has navigated diverse markets. However, the sales 
team faces a significant challenge, grappling with disparate data and lacking a centralized system for 
management and analysis. This has led to a dearth of accurate, real-time sales reports, adversely impacting the 
decision-making process.

In a proactive move to address this challenge, Axon Company has embarked on a transformative initiative by 
opting to implement a Business Intelligence (BI) tool. Recognizing the critical need for effective sales data 
management and analysis, the company has meticulously shortlisted Microsoft PowerBI and SQL as the primary 
contenders for this project. This strategic decision reflects Axon's commitment to enhancing operational 
efficiency, facilitating informed decision-making, and maintaining its position as an industry leader in the realm 
of classic vehicles and transportation.



### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is in Mysql server.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : Errors and empty values were seen in the columns, which will be eliminated.
- Step 5 : In the report view, under the view tab, theme was selected.
- Step 6 : Since data is about sales then card visual is chosen to show kpi. 
- Step 7 : Visual filters (Slicers) were added for date.
- Step 8 : Eight card visuals were added to the canvas, they are Total sales and six commodities sales perecntage.
- Step 9 : Line and stacked column chart is added to show total sale of each commodity and their respective profit margin.

![bar chart](https://github.com/aniketpawar123/Project-Axon/assets/123149177/4de51011-ded4-4d6d-83ef-0d60e60af8c2) 

- Step 10 : Top five countries sales is shown by pie chart.
- Step 11 : Profit by month is shown using line chart, it show all year profit comparision.
- Step 12 : In the report view, under the insert tab, using shapes option from elements group a rectangle was inserted & similarly using image option company's logo was added to the report design area. 
- Step 14 : Top five customer and vendore are show using table.
### Following is the image of sales report:-

![sales report](https://github.com/aniketpawar123/Project-Axon/assets/123149177/e25a9c36-c521-4d9a-9ef0-730c3f98e3f0)
        
- Step 15 : Second page of employee report. Employees' overall sales performance is measured using the company's regional office.

### Following is the image employee report:-

![employee](https://github.com/aniketpawar123/Project-Axon/assets/123149177/92a4fbd7-5311-4b62-b012-d9ee8be8309a)

### Sales Report summary

1. Overall Sales Overview:

    • The company has achieved a commendable total sales figure of $9.06 million.
• Classic cars dominate the sales landscape, constituting the highest percentage at 40.82%, while trains exhibit the lowest sales 
percentage at 1.99%.

2. Top Performing Countries:

• The top five countries contributing significantly to sales are the USA, Spain, 
 France, Australia, and the UK.
• Ireland, on the other hand, registers the lowest sales among all countries.

3. Profit Margin Analysis:

• Motorcycles emerge as the most lucrative category with a high profit margin of 42.08%, contributing to a total sale of $120k.
• Despite classic cars leading in sales, their profit margin is comparatively lower than motorcycles.

4. Performance of Trains and Ships:

• Trains and ships exhibit modest total sales figures of $20k and $70k, respectively.
• However, their profit margins stand out at 34.73% and 39.33%, demonstrating solid profitability.

5. Top Customers and Vendors:

• Euro Shopping Channel emerges as the top customer, contributing significantly with a total sales figure of $821k.
• Classic Metal Creations leads as the top vendor, boasting a substantial total sales figure of $883k.

6. Monthly Performance:

• November consistently stands out with the highest total sales and the highest profit across all years

### Employee report summary:

1. Top Sales Performer:

• Hernandez Gerard, based in the France office, emerges as the top-performing sales employee.
• Gerard has achieved an impressive total sales figure of $1.26 million, showcasing exceptional sales 
prowess.

2. Lowest Sales Achievement:

• Marsh Peter, representing the Sydney office in Australia,
 has the lowest sales among the team.
• Peter has contributed sales amounting to $110k.

3. Office Performance Rankings:

• Paris office takes the lead in performance, achieving the highest total sales of $3.1 million.
• Following closely are London, San Francisco, and NYC, with robust sales figures.
• Boston, Sydney, and Tokyo exhibit commendable efforts, with Tokyo securing the lowest position, 
achieving total sales of $400k.
