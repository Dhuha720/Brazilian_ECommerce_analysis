# Brazilian_ECommerce_analysis

WE made some analyzing on Brazilian ecommerce public dataset of orders made at Olist Store. The dataset has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. Its features allows viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers. We also released a geolocation dataset that relates Brazilian zip codes to lat/lng coordinates. 

## This project originates to find:
* Finding the number of orders for each state.
* Comparing the number of orders between weekdays and weekends.
* Finding the number of orders by date.
* Comparing the number of orders between 2017 and 2018 based on quarters.
* Finding rush hour for orders.
* Defining the most used payment method.
* What is the status of the order's delivery (on time, Early, late)?
* The 20 most categories based on orders.

### We use only 6 of 9 datasets:

* olist_customers_dataset
* olist_orders_dataset
* olist_order_items_dataset
* olist_order_payments_dataset
* olist_products_dataset
* product_category_name_translation

### Data:
The datasets come from Kaggle " [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data) 

### Tools:
* Pandas
* Matplotlib
* Seaborn
* Plotly
