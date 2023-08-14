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
   - [January](https://github.com/sanjanand06/Electronic-Sales-Data/blob/main/Sales_January_2019.csv)
   - [February](https://github.com/sanjanand06/Electronic-Sales-Data/blob/main/Sales_February_2019.csv)
   - [March](https://github.com/sanjanand06/Electronic-Sales-Data/blob/main/Sales_March_2019.csv)
   - [April](https://github.com/sanjanand06/Electronic-Sales-Data/blob/main/Sales_April_2019.csv)
   - [May](https://github.com/sanjanand06/Electronic-Sales-Data/blob/main/Sales_May_2019.csv)
   - [June](https://github.com/sanjanand06/Electronic-Sales-Data/blob/main/Sales_June_2019.csv)
   - [July](https://github.com/sanjanand06/Electronic-Sales-Data/blob/main/Sales_July_2019.csv)
   - [August](https://github.com/sanjanand06/Electronic-Sales-Data/blob/main/Sales_August_2019.csv)
   - [September](https://github.com/sanjanand06/Electronic-Sales-Data/blob/main/Sales_September_2019.csv)
   - [October](https://github.com/sanjanand06/Electronic-Sales-Data/blob/main/Sales_October_2019.csv)
   - [November](https://github.com/sanjanand06/Electronic-Sales-Data/blob/main/Sales_November_2019.csv)
   - [December](https://raw.githubusercontent.com/sanjanand06/Electronic-Sales-Data/main/Sales_December_2019.csv)

- Merged dataset by using to_csv: View [Dataset](https://github.com/sanjanand06/Electronic-Sales-Data/blob/main/all_data.csv)

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
- Jupyter Notebook [Python script](https://github.com/sanjanand06/Electronic-Sales-Data/blob/main/Sales%20Analysis.ipynb)


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




