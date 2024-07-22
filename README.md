# Online-Sales-Analysis-Dashboard-Exercise

## Data Source: https://www.kaggle.com/datasets/shreyanshverma27/online-sales-dataset-popular-marketplace-data

## About the Dataset
This dataset provides a comprehensive overview of online sales transactions across different product categories. Each row represents a single transaction with detailed information such as the order ID, date, category, product name, quantity sold, unit price, total price, region, and payment method.

## Columns:

##### Order ID: Unique identifier for each sales order.

##### Date: Date of the sales transaction.

##### Category: Broad category of the product sold (e.g., Electronics, Home Appliances, Clothing, Books, Beauty Products, Sports).

##### Product Name: Specific name or model of the product sold.

##### Quantity: Number of units of the product sold in the transaction.

##### Unit Price: Price of one unit of the product.

##### Total Price: Total revenue generated from the sales transaction (Quantity * Unit Price).

##### Region: Geographic region where the transaction occurred (e.g., North America, Europe, Asia).

##### Payment Method: Method used for payment (e.g., Credit Card, PayPal, Debit Card).

## Objective
In this exercise, we aim to:

Analyze sales trends over time to identify seasonal patterns or growth opportunities.

Explore the popularity of different product categories across regions.

Investigate the impact of payment methods on sales volume or revenue.

Identify top-selling products within each category to optimize inventory and marketing strategies.

Evaluate the performance of specific products or categories in different regions to tailor marketing campaigns accordingly.


## Overview
It can be observed that the total revenue exhibits an overall decline from Jan to Aug. 

The total sales volume experienced fluctuations throughout this period, exhibiting a steep drop in sales volume from Jul to Aug. 

<img width="479" alt="image" src="https://github.com/user-attachments/assets/bc4ce7f8-dddb-4822-b809-89f37c845299">

<img width="479" alt="image" src="https://github.com/user-attachments/assets/f0dfa6b1-52ae-46e8-893c-576c59a2b5af">




The treemap chart illustrates the top 10% products sold, where a larger segment represents a larger quantity of that particular product being sold.

<img width="394" alt="image" src="https://github.com/user-attachments/assets/b43cffc2-5a02-4079-be34-082c01c5ecc7">


Three doughnut charts help us visualize the percentage of sales volume classified by region and product category, and the percentage of transactions classified by payment method.

<img width="190" alt="image" src="https://github.com/user-attachments/assets/eb2df00c-5d6b-4136-be27-cc10c3a568d5">

<img width="190" alt="image" src="https://github.com/user-attachments/assets/bf29dc3d-3ce7-4003-82df-f8b1c1a8cd03">

<img width="190" alt="image" src="https://github.com/user-attachments/assets/7a767420-649e-45c6-990a-fa114e42aff1">


The sunburst chart illustrates the popularity of a certain product category among different regions, and it can be observed that:

Only clothing and sports related products are sold in Asia

Only beauty and home appliance related products are sold in Europe

Only books and electronics are sold in North America

The percentages of each product category sold, relative to their region, are shown as well.

<img width="439" alt="image" src="https://github.com/user-attachments/assets/4c275509-233d-4e1d-a136-131ecbaf822f">

## Insights

### Asia

<img width="479" alt="image" src="https://github.com/user-attachments/assets/d7b800b8-05d3-4f32-aefd-18c98cf40123">

<img width="479" alt="image" src="https://github.com/user-attachments/assets/7f4c6f7d-bcad-4352-892e-2d85d17e3a69">

#### Observations

100% of clothing products were paid with a debit card, and 100% of sports products were paid with a credit card.

'Nike Air Force 1', 'Hanes Comfort Soft T-shirt', 'Gap Essential Crewneck T-Shirt' and 'Spalding NBA Street Basketball' were the top selling products.

Although the sales volume was mostly consistent, the total sales revenue in Asia experienced an overall decline from Jan to Aug.

Clothing products sold in January exhibited the largest monthly revenue, while sports products sold in February exhibited the largest monthly revenue.

A spike in sales volume and sales revenue can be observed for clothing products sold in July.

Sports products exhibited a fluctuating sales revenue throughout Jan - Aug, but a constant sales volume throughout.


### Europe

<img width="475" alt="image" src="https://github.com/user-attachments/assets/05527635-f28b-4ca0-abf8-7f8c9b84d22b">

<img width="475" alt="image" src="https://github.com/user-attachments/assets/c35ce373-e29e-4631-b75f-fb07bba3d9b3">

#### Observations

All transactions in Europe were through PayPal.

March saw the highest sales revenue for all products sold in Europe, while May saw the highest sales volume.

Beauty products sold in Europe exhibited a highest monthly revenue in January, with an overall decrease from Jan - Aug. A spike in revenue can be observed in July.
Sales volume for beauty products remained constant throughout.

Home appliances sold in Europe exhibited a highest monthly revenue in March, followed by a steep decline the following month. The monthly revenue remained relatviely constant thereafter.

The majority (approximately 75%) of the top products sold in Europe belong to home appliances.

### North America

<img width="475" alt="image" src="https://github.com/user-attachments/assets/7ed7b7d0-e7b4-4643-af51-5db3b58eb8d4">

<img width="475" alt="image" src="https://github.com/user-attachments/assets/7460fef8-a92d-4c72-9f21-cda4635d79f1">

#### Observations

All transactions in North America were through credit cards.

January and April saw the two largest monthly sales revenue for all products sold in North America.

February saw the largest monthly sales revenue for books sold in North America.

January and April saw the two largest monthly sales revenue for electronic products sold in North America.

100% of the top 10% products sold in North America were books, and an average of 10 books were sold each month.

An average of 5 electronic products were sold each month.











