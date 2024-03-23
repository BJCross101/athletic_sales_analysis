
# Introduction
This repository contains Python scripts for analyzing sales data from the athletic retail industry. The scripts utilize the Pandas library for data manipulation and analysis.

1. Combine and Clean the Data
This section focuses on importing, combining, and cleaning the sales data from two CSV files representing sales data from 2020 and 2021.

2. Determine which Region Sold the Most Products
Here, we determine the regions that sold the most products by aggregating the sales data based on region, state, and city. Both groupby and pivot_table methods are used for this analysis.

3. Determine which Region had the Most Sales
Similar to the previous section, this part focuses on determining the regions with the highest sales. We aggregate the sales data by region, state, and city using both groupby and pivot_table methods.

4. Determine which Retailer had the Most Sales
In this section, we identify the retailers with the highest sales by aggregating the data based on retailer, region, state, and city. Both groupby and pivot_table methods are used for this analysis.

5. Determine which Retailer Sold the Most Women's Athletic Footwear
Here, we filter the sales data to extract information specifically about women's athletic footwear. We then determine which retailers sold the most women's athletic footwear, using both groupby and pivot_table methods.

6. Determine the Day with the Most Women's Athletic Footwear Sales
Lastly, we focus on determining the day with the highest sales of women's athletic footwear. We create a pivot table with invoice dates as the index and total sales as the values. Then, we resample the data into daily bins and identify the day with the highest sales.

This README provides an overview of the analysis conducted on the sales data, showcasing different methods used to derive insights from the dataset.