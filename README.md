# ML--Customer-Segmentation

## Objective : To increase marketing efficiency by exploring the Retail Store Data and coming up with insights to build a data driven business strategies
## Project Summary
### 1 - Data Exploration
### 2 - Data Analysis
### 3 - Building Features 
### 4 - Visualizing the data
### 5 - Building the RFM Metrics to visualize to categorise the customer
### 6 - Preprocessing the Data for Machine Learning
### 7 - Building the Machine Learning Model to obtain the clusters
### 8 - Profiling the clusters

## Business Impact 

### 1. Helping Business Development Team to create product differentiation based on the characteristic for each customer.
### 2. Know how to treat customer with specific criteria.
### 3. Recommendation based on customer segmentation.

## Data Exploration

#### 25% of the rows do not have Customer ID
#### 90% of the data is from United Kingdom
#### We have total around 1 years of data


## Data Analysis

#### Total return orders = 5172
#### Total return orders where CustomerID is null= 1518

![Month on Month Orders](https://github.com/Sreemanto/ML---Customer-Segmentation/blob/main/Monthwise%20Order%20Summary.png)

#### Highest number of orders are placed in November and th lowest being December (Maybe business was not expecting such a drastic sales and ran out of stock the following month)

![Month on Month Orders](https://github.com/Sreemanto/ML---Customer-Segmentation/blob/main/Monthwise%20Order%20Summary.png)

#### Sales in the 1st half of the year was not so great



Do a value counts on country you will see that 90% data is from UK

1. Restrict the data where country = United Kingdom.
2. Restrict the data further where Quantity > 0
3. Convert the date into DateTime object. Print the max and min date.
4. Drop record where CustomerID is null
5. Drop record where Unitprice is less than 0
6. Create a revenue field (Revenue = Quantity * Unit Price)
7. Aggregating the Orders by Month
8. Create Month wise Quatity plot (line plot)
9. Create Month wise Revenue plot (line plot)

Study about RFM Metric(Recency Frequent, Monetary) used in Businesses
