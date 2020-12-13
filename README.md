# Boston-Marathon-KmeanClustering-LinReg-in-Python

Boston marathon finisher's unsupervised and supervised methods analysis using Kmean clustering and linear regression to find finishers groups and paces.


1. Summary
	- Data exploration was performed: 25 attributes with 5 integers and 20 strings. Most columns contains either null or "-" value or both. All time attributes are string type. The distance unit used are also different, some is KM and some is mile.
	- Data processing: missing values mostly in attributes that were not interested for further analysis, so they weren't process. "-" were removed. Time attributes were converted into float type. 
	- Summarized data statistics: histogram, boxplot, and scatter plot were applied to see distribution of each columns and relationship between 2 attributes. 
	- Unsupervised learning method with K-mean clustering. K-mean was employed to segment finishers by their age and finish time. Elbow methods was used to select the no. of groups the data should be segmented into.  K-mean was performed, fitted,  and predicted. Then, cluster charted was created to show the groups of data. 
	- Supervised learning method: employed linear regression to analyse pace profile of each group which was segmented in the unsupervised method. Then, fitness was measured with MAE, MSE, and R2.

2. Tool: Python.

3. Algorithm: K-mean and linear regression.

4. Evaluation:
	- Completeness and homogeneity scores for k-mean.
	- Mean Absolute Error, Mean Squared Error, Root Mean Square Error, and r2 for linear regression.

5. Dataset: The Finishers of Boston Marathon 2017 dataset from https://www.kaggle.com/. 
There are 26,410 records and total of 25 attributes. 
