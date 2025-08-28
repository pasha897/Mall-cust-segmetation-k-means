# Mall-cust-segmetation-k-means
This project uses K-Means clustering for mall customer segmentation, grouping people by features like age, income, and spending score. The Elbow Method helps choose optimal clusters, and scatter plots visualize groups. Insights support targeted marketing strategies and better customer engagement.
This project applies K-Means clustering, an unsupervised machine learning algorithm, to perform customer segmentation for a mall. The aim is to group customers into distinct clusters based on purchasing behavior and demographic attributes, helping businesses design targeted marketing strategies.

The dataset typically contains customer information such as CustomerID, Gender, Age, Annual Income, and Spending Score. Since the goal is segmentation rather than prediction, there is no target variable. Instead, the model learns patterns and groups similar customers together.

The workflow begins with importing essential libraries such as Pandas, NumPy, Matplotlib, and Seaborn. The dataset is loaded, and exploratory data analysis (EDA) is performed to understand distributions and relationships. Features like Annual Income and Spending Score are often chosen for clustering, though Age can also be included.

Before applying K-Means, the Elbow Method is used to determine the optimal number of clusters (k). This involves running K-Means with different k values and plotting the Within-Cluster-Sum-of-Squares (WCSS) to find the “elbow point,” where the curve starts flattening.

Next, the K-Means algorithm is applied with the chosen k. The model assigns each customer to a cluster by minimizing distances between data points and their respective cluster centroids. After clustering, visualization techniques such as scatter plots are used to show customer groups, often with Annual Income vs. Spending Score on the axes.
