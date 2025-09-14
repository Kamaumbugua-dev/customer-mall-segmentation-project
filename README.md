# customer-mall-segmentation-project
Part A — Load & basic EDA (1–8)
1.	Load the CSV into a Pandas DataFrame and show the first 5 rows.

2.	Show the dataset shape (rows, columns) and column names with dtypes.

3.	Count unique values per column and list the top 10 most frequent values in a categorical field.

4.	Find missing values per column and report counts.

5.	Show summary statistics for numeric columns: mean, median, std, min, max, quartiles.

6.	Convert a numeric column (e.g., Age) into bins (e.g., Young, Adult, Senior). Show counts by group.

7.	Detect and count any unrealistic values (e.g., negative or zero values).

8.	Find how many unique customers exist and which group/category is most common.

________________________________________
Part B — Data cleaning & filtering (9–15)
9.	Remove rows with missing values in a key column and explain the pros/cons.

10.	Drop duplicate rows and report how many were dropped.

11.	Filter out records where Age < 18.
14.	Bucket customers into categories based on quantiles (e.g., spending level).

15.	Explain and apply feature scaling to numeric features.

________________________________________
Part C — Aggregation & feature engineering (16–22)
16.	Compute average income by gender using groupby.

17.	Calculate max, min, and mean for numeric columns per group.

18.	Create a new ratio feature (e.g., income-to-age).

19.	Flag “High value” customers based on income and spending greater than average.

20.	Compute correlation between numeric features.

21.	Determine which gender has a higher average spending score.

22.	Create a pivot table by age group and gender for average spending.

________________________________________
Part D — Visualizations & group exploration (23–27)
23.	Plot a histogram of the Age distribution.

24.	Create a bar chart of average spending score by gender.

25.	Create a scatter plot of Annual Income vs Spending Score.
26.	Create a boxplot of spending score grouped by age bins.

27.	Create a heatmap of correlations between numeric features.

________________________________________
Part E — Dimensionality reduction (PCA & t-SNE) (28–31)
28.	Run PCA on standardized income and spending features and plot explained variance.

29.	Plot 2D PCA components scatter colored by a category (e.g., Gender).

30.	Run t-SNE and plot the 2D embedding.

31.	Compare PCA and t-SNE plots — which shows clearer clusters?

________________________________________
Part F — Clustering & evaluation (32–40)
32.	Run k-means for k=2…10 on standardized features and plot the elbow curve.

33.	Compute silhouette score for each k and identify the best k.

34.	Plot clusters for the chosen k using a scatter plot.

35.	Run hierarchical clustering and visualize a dendrogram.

36.	Cut the dendrogram at k clusters and compare with k-means.

37.	Profile each cluster: average age, income, spending score.
38.		Check cluster sizes — are some clusters too small?

39.	Run k-means with different random states and see if cluster assignments change.

40.	Export the dataset with cluster labels to CSV.
12.	Create a new categorical column from numeric data using conditional statements.

13.	Replace missing values in a numeric column with the mean.
