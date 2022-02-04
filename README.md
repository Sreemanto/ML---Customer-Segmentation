# ML--Customer-Segmentation

## Objective : To increase marketing efficiency by directing effort specifically toward the designated segment.

## Approach
### 1 - Data Exploration
### 2 - Data Analysis
### 3 - Building Features 
### 4 - Visualizing the data
### 5 - Building the RFM Metrics to visualize to categorise the customer
### 6 - Preprocessing the Data for Machine Learning
### 7 - Building the Machine Learning Model to obtain the clusters
### 8 - Profiling the clusters




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
