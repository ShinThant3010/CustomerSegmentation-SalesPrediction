# Customer-Segmentation-and-Prediction-using-ML

Business Intelligence Analysis (BIA) group project with four members. 

Dataset: 
- sales data of an actual retail business in Myanmar from June 2018 to December 2020 (159,682 records) including customer, product, and salesman information. 

Methodology:
- Customer Segmentation using Kmeans on RFM (Recency, Frequency, Monetary) analyzed data
- Sales Prediction using LSTM
- For sales prediction, 
  - Since we have only two years data, prediction for overall sales may not give a good result. Moreover, our data is obtained from an actual retail
system, the sales trend is affected by the pandemic (Covid-19).
  - For these reasons, we decided to predict sales over specific products. We focus on three best selling products under the ‘O2’ product brand. We
analyze individual product trends to predict each product's sales respectively.
  - We predicted the amount of sales in the last 4 months based on the first 20 months.
