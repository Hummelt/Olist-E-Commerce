# How to dive into the field of Data - Story of a rookie.
### Analysing of the E-Commerce company Olist dataset
![Python](https://files.realpython.com/media/wxPython-GUI-Tutorial_Watermarked.917be5fbbf2c.jpg)

## Business Understanding of Olist E-Commerce
This dataset was generously provided by Olist, the largest department store in Brazilian marketplaces. Olist connects small businesses from all over Brazil to channels without hassle and with a single contract. Those merchants are able to sell their products through the Olist Store and ship them directly to the customers using Olist logistics partners. See more on Olist's website: www.olist.com

After a customer purchases the product from Olist Store a seller gets notified to fulfill that order. Once the customer receives the product, or the estimated delivery date is due, the customer gets a satisfaction survey by email where he can give a note for the purchase experience and write down some comments.

### Questions of the Analysis
With the Analysis of this dataset we want to answer the following 3 questions:
1) What does the order profile of olist look like?
2) Does Olist deliver on time (or even earlier than the expected delivery date)?
3) What correlations can we find between item price and payment method?

Further this analysis should be an example on how to analyze (multiple datasets) on the one hand and on the other hand explain every step to everybody out there who is just starting to become a Parselmouth.

## Data Understanding 
The data is divided in multiple datasets for better understanding and organization:

![Dataset](https://i.imgur.com/HRhd2Y0.png)

Used .csv sets in this analysis:
- olist_orders_dataset.csv: table of orders
- olist_order_payments_dataset.csv: table of payments
- olist_products_dataset.csv: table of products
- olist_order_items_dataset.csv: table of order items
For more details check the Notebook.

The data set is provided by [kaggle.](https://www.kaggle.com/olistbr/brazilian-ecommerce)

## Prepare Data

Analysis software and libraries:

- Python
- NumPy
- Pandas
- Matplotlib
- Plotly
- Seaborn
- scikit-learn
- datetime

The following steps have been processed in this analysis:

- Understanding the dataset
- Checking for missing values 
- Checking for duplicates
- Checking data formats


## Data Moddeling

- Combining data sets
- Analyzing the data
- Checking for correlations
- Logistical Regression
- Checking the R2squared

## Evaluate the Results

Conclusion:
1) Olist has a typical order profile for an e-com business with >90% SIOs.
2) The mean delivery time is 12,49  days after the purchase.
3) We can see some correlations which are quite intuitive to understand and others less. The payment via credit card makes >73% of the orders and >50% of the orders are payed at once, without any payment installments.


See Medium Blogpost for this analysis [here.](https://mjhummelt.medium.com/diving-into-the-e-com-business-through-data-b8b579054b34)
