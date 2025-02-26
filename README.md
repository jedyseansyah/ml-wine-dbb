# 🍷 Wine Classification with K-Nearest Neighbors

### Description:
This dataset is a data set used to classify grape types based on chemical analysis results. The data comes from three types of grape cultivars from Italy grown in the same region of Italy. The purpose of this dataset is to classify grape samples into one of three cultivar classes based on 13 chemical attributes that can be used to confirm the authenticity of a wine and detect adulteration in the beverage industry.

The dataset used comes from the scikit learn libary which is accessed via the following link: https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_wine.html#sklearn.datasets.load_wine.

### Goals:
1. Knowing the performance of the K Nearest Neighbors algorithm for determining wine classes.
2. Visualize the prediction results into a graph to facilitate understanding. 
3. Determine the column that has the most influence on the target prediction result.

### Algorithm Used
The algorithm used in this model is K-Nearest Neighbors. K-Nearest Neighbors (KNN) is a distance-based classification algorithm that determines the class of new data based on the majority of its nearest neighbors. KNN starts by determining the number of nearest neighbors (K), then calculating the distance between the new data and all data in the dataset, usually using the Euclidean Distance method. After that, the K nearest neighbors are selected, and the class that appears most often from these neighbors will become the class for the new data.

### Insights:
1. The K-Nearest Neighbors algorithm shows high accuracy for detecting wine classes, at 0.97
2. There are 3 features that are highly correlated with the target, namely flavanoids, total phenols, and OD280/OD315 of dilluted wines.
3. The three correlated features are all negatively correlated, meaning that the higher the feature, the lower the target value (the wine class may change).
4. The ash feature has a very small correlation, only -0.04. This shows that the ash feature has little effect on the target value.

If you have any suggestions or feedback, please don't hesitate to contact to me in direct message on Email: jedysyah@gmail.com
