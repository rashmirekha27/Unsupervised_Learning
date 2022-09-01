# unsupervised_learning
Unsupervised learning by fitting data to a model and using clustering algorithms to place data into groups. Created a visualization that shares findings. provided with raw data, so you’ll first need to process it to fit the machine learning models. You will use several clustering algorithms to explore whether the patients can be placed into distinct groups. Then, you’ll create a visualization to share your findings with your team and other key stakeholders.

Part 1: Prepare the Data, dropped nulls
Part 2: Apply Dimensionality Reduction 
Part 3: Perform a Cluster Analysis with K-means
Part 4: Make a Recommendation 

Added `myopia.csv` data into a Pandas DataFrame. Removed the "MYOPIC" column from the dataset.Standardize the dataset so that columns that contain larger values do not influence the outcome more than columns with smaller values.Performed dimensionality reduction with PCA. Checked the number of the features changed? The dataset dimensions with t-SNE and visually inspect the results. Created a scatter plot of the t-SNE output. Are there distinct clusters?
Used a `for` loop to determine the inertia for each `k` between 1 through 10

![image](https://user-images.githubusercontent.com/101225094/187982753-ec32e3f2-cc7a-4981-8118-676ebcbc8104.png)
![image](https://user-images.githubusercontent.com/101225094/187982839-7267c28f-d43e-4dce-9e4e-c45350247286.png)
![image](https://user-images.githubusercontent.com/101225094/187982910-633143a1-2870-404a-8041-3742a20e39aa.png)

