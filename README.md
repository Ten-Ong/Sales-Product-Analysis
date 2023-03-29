## Sales-Product-Analysis
For this analysis, I will be using python for data cleaning process and Power BI for Visualization.

### About The Dataset
  - Data was downloaded Kaggle [here](https://www.kaggle.com/datasets/knightbearr/sales-product-data).
  - This 2019 sales product dataset contains 12 files of sales data records, each file representing each month of the year.

### Data Cleaning
  - I am using Python to import, combine and cleaning data, which included in this folder or click [here](https://github.com/Ten-Ong/Sales-Product-Analysis/blob/main/Sales_data_cleanning.ipynb) to view.

----- 
### Data Visualization
Before creating charts, there are a few steps needed to process 
- The 'Purchase Address' column need to break down to Address, City, States and Zipcode.
- Create Date table based on 'Order Date' column. 

Below is the screenshot of the overall analysis

![ Overall](https://github.com/Ten-Ong/Sales-Product-Analysis/blob/main/Overall.JPG)



- There are 8 States and 19 products with a total of $34.48 million in revenue. 
- CA was the highest state in revenue with $13.71m (39.76%). 
- Macbook Pro Laptop was the product that yielded the most revenue $8.035m,(23.3% of all revenue), also it was the most expensive item in this dataset.
- AAA Batteries(4-pack) was the most sold product with 31,012 quantity ordered (14.84% in all quantity order), also it was the least expensive item in this dataset.

--------


![ monthly sales](https://github.com/Ten-Ong/Sales-Product-Analysis/blob/main/monthly_sales.JPG)

- As expected, most electronic product will have its biggest sales toward the end of the year. December was the highest sales month with $4.6m ( 13.38%) followed by October with $3.7m.
- Revenue and quantity sold were not correlated because the price of the products.


