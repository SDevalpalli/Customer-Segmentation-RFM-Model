# RFM segmentation model #
The business objective of this project was to increase the conversion rate of emails to purchases using a suitable customer segmentation model on existing users who opted to receive emails to improve marketing efforts via personalised email recommendations. The choice of segmentation used was a modified RFM model.
The tools used in this project are as follows:
* SQL using BigQuery
* Microsoft Power BI
* Microsoft Powerpoint

Along with the customer segmentation for email marketing, the below KPIs were calculated for each segment to compare how customer behaviour changed over time:
* Total Revenue per segment
* No. of customers per segment who opted for email.
* Average email conversion rate.

Below is a schema of how the customer base was segmented via the recency, frequency and monetary elements of RFM.

* Ranked each section 1-5.
* Recency - the date of a customer’s last order.
* Frequency - the total number of transactions per customer.
* Monetary - total revenue generated per customer.  

Score | Recency | Description
:---: | :---------: | :---------------------------:
  1   | 1st 20%  |  Most Recent
  2   | 2nd 20% |  Relatively Recent
  3   | 3rd 20% |  Somewhat Recent
  4   | 4th  20% |  Less Recent
  5   | 5th 20%  |  Not Recent
  

Score | Frequency | Description
:---: | :----------: | :---------------------------:
  1   | Top 5%    |  Most Frequent
  2   | Top  20% |  Relatively Frequent
  3   | Top 30% |  Somewhat Frequent
  4   | Top 60% |  Less Frequent
  5   | Bottom   |  Not Frequent
  

Score | Monetary | Description
:---: | :----------: | :---------------------------:
  1   | Top 5%    |  Most Money
  2   | Top  20% |  High Money
  3   | Top 30% |  Medium Money
  4   | Top 60% |  Low Money
  5   | Bottom   |  Lowest Money
  
  
Using this scoring system we could segment the customers and personalise recommendations for these separate groups to increase the conversion rate from email to purchase.

Below is the finalised dashboard used in the reports of the project:

![Power BI Dashboard for RFM Segemntation](https://github.com/SDevalpalli/Customer-Segmentation-RFM-Model/commit/24a5f2d876fec7e3c612fb07d7457120ed867077)

![Customer Segmentation_RFM_Dashboard](https://github.com/SDevalpalli/Customer-Segmentation-RFM-Model/assets/ff95296bd9f6e7139d3b253b03128de427be57c3)
