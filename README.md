# Excel-Challenge
Use conditional formatting to fill each cell with different color ("red" for failed, "green" for successful, and "yellow" for canceled)
Create new column named "percent funded", use the formula "=ROUND((E/D)*100,0)" to find percentage
Usde conditional formatting to format "percent funded" column according to a three-color scale with criterial start at "0" with a dark red, transition to green at "100" and blue at "200"
Create new column named "Average donation" and then using the formula "=ROUND(IF(AND(E2=0,H2=0),0,E2/H2),2)" to calculate average. Make sure that the value of column "H" can not equal to 0
Create Parent- and sub-category, then use formula "Data --> Text to Columns" to split category and sub-category into two new and separate columns. 
Create a new sheet with a pivot table (new sheet named "parent category" that analyzes our initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category
Create a pivot and plot a pivot chart of the sub-category
Follow the tutorial provided on BCS to convert Unix timestamps to a normal date. The command which I used is "=(((L2/60)/60)/24)+DATE(1970,1,1)"
Write a report in MS Word and answer the questions: 
o	Given the provided data, what are three conclusions that we can draw about crowdfunding campaigns?
o	What are some limitations of this dataset?
o	What are some other possible tables and/or graphs that we could create, and what additional value would they provide?
Create a new sheet with a pivot table that has a column of outcome, rows of Date Created Conversion, values based on the count of outcome, and filters based on parent category and Years
Creat a new sheet with 8 columns, then use COUNTIFS() to filter the number of successful, failed, and canceled campaigns
Add up each of the values in the Number Successful, Number Failed, and Number Canceled columns to populate the Total Projects column. 
Then, using a mathematical formula, find the percentage of projects that were successful, failed, or canceled per goal range.
PLot a pivot chart of outcomes based on goal, show the relationship between a goal amount and its chances of success, failure, or cancelation
Statistical Analysis: Mean, Median, Min, Max, Variance, Standard Deviation. And then write the statements to justify whether "mean" or "median" provide a more significant summarize of the data. 

