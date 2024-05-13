# Customer-Segmentation-using-clustering
Customer Segmentation using clustering.
### Overview
Customer Segmentation is one the most important applications of unsupervised learning. Using clustering techniques, companies can identify the several segments of customers allowing them to target the potential user base. In this machine learning project, we will make use of [K-means clustering](https://data-flair.training/blogs/k-means-clustering-tutorial/) which is the essential algorithm for clustering unlabeled dataset. Before ahead in this project, learn what actually customer segmentation is.<br>


### What is Customer Segmentation
Customer Segmentation is the process of division of customer base into several groups of individuals that share a similarity in different ways that are relevant to marketing such as gender, age, interests, and miscellaneous spending habits.<br>

Companies that deploy customer segmentation are under the notion that every customer has different requirements and require a specific marketing effort to address them appropriately. Companies aim to gain a deeper approach of the customer they are targeting. Therefore, their aim has to be specific and should be tailored to address the requirements of each and every individual customer. Furthermore, through the data collected, companies can gain a deeper understanding of customer preferences as well as the requirements for discovering valuable segments that would reap them maximum profit. This way, they can strategize their marketing techniques more efficiently and minimize the possibility of risk to their investment.<br>

The technique of customer segmentation is dependent on several key differentiators that divide customers into groups to be targeted. Data related to demographics, geography, economic status as well as behavioral patterns play a crucial role in determining the company direction towards addressing the various segments<br>
### What is K-Means Algorithm
While using the k-means clustering algorithm, the first step is to indicate the number of clusters (k) that we wish to produce in the final output. The algorithm starts by selecting k objects from dataset randomly that will serve as the initial centers for our clusters. These selected objects are the cluster means, also known as centroids. Then, the remaining objects have an assignment of the closest centroid. This centroid is defined by the Euclidean Distance present between the object and the cluster mean. We refer to this step as “cluster assignment”. When the assignment is complete, the algorithm proceeds to calculate new mean value of each cluster present in the data. After the recalculation of the centers, the observations are checked if they are closer to a different cluster. Using the updated cluster mean, the objects undergo reassignment. This goes on repeatedly through several iterations until the cluster assignments stop altering. The clusters that are present in the current iteration are the same as the ones obtained in the previous iteration.<br>

### Dataset
The dataset is aquired from kaggle and the link is given below :

https://www.kaggle.com/nelakurthisudheer/mall-customer-segmentation

The dataset consists of following five features of 200 customers:

-  CustomerID: Unique ID assigned to the customer

-  Gender: Gender of the customer

-  Age: Age of the customer

-  Annual Income (k$): Annual Income of the customer

-  Spending Score (1-100): Score assigned by the mall based on customer behavior and spending nature.


### K-means Algorithm
-  We specify the number of clusters that we need to create.
-  The algorithm selects k objects at random from the dataset. This object is the initial cluster or mean.
-  The closest centroid obtains the assignment of a new observation. We base this assignment on the Euclidean Distance between object and the centroid.
-  k clusters in the data points update the centroid through calculation of the new mean values present in all the data points of the cluster. The kth cluster’s centroid has a -  -  Length of p that contains means of all variables for observations in the k-th cluster. We denote the number of variables with p.
-  Iterative minimization of the total within the sum of squares. Then through the iterative minimization of the total sum of the square, the assignment stop wavering when we -  -  Achieve maximum iteration. The default value is 10 that the R software uses for the maximum iterations.<br>
