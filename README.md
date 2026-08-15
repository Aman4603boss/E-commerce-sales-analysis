# E-commerce-sales-analysis
## About the Project
 This is an E-Commerce Sales Analytics project created using **Power BI**.
 The main goal of this project is to analyze e-commerce data and understand sales, customers, products,sellers, payments,order and delivery performance.
### Tool Used
- Power BI
- Python
- Pandas
- Numpy
- Excel
- jupyter Notebook
### Dataset
The project uses the brazilian E-Commerce Public Dataset by olist.
The dataset contains information about:
- orders
- customers
- products
- sellers
- payments
- reviews
- product categories
- delivery
  
The final cleaned dataset is not included directly in this repository because of its large file size.
[Download the final cleaned dataset](https://drive.google.com/file/d/17oKJrtfg9SEkvqkaoIAhZodRjaLifzbp/view?usp=drive_link)
### Data Cleaning
The data was cleaned and combined using Python and Pandas
some of the main cleaning steps were:
- Handling missing values
- Checking duplicate records
- Correcting data types
- Creating delivery-related columns
- Creating delivery status
- Creating order month
- Combining different datasets
- Checking invalid sales values
  The final cleaned dataset contains:
  - 112650 rows
  - 34 columns
## Analysis Performed
   ### Sales Analysis
   - Total sales
   - Monthly Sales
   - Sales by Product category
   - top Products by sales
   - top sellers by sales
   - Average Sales by Product and seller
   ### Customer Analysis
   - Total Customer
   - One-time Customer
   - Repeat Customer
   - Customer Order Frequency
   - Customer Sales
   ### Product Analysis
   - Top Products by Orders
   - Top Products by sales
   - Average Sales per Product
   - Product Category Performance
   ### seller analysis
   - top seller by sales
   - top seller by orders
   - average sales per order
   - seller performance
   ### payment Analysis
   - payment type distribution
   - sales by Payment type
   - average payment value
   - payment installments
   ### Review Analysis
   - Review Score distribution
   - average review score
   - sales by review score
   - orders by review score
   - average sales by review score
### delivery analysis
- delivery status
- actual delivery days
- delay days
- early,on-time and delayed orders
- order status vs delivery status
## key project statisitics
- Total Orders:98666
- total sellers:3095
- total products:32951
- anverage review score:4.09
- one-time customers:96.9%
- repeat customers:3.05%
## Power BI Dashboard
 An interactive Power BI dashboard was created to visualize the analysis.
 The dashboard includes:
 - sales KPIs
 - Monthly sales trends
 - Category analysis
 - Product analysis
 - Customer analysis
 - Seller analysis
 - Payment analysis
 - Review analysis
 - Delivery analysis
 - Interactive slicers and charts
The interactive Power BI dashboard was created using the cleaned e-commerce data.
[Download Power BI dashboard](https://drive.google.com/file/d/1dJoU5EXjNtsJrcPwdD0h3sKEF_VsumGx/view?usp=drive_link)
## Project Files
 - ecommercecleaning.ipynb -Python data cleaning and analysis
 - olist_products_dataset.csv -Product dataset
 - olist_sellers_dataset.csv -seller dataset
 - product_category_name_translation.csv -Product category translation
 - README.md -Project documentation
 - Dashboard screenshots
## Note
   The final cleaned dataset is not included in this repository because of its large file size.
## Conclusion
   This project helped analyze e-commerce sales, customers,products,sellers, payments,reviews and delivery performance using Python and Power BI
  
