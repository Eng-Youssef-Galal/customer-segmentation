# customer-segmentation
The code is performing exploratory data analysis (EDA) on the Mall Customers dataset using Python. Here's a brief explanation of what each section of the code does:

## 1.Importing necessary libraries:
numpy for numerical computations
pandas for data manipulation and analysis
matplotlib and seaborn for data visualization

## 2.Reading the dataset:
The Mall Customers dataset is read from a CSV file using pandas' read_csv() function.

## 3.Removing unnecessary columns:
The "CustomerID" column is dropped from the dataset using the drop() function with the axis parameter set to 1 (columns) and inplace parameter set to True to make the changes in the original dataframe.

## 4.Visualizing the distribution of data:
A violin plot is created for the "Age" column using seaborn's violinplot() function to visualize the frequency of different ages.

Two boxplots are created, one for "Spending Score (1-100)" and the other for "Annual Income (k$)", using seaborn's boxplot() function to visualize the distribution of these columns.

A barplot is created to show the count of customers for each gender.

Age groups are created and a barplot is created to show the count of customers in each age group.

Spending score and annual income groups are created and barplots are created to show the count of customers in each group.

## 5.Clustering the data:
K-means clustering algorithm is applied to the dataset using the KMeans() function from sklearn.

The optimal number of clusters is determined by finding the within-cluster sum of squares (WCSS) for different values of K (number of clusters) using the elbow method.

The dataset is labeled based on the clusters and a 3D scatter plot is created to visualize the relationship between age, annual income, and spending score for each cluster.

![download](https://github.com/Eng-Youssef-Galal/customer-segmentation/assets/138930263/515f6446-46cb-495f-87c4-02560ed2e4f3)
