### Iris-EDA-and-Classification
In this project, I have performed Exploratory Data Analysis (EDA) on famous iris dataset which consists of data of three flower species known as Versicolor, Setosa and Virginica.

*Steps-*
1. First, I imported all the required modules such as NumPy, Pandas, Matplotlib, Seaborn to process and visualize the data.

2. Then, I loaded the data into iris_df variable using pd.csv_read function. This data consists of mainly five colums ( 4 features and 1 label). Features are sepal_length, sepal_width, petal_length and petal_width. Label is species.

3. After that I used plot.pie on label species to make pie of data that shows parts-to-the-whole relationship.
4. Then I visualize the data with boxplot. A boxplot is a standardized way of displaying the distribution of data based on a five number summary (“minimum”, first quartile, median, third quartile, and “maximum”). It can tell you about your outliers and what their values are.
5. Then again I visulize the data with an amazing function of seaborn that is pairplot. Pair plot is used to understand the best set of features to explain a relationship between two variables or to form the most separated clusters.
6. Further I imported modules from sklearn for splitting, training and testing.
7. After that I splitted my data into training_data(X_train, y_train) and testing_data(X_test, y_test) in ratio 2:1 and trained the model using DecisionTreeClassifier.
8. And finally I applied accuracy_score to check the accuracy on test set which turned out to be 98.0%.
