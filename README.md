# Fetch Rewards Tasks

## NLP Task:

Fetch process and reward points to its customers for both types of receipts. A customer can snap and upload the picture of physical (paper) receipts to get rewards. They can connect their email account or amazon account to process digital receipts (eReceipts) and get points. In this exercise we will focus on eReceipt processing.

Task
When a customer places an order, they receive several emails from the retailers/stores regarding their purchases. Not all of these emails that end up in their inbox are actual eReceipts. Explain your approach on how you would identify which email is a genuine eReceipt and not a shipping update/ marketing email/ refund/ return/ cancellation type email.

How would you identify and extract the key information of interest from these eReceipts?

Key information include but not limited to following: store_name, receipt_date, receipt_subtotal, receipt_total, order_id, product_description, product_quantity, product_price.

Deliverables
Prepare a write up that answers the following:

Describe your approach/methodology to solve above mentioned tasks.

Description of Machine Learning/Deep Learning algorithms/models and frameworks you would choose.

How would you evaluate the proposed solution?

Diagrams/reference links etc. (code samples are bonus)

These all are answered in notedbook **DS_NLP.ipynb.**

## User Social Networks:

Fetch users may friend each other to share product recommendations, or compete for top spots on points leaderboards. Graphs can be used to analyze these social networks. For example, we can assess the relative influence of users, or predict the likelihood of user links or attributes. We can also detect communities.

The next data collection includes the nodes of all users who all have at least one friend in Wisconsin. They each have one binary attribute indicating whether they, themselves, are from Wisconsin or not. The edge data indicates which users are friended with whom.

Write a routine to ingest this data. Select and train a mode to describe how many natural communities of Fetch users exist in Wisconsin.

Your solution may include any or all of the following:

Discuss different measures of betweenness that could apply to the problem

Select one or more standard clustering algorithm(s) for the problem and explain your choice(s)

Write your own clustering algorithm

Write a training routine to arrive at your best model for this data

Discuss how you tuned the model, especially highlighting different measures you may have tried

Describe your clusters in terms of internal characteristics that unit them, or boundaries that separate them

These are answered in **Fetch_Social_Networks_Graph.ipynb**

##  Graph Anomaly Detection:

At Fetch we use Graph ML to find anomalous points in our data warehouse. Anomalous points can indicate remarkable new trends, or they can identify a weakness in a data pipeline that needs repairing.

The attached data describes anomalies in Fetch’s data warehouse. Your responsibility is to train a model to find similar issues and flag for resolution. Write a routine to ingest this data. Select an appropriate model to train and share your results.

The data has these nodes, node attributes and edges. The y variable indicates whether a node is an anomaly or not.

Data(x=[5794, 4], edge_index=[2, 430548], y=[5794, 1])

Your solution may include any or all of the following:

Profile the node attributes and discuss what embeddings they suggest

Select a framework

Select one or more standard classification algorithm(s) for the problem and explain your choice(s)

Write your own classification algorithm

Write a training routine to arrive at your best model for this data

Discuss how you tuned the model, including selection of hyperparameters, loss, and activation functions

Predict how your model will perform on unseen data

These are answered in the notebook **Graph_anomaly_detection.ipynb**
