# Trees and Forests

Use this link to access the data:

``wine_red <- read.csv("https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-red.csv",
sep = ";")``

- Task: To build a tree and a forest model to predict wine quality.

- Data Source: From UC-Irvine ML repository. 

- Number of predictors (x-variables) - 11

- Response variable (Y) : 'quality' (ranges from 1--8); The min in the dataset is 3.


### Please answer the following questions:


<!--- (1. Following what we did in class, create a training set and a validation set (test set) from your data.  
Please use 1200 for the training set and the rest for the validation set.) -->

1. Construct a linear model to predict the wine quality using ALL predictors.  Which variables seem to be more predictive of Wine quality.  Use confidence intervals to answer this question. 


2. Construct a tree model to predict the wine quality using ALL predictors.  Please include your code and the plot of the tree.




3. Click on any of the terminal nodes (the ones displayed as squares) in your tree.  Explain how mean and variance values are computed.



4. Create the "going-to-the-beach" plot to assess the accuracy of your model.  Please attach your plot.


5. Based on your tree what are the 3 most useful variables in predicting the wine quality.




6. Compare your tree model with a random forest model. Please use 100 trees and 3 predictors at each split of each tree.  In particular, compare the  "going-to-the-beach" plots of all 3 models. Please attach your plots.

7.  **(Bonus 2pt)** Redo #6, but this time construct a single "going-to-the-beach" plot with ALL 3 model predictions.   Use different colors and shapes to denote the 3 models for clarity.  You can use `col` and `shape` aesthetics in `ggplot` to do this.  I encourage you to **NOT USE GPT** for this.  You have the skills to do it!

   




