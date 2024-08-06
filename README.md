# Olist Ecommerce Analytics

## Project Overview
This project involves analyzing Olist Ecommerce data to derive meaningful insights and create visualizations for better decision-making. The analysis focuses on various key performance indicators (KPIs) using Excel, MySQL, Tableau, and Power BI.

## Tools Used
- **Excel**: Used for initial data cleaning, merging datasets, and preliminary analysis.
- **MySQL**: Utilized for storing, querying, and analyzing data.
- **Power BI**: Employed for creating interactive and advanced visualizations.
- **Tableau**: Employed for creating interactive and advanced visualizations.

## Datasets
The project involves nine datasets:
- olist_customer_dataset
- olist_geolocation_dataset
- olist_order_items_dataset
- olist_order_payment_dataset
- olist_order_review_dataset
- olist_order_dataset
- olist_products_dataset
- olist_sellers_dataset
- product_category_name_translation

These datasets were merged and analyzed to derive insights.

### Dataset Columns

#### olist_customer_dataset
- customer_id: Unique identifier for each customer.
- customer_unique_id: Unique identifier for each customer, different from customer_id, possibly anonymized.
- customer_zip_code_prefix: Zip code prefix of the customer's address.
- customer_city: City of the customer's address.
- customer_state: State of the customer's address.

#### olist_geolocation_dataset
- geolocation_lat: Latitude of the customer's location.
- geolocation_lng: Longitude of the customer's location.
- geolocation_city: City according to geolocation data.
- geolocation_state: State according to geolocation data.

#### olist_order_dataset
- order_id: Unique identifier for each order.
- order_status: Current status of the order (e.g., delivered, shipped, canceled).
- order_purchase_timestamp: Timestamp when the order was made.
- order_purchase_timestamp_year: Year when the order was made.
- order_approved_at: Timestamp when the order was approved.
- order_delivered_carrier_date: Date when the order was delivered to the carrier.
- order_delivered_customer_date: Date when the order was delivered to the customer.
- order_estimated_delivery_date: Estimated delivery date for the order.

#### olist_order_items_dataset
- product_id: Unique identifier for each product.
- seller_id: Unique identifier for each seller.
- shipping_limit_date: Deadline for the seller to ship the order.
- price: Price of the product.
- freight_value: Shipping cost for the order.

#### olist_order_payment_dataset
- payment_type: Type of payment used (e.g., credit card, voucher).
- payment_value: Total value of the payment.

#### olist_order_review_dataset
- review_id: Unique identifier for each review.
- review_score: Score given in the review (typically 1 to 5).
- review_creation_date: Date when the review was created.
- review_answer_timestamp: Timestamp when the review was answered.

#### olist_products_dataset
- product_category_name: Category name of the product.
- product_weight_g: Weight of the product in grams.

#### olist_sellers_dataset
- seller_zip_code_prefix: Zip code prefix of the seller's address.
- seller_city: City of the seller's address.
- seller_state: State of the seller's address.

### Additional Columns
- Day of Week: Day of the week when the order was placed.
- Weekend_Weekday_Flag: Indicates if the order was placed on a weekend or a weekday.
- Delivery Duration (Days): Delivery duration in days, possibly specific to the pet shop category.
- Shipping Days/Order Fulfillment Time: Time taken to fulfill the order.
- Response Time: Time taken to respond to a review or query.
- Shipping_Days_Bin: Categorized shipping days into bins (e.g., 0-2 days, 3-5 days).

## Key Performance Indicators (KPIs)
1. Weekday Vs Weekend Payment Statistics
2. Review Score and Payment Type Orders
3. Average Pet Shop Delivery Days
4. Average Price & Payment Value for Sao Paulo Customers
5. Shipping Days & Review Scores Relationship
6. Top 10 Highest Selling Products
7. Top 10 Lowest Selling Products
8. Percentage of Orders with Payment Type
9. Top 10 Average Payment Value per Product Category
10. Cancellation Rate by Day of Week

## Visualizations
The data has been visualized using Power BI and Tableau to provide an interactive experience and gain insights into the various KPIs. The visualizations include bar charts, line charts, and maps to effectively communicate the findings.

## Conclusion
This project demonstrates the use of Excel for data cleaning, MySQL for data analysis, and Power BI and Tableau for visualization. The KPIs provide valuable insights into ecommerce performance, customer behavior, and other critical factors that can aid in decision-making processes.

## Additional Information
This project is particularly useful for people who want to add substantial projects to their portfolio. If you are facing any challenges in creating similar projects, you can refer to the files and code in this project for guidance.
