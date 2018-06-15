# customer-segmentation-python
This project applies customer segmentation to the customer data from a company and derives conclusions and data driven ideas based on it.
### Dataset
This data set is the customer data of a online super market company Ulabox. The data set is available in this link https://github.com/ulabox/datasets
### Customer segmentation
In customer segmentation we categorize similar customers together in the same cluster and analyse them. It can reveal information like: 
1) who are the most valuable customers of the company 
2) what kinds of customers does the company have
3) This can be used for targeted marketing and other marketing strategies.
4) Sometimes it can even reveal a potential white space in the market place which no company has yet occupied.
Well we can get creative here.
### Clustering
Clustering is a process in which we put similar data points into the same cluster. There are a lot of algorithms to do this, for example agglomerative heirarchical clustering, kmeans clustering, Gaussian Mixture Model etc.
## Map to the project
1) The order_segmentation_0.0.ipynb file contains detailed notes and explanation of doing segmentation of orders in the data. I have also added my ideas in it. It's a clean walk through. I suggest to start there.
2) The customer_segmentation.ipynb file tries to do segmentation of customers in the data. It is very much similar to the order segmentation notebook. Though it doesn't have a lot of explanation you should be able to understand it after going through the former notebook. At the end of this notebook it gets real interesting.
3) I have added another file which is a bunch of functions that could help in visualizing and finding meaningful clusters within the data. These functions provide various ways to analyse for clusters in the data.<br>
4) Model_Building.ipynb is where we build a model to predict the class of each customer, which can be used to find the classes of customers in future. I have added some ideas there.
5) The two csv files are the results after clustering.<br>
Thank you for your time :)
