# GRIP INTERSHIP  TASK 2 - Finding Optimum Cluster In Iris Dataset 

While working with the k-means clustering scratch, one thing we must keep in mind is the number of clusters ‘k’. We should make sure that we are choosing the optimum number of clusters for the given data set. But, here arises a question, how to choose the optimum value of k ?? We use the elbow method which is generally used in analyzing the optimum value of k.

The Elbow method is based on the principle that “Sum of squares of distances of every data point from its corresponding cluster centroid should be as minimum as possible”.

<h1>STEPS OF CHOOSING BEST K VALUE</h1>

![optimum cluster ](https://aihubprojects.com/wp-content/uploads/2020/10/elbow-method-to-find-k.png)

1. Run k-means clustering model on various values of k 
2. For each value of K, calculate the Sum of squares of distances of every data point from its corresponding cluster centroid which is called WCSS ( Within-Cluster Sums of Squares)
3. Plot the value of WCSS with respect to various values of K
4. To select the value of k, we choose the value where there is bend (knee) on the plot i.e. WCSS isn’t increasing rapidly.
