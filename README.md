# Business-Case-TARGET SQL
Scaler DSML: Business Case: TARGET - SQL
# TARGET - SQL
![image](https://github.com/user-attachments/assets/3e8aa802-65a3-4ef5-99be-0d170d08ec49)
Welcome to the Target Data EDA project! 🎉 In this repository, we delve into the world of Target to uncover valuable insights from their Brazil customers data. Whether you're a target analyst, this project has something for everyone.
## About TARGET 🛒
Target is a globally renowned brand and a prominent retailer in the United States. Target makes itself a preferred shopping destination by offering outstanding value, inspiration, innovation and an exceptional guest experience that no other retailer can deliver.
## Business Problem 📈
By analyzing this extensive dataset, it becomes possible to gain valuable insights into Target's operations in Brazil.
## Dataset 📋
The dataset offers a comprehensive view of various dimensions including the order status, price, payment and freight performance, customer location, product attributes, and customer reviews:
The column description for these csv files is given below.

##The customers.csv contain following features:
- **Features:** Description
- **customer_id:** ID of the consumer who made the purchase
- **customer_unique_id:** Unique ID of the consumer
- **customer_zip_code_prefix:** Zip Code of consumer’s location
- **customer_city:** Name of the City from where order is made
- **customer_state:** State Code from where order is made (Eg. são paulo - SP)
  
##The sellers.csv contains following features:
- **seller_id:** Unique ID of the seller registered
- **seller_zip_code_prefix:** Zip Code of the seller’s location
- **seller_city:** Name of the City of the seller
- **seller_state:** State Code (Eg. são paulo - SP)
  
##The order_items.csv contain following features:
- **order_id:** A Unique ID of order made by the consumers
- **order_item_id:** A Unique ID given to each item ordered in the order
- **product_id:** A Unique ID given to each product available on the site
- **seller_id:** Unique ID of the seller registered in Target
- **shipping_limit_date:** The date before which the ordered product must be shipped
- **price:** Actual price of the products ordered
- **freight_value:** Price rate at which a product is delivered from one point to another
  
##The geolocations.csv contain following features:
- **geolocation_zip_code_prefix:** First 5 digits of Zip Code
- **geolocation_lat:** Latitude
- **geolocation_lng:** Longitude
- **geolocation_city:** City
- **geolocation_state:** State
##The payments.csv contain following features:
- **order_id:** A Unique ID of order made by the consumers
- **payment_sequential:** Sequences of the payments made in case of EMI
- **payment_type:** Mode of payment used (Eg. Credit Card)
- **payment_installments:** Number of installments in case of EMI purchase
- **payment_value:** Total amount paid for the purchase order
  
##The orders.csv contain following features:
- **order_id:** A Unique ID of order made by the consumers
- **customer_id:** ID of the consumer who made the purchase
- **order_status:** Status of the order made i.e. delivered, shipped, etc.
- **order_purchase_timestamp:** Timestamp of the purchase
- **order_delivered_carrier_date:** Delivery date at which carrier made the delivery
- **order_delivered_customer_date:** Date at which customer got the product
- **order_estimated_delivery_date:** Estimated delivery date of the products

##The reviews.csv contain following features:
- **review_id:** ID of the review given on the product ordered by the order id
- **order_id:** A Unique ID of order made by the consumers
- **review_score:** Review score given by the customer for each order on a scale of 1-5
- **review_comment_title:** Title of the review
- **review_comment_message:** Review comments posted by the consumer for each order
- **review_creation_date:** Timestamp of the review when it is created
- **review_answer_timestamp:** Timestamp of the review answered
  
##The products.csv contain following features:
- **product_id:** A Unique identifier for the proposed project.
- **product_category_name:** Name of the product category
- **product_name_lenght:** Length of the string which specifies the name given to the products ordered
- **product_description_lenght:** Length of the description written for each product ordered on the site
- **product_photos_qty:** Number of photos of each product ordered available on the shopping portal
- **product_weight_g:** Weight of the products ordered in grams
- **product_length_cm:** Length of the products ordered in centimeters
- **product_height_cm:** Height of the products ordered in centimeters
- **product_width_cm:** Width of the product ordered in centimeters
## #Dataset schema#

<img width="503" alt="Screenshot 2024-11-19 115055" src="https://github.com/user-attachments/assets/c373f92e-1e5b-4cc9-8172-417c7b4ff394">

## 🚀 Mission 🚀
Task is to analyzing the given dataset to extract valuable insights and provide actionable recommendations
To get you started, here are some questions you might consider:

- Data type of all columns in the "customers" table.
- Get the time range between which the orders were placed.
- Count the Cities & States of customers who ordered during the given period.
- Is there a growing trend in the no. of orders placed over the past years?
- Can we see some kind of monthly seasonality in terms of the no. of orders being placed?
  During what time of the day, do the Brazilian customers mostly place their orders? (Dawn, Morning, Afternoon or Night)
- Get the month on month no. of orders placed in each state.
- How are the customers distributed across all the states?
- Get the % increase in the cost of orders from year 2017 to 2018 (include months between Jan to Aug only).
- You can use the "payment_value" column in the payments table to get the cost of orders.
- Calculate the Total & Average value of order price for each state.
- Calculate the Total & Average value of order freight for each state.
- Find the no. of days taken to deliver each order from the order’s purchase date as delivery time.
- Find out the top 5 states with the highest & lowest average freight value.
- Find out the top 5 states with the highest & lowest average delivery time.
- Find out the top 5 states where the order delivery is really fast as compared to the estimated date of delivery.
- Find the month on month no. of orders placed using different payment types.
- Find the no. of orders placed on the basis of the payment installments that have been paid.

## Conclusion📌

Now that you're armed with questions and a powerful dataset, it's time to embark on your Target data EDA journey. Feel free to fork this repository, clone it to your local machine, and start diving into the code and data.

Remember, the more we learn from this data, the better we can help Target continue to Deliver the  millions of orders around the world! 🏌️‍♀️🛒

Happy coding! 🚀👨‍💻🛒
