TRANSACTIONS ANALYSIS

Stack: python (pandas)

Tasks:
1. Whether there are duplicate observations in the data? What is their number? Delete them

2. If the user canceled the order, the transaction number (InvoiceNo) is preceded by C (canceled)
How many transactions were canceled by users in total?

3. Аilter the data and leave in retail only those orders where Quantity > 0
Indicate the number of remaining rows

4. Count the number of orders for each user (CustomerID) from Germany
Leave only those who made more than N transactions (InvoiceNo), where N is the 80% percentile
Write the resulting user id to germany_top (not the whole dataframe, just the id)

5. Leave data only for top German users

6. Group top_retail_germany by StockCode
Which of the products was added to the cart most often, except for POST?

7. Create a Revenue column with the purchase amount using the Quantity and UnitPrice columns

8. For each transaction (InvoiceNo), calculate the final amount of the order
Indicate the top 5 (InvoiceNo) by order amount (comma-separated with a space and in descending order of TotalRevenue)