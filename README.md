# cohort-analysis
I wanted to learn more about the field of behavioral analytics, which I believe to be an interesting and promising field at the intersection of behavioral science and data science. Cohort analysis seemed like a good place to start.

Cohort analysis is a subset of behavioral analytics that takes data from a given platform and breaks users into related groups for analysis. There groups, or cohorts, usually share similar characteristics within a given time frame.

Cohort analysis can be valuable because it separates growth and engagement metrics since growth can mask engagement problems. Lack of activity in older users can be masked by growth from new users.

## About the Data
I used the “Online Retail Data Set” from the UCI Machine Learning Repository. This is a data set containing all the transaction between 1/12/2010 and 9/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

The data has 8 columns:

1. InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
2. StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
3. Description: Product (item) name. Nominal.
4. Quantity: The quantities of each product (item) per transaction. Numeric.
5. InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
6. UnitPrice: Unit price. Numeric, Product price per unit in sterling.
7. CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
8. Country: Country name. Nominal, the name of the country where each customer resides.

## Steps Taken
1. Explore and clean dataset
2. Create 3 cohort groups and conduct a cohort analysis on each
3. Visualize the results using heatmaps
