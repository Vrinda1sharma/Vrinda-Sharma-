Sales Data Exploration-
Introduction
Sales analysis over a PostgreSQL database, aiming to discover diverse insights. Identify best seller products, biggest customers, and sales growth rate.

In this database, we have records of orders for different types of paper placed by companies such as Walmart, Microsoft, among others. We can see how much of each type of paper was ordered, how much was spent, who was responsible for the order, in which region the company is located, and the dates of the different web events each company has conducted

A SQL analysis of sales on differents types of paper.

Sales Analysis
Datasets used
accounts: This table contains all the different companies, their id (account_id), website, contact of point and the sale representative id
orders: Timestamp of every order, the quantity ordered of every type of paper (standard_qty, gloss_qty, poster_qty), the total, how much money was spend in each type of paper (standard_amt_usd, gloss_amt_usd, poster_amt_usd) and the total in dollars.
region: Four regions: Northeast, Midwest, Southeast, West
sales_reps: This table shows all the sales representative names with their corresponding id and region_id.
web_events: All the web events conducted by each company, the account_id, the date each web event was conducted and the channel (facebook, twitter, etc)
