# Random-Forest-Classifier
3rd Class exercise - training a random forest on a multi-dimensional dataset

Random Forest is an ensemble learning method used for classification and regression tasks that builds multiple decision trees during training. It combines the predictions from each tree to improve accuracy and control overfitting. Each tree in the forest is trained on a random subset of the data and a random subset of features, promoting diversity among the trees. By averaging or voting on the predictions of individual trees, Random Forests can produce more robust and accurate predictions than a single decision tree.

In this exercise we were asked to train the classifier on Pima dataset, we also examined the influence of 2 main parameters of a random forest classifier - max depth and number of trees (n_estimators) on the accuracy of the train and test dataset. After checking both parameters, we chose the optimal values to run them both together.

## The exercise
1. Train the classifier and measure the accuracy.
    
    a. Load the data and split it 80% for train, 20% for test.
    
    b. Specify the classifier's different parameters values (number of trees, maximum number of leaves etc.). If you didn't set them yourself, check the default values set by sklearn.
    
    c. What is the train and test datasets accuracies?
    
    d. What are the confusion matrixes of the train and test datasets?
    
    e. State the importance of each feature in achieving the classifier's performance.
    
    
2. Test the influence of the different parameters on the classifier's performance, use cross validation:

    a. Number of trees (set by n_estimators).
    
    b. The maximum depth of each tree (set by max_depth)
#### Make sure to plot the results.


3. Based on your results, choose the optimal values to set the parameters and explain why this is the optimal value.
