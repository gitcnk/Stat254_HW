# Trees and Forests

``wine_red <- read.csv("https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-red.csv",
sep = ";")``

- Task: To build a tree and forest model to predict wine quality.

- Data Source: From UC-Irvine ML repository. 

- Number of predictors (x-variables) - 11

- Response variable (Y) : 'quality' (ranges from 1--8); The min in the dataset is 3.


### Please answer the following questions:


1. Following what we did in class, create a training set and a validation set (test set) from your data.  
Please use 1200 for the training set and the rest for the validation set.




2. Construct a tree model using your training data.  Please include your code and the plot of the tree.




3. Click on any of the terminal nodes (the ones displayed as squares) in your tree.  Explain how mean and variance values are computed.



4. Create the "going-to-the-beach" plot to assess the accuracy of your model.  Do this for both the training set and the test set. Please attach your plot.


5. What are the 3 most useful predictors in predicting wine quality.




6. Compare your tree model with a random forest model. Please use 100 trees and 3 predictor at each split of each tree.  In particular, compare the  "going-to-the-beach" plots of both models using the test set.  Please attach your plots.




