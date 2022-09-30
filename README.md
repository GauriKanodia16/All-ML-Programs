# All-ML-Programs

About the dataset
The data were obtained in a survey of students math and portuguese language courses in secondary school. It contains a lot of interesting social,
gender and study information about students. 

Lab 1 Basic Exploratory Data Analysis
Exploratory Data Analysis refers to the critical process of performing initial investigations on data so as to discover patterns,
to spot anomalies,to test hypothesis and to check assumptions with the help of summary statistics and graphical representations.

step 1: basic  data cleaning 
1. Extracting important variables and leaving behind useless variables
2. Identifying outliers, missing values, or human error
3. Understanding the relationship(s), or lack of, between variables
4. Ultimately, maximizing your insights of a dataset and minimizing potential error that may occur later in the process

step 2: Analyzing relationships between variables

Correlation Matrix
The first thing I like to do when analyzing my variables is visualizing it through a correlation matrix because it’s the fastest way
to develop a general understanding of all of my variables. To review, correlation is a measurement that describes the relationship between 
two variables Thus, a correlation matrix is a table that shows the correlation coefficients between many variables. 
I used sns.heatmap() to plot a correlation matrix of all of the variables in the used car dataset.

Scatterplot
It’s pretty hard to beat correlation heatmaps when it comes to data visualizations, but scatterplots are arguably one of the most useful 
visualizations when it comes to data.

Histogram
Correlation matrices and scatterplots are useful for exploring the relationship between two variables. But what if you only wanted to explore 
a single variable by itself? This is when histograms come into play. Histograms look like bar graphs but they show the distribution of a variable’s set of values.

Boxplot
Another way to visualize the distribution of a variable is a boxplot. We’re going to look at ‘price’ this time as an example.

Lab 2: KNN
K-nearest neighbors (kNN) is a supervised machine learning algorithm that can be used to solve both classification and regression tasks.
I see kNN as an algorithm that comes from real life. People tend to be effected by the people around them. 

The K-NN working can be explained on the basis of the below algorithm:
Step-1: Select the number K of the neighbors
Step-2: Calculate the Euclidean distance of K number of neighbors
Step-3: Take the K nearest neighbors as per the calculated Euclidean distance.
Step-4: Among these k neighbors, count the number of the data points in each category.
Step-5: Assign the new data points to that category for which the number of the neighbor is maximum.
Step-6: Our model is ready.

[[ 11   4]
 [ 26 154]]
              precision    recall  f1-score   support

           0       0.30      0.73      0.42        15
           1       0.97      0.86      0.91       180

    accuracy                           0.85       195
   macro avg       0.64      0.79      0.67       195
weighted avg       0.92      0.85      0.87       195


obtained accuracy using knn 0.85  

Lab 3: Naive Bayes
Naive Bayes is an interpretable model because of the independence assumption. It can be interpreted on the modular level.
It is very clear for each feature how much it contributes towards a certain class prediction, since we can interpret the conditional probability.

Gaussian Naive Bayes model accuracy(in %): 82.05128205128204

Lab 4: K-Means clustering
K-means clustering is an extensively used technique for data cluster analysis.
It is easy to understand, especially if you accelerate your learning using a K-means clustering tutorial. Furthermore, it delivers training results quickly.

![image](https://user-images.githubusercontent.com/95648759/193256820-9f50d856-9bd9-4107-987a-9d62cd9bf435.png)

