# Machine Learning

## Unsupervised Learning

### Clustering Model

KMeans, OL Portfolio, this program is an example of a clustering model using unsupervised learning to train the program to group the data, sort of like the K-NN model.  The program goes step by step through this process: 
1. choose 'k' (number of clusters) as 3, 
2. Randomly initialize three centroids, 
3. Assign each data point to the closest centroid, 
4. Calculate the new centroids based on the assigned data points, 
5. Repeat the assignment and centroid update steps for a few iterations until convergence, 
6. Once the program is done, you'll have three clusters with customer data points grouped together and a classification report of the data.  
The classification report of the graph can be interpreted through its 4 categories (precision, recall, f1-score, and support).
The precision tells you how much of the data put in a group actually belongs there.
The recall represents the proportion of data points that truly belong to a cluster.
The f1-score measures the programs's effectiveness in terms of both precision and recall.
The support shows the true size of each cluster of data. 

Libraries:

- [Numpy](https://www.youtube.com/watch?v=lLRBYKwP8GQ&t=1073s)
- [Pandas](https://www.youtube.com/watch?v=zN2Hua6oII0&t=8s)
- [matplotlib](https://www.youtube.com/watch?v=nzKy9GY12yo)
- [scikit-learn intro](https://www.youtube.com/watch?v=rvVkVsG49uU)
- [scikit-learn tut](https://www.youtube.com/watch?v=M9Itm95JzL0)