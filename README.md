# Electronic Sales Data
Analysis of  a dataset containing details about sales of electronic components using Python and deriving important insights.

# Business Task
1.  What is the best month for sales? How much was the revenue for that month?
2.  Which city sold the most product?
3.  What time should we display advertisements to maximize the likelihood of customers buying products?
4.  What products are most often sold together?
5.  What products sold the most? Why do you think it sold the most?

# Dataset
- Sales data for all the months of the year 2019.
   - [January]
   - [February]
   - [March]
   - [April]
   - [May]
   - [June]
   - [July]
   - [August]
   - [September]
   - [October]
   - [November]
   - [December]

- Merged dataset by using to_csv: View [Dataset]

# Methods

- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime, astype)
- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns for answering business questions
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling our graphs


# Tools

- Python
- Pandas
- Matplotlib
- Jupyter Notebook [Python script]


# Outcome

1. There is rise in sales till April
- There is a continuous drop till October.
- December month has the best sales with revenue more than 4 million.

2. San Francisco has the highest sales, followed by Los Angeles and New York City.
- Based on the above results, cities which are at the coast have higher revenue and cities which have major tech advancements which need electronics components have higher sales.

3. It is recommended to advertise around 11am or around 7pm.

4. 'i-phone' and 'Lighting Charging Cable' were the top most products sold together.
- 'Google Phone', 'USB-C Charging Cable' and 'iPhone', 'Wired Headphones' were among the top most products sold together.

5. AA Batteries (4-pack) is the most sold product.
- By correlating products' quantity with price of the quantity, if the product is costlier, then the quantity ordered is less.
- If the product is cheaper, then the quantity ordered is more.




