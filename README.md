# Customer Segmentation with RFM-Based Clustering


**Version 1.0**

Here you'll find two jupyter notebooks (python) with the objective is to showcase a simple example of calculating **RFM scores** from customers' orders, which are used as data input for a **clustering model**, whose ouput serve to characterize/categorize segments of clients. This could be insightful for companies/organization whose business/profit model is based on a subscription/SaaS, or require continuous engagment from their customers in order to be successful.

The code should be executed as follows:
- First, **RFM_Scores.ipynb**, to calculate the RFM scores for all clients, fron their orders.
- Then, **Clustering_Model.ipynb**, that utilizes the RFM scores to determine the potential categories/segments those customers belong to. 

The input dataset requires the following  fields to work:
- **Customer Id** to identity each client.
- **Order Id** to identify each order of every customer.
- **Order Date** and **Order Amount** to describe those orders.



Note:
- The dataset, about customers' orders (included in this repository) is just an example, it doesn´t represent or reflect any real data (is **dummy data**).

---

## Developer
- Jose Alberto Salazar Jiménez <jasj.1991@gmail.com>

---

## RFM Scores (Analysis) in a nutshell:
An **RFM Analysis** is used to segment/categorize customers around three measures:
    - Recency (R): when was the last time a client bought/paid something.
    - Frequency (F): how often does a customer buy/pay soemthing.
    - Monetary Value (M): what the total amount of every order related to a client.

Here you can check more information about what an RFM analysis:
- [What Is Recency, Frequency, Monetary Value (RFM) in Marketing?](https://www.investopedia.com/terms/r/rfm-recency-frequency-monetary-value.asp)
- [RFM Analysis](https://www.ibm.com/docs/en/spss-statistics/saas?topic=marketing-rfm-analysis)
- [RFM (market research)](https://en.wikipedia.org/wiki/RFM_(market_research))
