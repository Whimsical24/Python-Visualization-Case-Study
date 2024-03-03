# Python-Visualization-Case-Study

Here, we present a collection of real-world case studies showcasing the power and versatility of data visualization techniques using Python. From exploratory data analysis to interactive dashboards, these case studies demonstrate how Python libraries such as Matplotlib, Seaborn, Plotly, and Bokeh can be leveraged to derive insights, communicate findings, and drive decision-making across various domains and industries.

ABOUT DATA:
The data attached is a two-year sales data of a pharma company which talks about 
sales in 2015 and 2016 across various regions and time frames.
Account Id : Customer ID
Account Name : Customer Name
Tier : Customer Segment
Sales 2015 : Sales for the year 2015
Sales 2016 : Sales for the year 2015
Units 2015 : No of Units sold for 2015
Units 2016 : No of Units sold for 2016

Here we have to reshape the data i.e., convert from wide to long and long to wide (with stack(), unstack() and pivot()) 
after aggregating it by using groupby(). Please refer to the material at Pandas – Data 
Understanding.ipynb for details.
1. Compare Sales by region for 2016 with 2015 using bar chart
2. What are the contributing factors to the sales for each region in 2016. Visualize it using a 
Pie Chart.
3. Compare the total sales of 2015 and 2016 with respect to Region and Tiers
4. In East region, which state registered a decline in 2016 as compared to 2015?
5. In all the High tier, which Division saw a decline in number of units sold in 2016 compared 
to 2015?
6. Create a new column Qtr using numpy.where() or any suitable utility in the imported 
dataset. The Quarters are based on months and defined as -
• Jan - Mar : Q1
• Apr - Jun : Q2
• Jul - Sep : Q3
• Oct - Dec : Q4 
7. Compare Qtr wise sales in 2015 and 2016 in a bar plot
8. Determine the composition of Qtr wise sales in and 2016 with regards to all the Tiers in a 
pie chart.

