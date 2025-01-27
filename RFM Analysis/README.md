<h1>Project Background</h1>

This project analyzes the sales data of an online retail store.
The aim of the project is to perform RFM analysis and identify customers in different segments.

Insights and Recommendations are provided based on the following key metrics:
- Recency: Number of days since the customer last ordered.
- Frequency: Number of times the customer has made purchase on the store.  
- Value: Total amount the customer has spent on the store.  

The Jupyter Notebook containing the analysis and visualizations can be found <a href="https://nbviewer.org/github/mzsprojects/DataAnalyticsProjects/blob/main/RFM%20Analysis/RFM%20Analysis.ipynb">here</a>.

<h1>Data Structure & Initial Checks</h1>

The raw data is stored in csv file which contains 8 columns: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country. <br>
The total amount for each sale is calculated using Quantity and UnitPrice. This value is stored in the TotalAmount column.

![image](https://github.com/user-attachments/assets/52728575-01ed-4644-a37b-c61b6de2a7ae)

<br>
Before performing the analysis, the dataset was checked for the integrity and NULL values.

The CustomerID column contained 1,35,080 NULL values. Since there was no data available to identify these values, these records were dropped.

The data is spread from December 2010 to December 2011.
Since it is very old, the date after the last order is considered as reference.

<h1>Observations</h1>

The majority of the store’s customer base consists of mid-value customers, with high-value customers following closely behind, differing by only 200 customers. 
<br> <br>
All the high-value customers are VIP/Loyal. Among the mid-value customers, 72% are Potentially Loyal. However the remaining 28% are At Risk Customers. If no proactive measures are taken, these At Risk Customers may degrade to low-value status and eventually churn. They can be retained by offering targeted discounts or other form of rewards or loyalty incentives. 
<br> <br>
There are 768 low-value customers with nearly half of them already been lost. The remaining customers in this segment will also churn if no intervention occurs. It is essential to engage these customers with special offers and address any concerns or issues they may be facing to ensure that they don't leave.

![image](https://github.com/user-attachments/assets/c0e3e1f1-e43b-42dd-b6f4-7dd2c8c41dc8)

On an average, the VIP customers have RFM score of 3.40, 3.57, 3.55 respectively for each metric.
The Potentially Loyal customers have the RFM score of 2.43, 2.28, 2.29 respectively. 

![image](https://github.com/user-attachments/assets/3663fc4c-a678-4c71-b222-bcda9034e018)

Customers having RFM Score below 2 for each or any of the metric require attention.

<!---
<p><b>Data Source:</b> <a href="https://www.kaggle.com/datasets/ulrikthygepedersen/online-retail-dataset">Kaggle - Online Retail Datset (Version 2)</a></p>
--->
