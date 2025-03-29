# SC5002_Assignment3
This is the file for NTU SC5002 Lab Assignment 3 from Group 1 (LAM YUEN IN, WANG WEIQIAN, FANG XINQING)

**Project Explanation and Steps taken:**
 
  In this project, our aim is to examine two models using the same dataset -- k-means model and MLP (Multi-Layer Perceptron) model. We first applied the K-means algorithm from _sklearn.cluster_ to test the data using different k values. This method is to see how data groups themselves naturally, and minimizing the within-cluster sum of squares. Elbow method was used to figure out the optimal number of clusters to have for our data, where we get the result that 3 is the optimal value for k. In addition, silhouette score was applied to evaluate the clustering quality, where k=3 was found to have the highest silhouette score. As for the MLP (Multi-Layer Perceptron) model, we guided the network to learn the mapping from flower measurements to species labels. MLP performes an accuracy score of 96-97% from the 5-fold cross-validation method. Lastly, we used a confusion matrix to evaluate the performance of the classification model by comparing predicted labels with actual labels.
  
**Dataset Explanation:**
  
  The dataset we chose is the Iris dataset from the UCI Machine Learning Repository. The dataset contains data about flowers, and it consists of 150 samples and four numerical features which are categorized into three species. There is no missing values in the data, so all data were properly given.

**Insights**

1. Ridge Regression Model prevented overfitting in our dataset.
2. Linear Regression Model is more suitable for small datasets, where the relationship between variables is simple and few features comparing with the number of data provided.
3. Ridge Regression Model is more suitable for dataset with a lot of independent variables, and overfitting is a concern (the model fits the training data too well but performs poorly on new data).
