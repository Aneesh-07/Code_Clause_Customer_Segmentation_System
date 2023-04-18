# Customer Segmentation System

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)<br>

## What It Does: 
Customer Segmentation System is a detailed analysis of a company’s ideal customers. It helps a business to better understand its customers and makes it easier for them to modify products according to the specific needs, behaviors and concerns of different types of customers.

Customer Segmentation System helps a business to modify its product based on its target customers from different types of customer segments. For example, instead of spending money to market a new product to every customer in the company’s database, a company can analyze which customer segment is most likely to buy the product and then market the product only on that particular segment.


 It performs clustering to summarize customer segments.

1️⃣ Data Collection <br>
2️⃣ Data Preprocessing <br>
3️⃣ Exploratory Data Analysis <br>
4️⃣ Dataset Balancing & Scaling <br>
5️⃣ Clustering and Analysis of Clustered Data

## Prerequisites:
I would highly recommend that before the hack night you have some kind of toolchain and development environment already installed and ready. If you have no idea where to start with this, try a combination like: <br>


1️⃣ `Python`<br>
2️⃣ `scikit-learn` / `sklearn`<br>
3️⃣ `Pandas`<br>
4️⃣ `NumPy`<br>
5️⃣ `Swaborn`<br>
6️⃣ `Yellowbrick`<br>

An environment to work in - something like `Jupyter` or `colab`<br>
For Linux people, your package manager should be able to handle all of this. If it somehow can't, see if you can at least install Python and pip and then use pip to install the above packages.

## Dataset:

> You can collect raw dataset from [here](marketing_campaign.csv).

## Attribute Information:<br>
**Attributes**<br>
<br>
**People**<br><br>

- ID: Customer's unique identifier<br>
- Year_Birth: Customer's birth year<br>
- Education: Customer's education level<br>
- Marital_Status: Customer's marital status<br>
- Income: Customer's yearly household income<br>
- Kidhome: Number of children in customer's household<br>
- Teenhome: Number of teenagers in customer's household<br>
- Dt_Customer: Date of customer's enrollment with the company<br>
- Recency: Number of days since customer's last purchase<br>
- Complain: 1 if the customer complained in the last 2 years, 0 otherwise<br><br>
**Products**<br><br>

- MntWines: Amount spent on wine in last 2 years<br>
- MntFruits: Amount spent on fruits in last 2 years<br>
- MntMeatProducts: Amount spent on meat in last 2 years<br>
- MntFishProducts: Amount spent on fish in last 2 years<br>
- MntSweetProducts: Amount spent on sweets in last 2 years<br>
- MntGoldProds: Amount spent on gold in last 2 years<br><br>
**Promotion**<br><br>

- NumDealsPurchases: Number of purchases made with a discount<br>
- AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise<br>
- AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise<br>
- AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise<br>
- AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise<br>
- AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise<br>
- Response: 1 if customer accepted the offer in the last campaign, 0 otherwise<br><br>
**Place**<br><br>

- NumWebPurchases: Number of purchases made through the company’s website<br>
- NumCatalogPurchases: Number of purchases made using a catalogue<br>
- NumStorePurchases: Number of purchases made directly in stores<br>
- NumWebVisitsMonth: Number of visits to company’s website in the last month
<br>
