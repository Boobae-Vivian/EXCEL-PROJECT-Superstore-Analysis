# SUPERSTORE-ANALYSIS

## INTRODUCTION

This project based on a dataset comprising 9994 rows and 21 columns of information, aims to provide a comprehensive  analysis of the U.S. Superstore Sales Data by answering key business questions and delving into various aspects such as total sales, profit by region, shipping modes, product quantity, customer profitability, and product discount, this dataset offers a holistic view of the Superstore's sales landscape. The insights obtained through thorough analysis and visualization will empower decision-makers to optimize strategies, enhance customer satisfaction, and boost overall business performance.

## PROBLEM STATEMENT

In the realm of U.S. Superstore Sales, a critical need arises to unravel the layers of data and derive meaningful insights. This project is tasked with a comprehensive analysis, aiming to address six pivotal business questions.
1. The total sales distribution by segment
2. Total profit across different regions
3. Number of sales across the top three shipping modes
4. Top three(3) products by total quantity
5. Top five(5) customers by total profit
6. Top three(3) products bearing the highest total discount.

The problem at hand is not just about understanding the data; it's about harnessing the power of insights to make informed and impactful business decisions in the competitive landscape of the U.S. Superstore Sales domain.

## SKILLS AND CONCEPT DEMOSTRATED

- Ensuring consistency in data types.
- Pivot table proficiency
- Grouping and aggregating data for meaningful insights.
- Calculating various metrics such as total sales, profit, and quantity.
- Creating effective visualizations to represent complex data.
- Using appropriate chart types for different insights.

## ANALYSIS, RESULTS AND DISCUSSIONS

### 1. The Total Sales Distribution by Segment

To determine the distribution of total sales by segment, begin by creating a pivot table with two pivot fields. Place the sales column in the values field for aggregation and the segment column in the row field for categorization. The resulting figures will emerge as follows:
- Consumer: $1,161,401
- Corporate: $706,146
- Home Office: $429,653

These numbers represent the total sales attributed to each segment. Specifically, the Consumer Segment constitutes 50% of the overall sales, contributing $1,161,401. The Corporate Segment represents 31% of total sales with a contribution of $706,146, while the Home Office Segment accounts for 19% of overall sales, contributing $429,653. This reveals that the Consumer segment has the highest distribution, while the Home Office segment has the lowest distribution.

Afterward, for visual representation, create a pie chart. Select any cell in the pivot table, go to the "PivotTable Analyze" tab, click on "PivotChart," and choose a suitable chart type. Confirm selection by clicking "OK," and the chosen chart will emerge, providing a graphical representation of the pivot table. It is advisable to follow design principles for effective data visualizations, such as simplifying visuals by eliminating unnecessary elements like gridlines and superfluous labels, ensuring clarity and focus in conveying the intended insights.

![](Project1.png)

### 2. Total Profit Across Different Regions

To ascertain the total profit across different regions, initiate the process by creating a pivot table with two pivot fields. Choose the profit column for the values field to aggregate and the regions column for the row fields to categorize. This will yield the following results:
- Central: $39,706
- East: $91,523
- South: $46,749
- West: $108,418

These figures depict the overall profits generated in each region. To visualize this data, a doughnut chart was employed by selecting any cell in the pivot table containing the calculation, going to the pivot table analyze bar, clicking on pivot chart, and choosing the doughnut chart. The West Region stands out with the highest profit, totaling $108,418, constituting 38% of the total profit. Following closely, the East Region contributed $91,523, representing 32% of the total profit. The South Region follows with $46,749, accounting for 16% of the total profit, and the Central Region contributed $39,706, making up 14% of the total profit. This breakdown sheds light on the profitability of each region, highlighting the West Region as the most profitable and the Central Region as the least profitable among the four.

![](Project2.png)

### 3. Number of Sales Across the Top Three Shipping Modes

To identify the sales count across the top three shipping modes, initiate the process by creating a pivot table with two pivot fields. Choose the sales column for the values field to aggregate, and the ship mode column for the row field to categorize. By default, the results will display as a sum. However, since our interest lies in the count of sales, we would modify the aggregation by selecting the sales header and opting to summarize values by count. This adjustment will reaggregate the data, providing the count of sales across the shipping modes.
To narrow our focus to the top three shipping modes, we would  select the region header, right-click, and choose to filter the top 3. This will yield the following results as:
- Standard Class: 5,968 
- Second Class: 1,945 
- First Class: 1,538 

These figures outline the distribution of sales transactions among different shipping modes. Visualizing this data with a pie chart, "Standard Class" leads with the highest number of sales at 5,968 transactions, constituting 63% of the total sales. Following this, "Second Class" accounts for 1,945 transactions, representing 21% of the total sales, while "First Class" contributes 1,538 transactions, representing 16% of the overall sales transactions.

![](Project3.png)

### 4. Top Three(3) Products by Total Quantity

To identify the top three products by total quantity, begin by creating a pivot table with two pivot fields, namely the value and row fields. Select the quantity column for the value field to aggregate, and the products column for the row field for categorization. However, to focus solely on the top three products, choose the product header, right-click, and opt to filter, narrowing down to the first three products with the highest total quantity sold. This process yields the following results:
- Easy-staple paper: 150 units
- Staple envelope: 170 units
- Staples: 215 units

These figures signify the top three products based on total quantity, revealing the number of units sold for each item. This information is visually represented using a clustered bar chart, where Easy-staple paper has 150 units, Staple envelope has 170 units, and Staples have 215 units. Such insights prove valuable for tasks like inventory management, sales tracking, and gauging the popularity of different products.

![](Project4.png)

### 5. Top Five(5) Customers by Total Profit














