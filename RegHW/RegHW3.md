# Regression HW3

*Use this link to access data*
  
``BW <-  read.csv('https://academics.hamilton.edu/mathematics/ckuruwit/Data/Birth_Weights1960.csv')``


1.  Construct a multiple regression model to predict the birthweight (bwt) of babies using the following predictor variables:
* age 
* height
* weight 

*Note that these variables are about the mother.*

2.  Interpret the $R^2$ (R-sqaured) of your model.  Read the document on Bb related to $R^2$.  Give two interpretations of this metric.


3. Interpret the residual standar error of your model.  Do you think this value is reasonable or is it too high/low?  Briefly explain. 

4.  Construct two residual plots (histogram and qq plot) and briefly explain why we need to examine them.

5.  Is the variable 'age'(mother's age) an important predictor of the weight of the baby?  Please answer this using a confidence interval.


6.  Interpret the coefficient of 'height'.


7.  Now add the variable 'gestation' into the model. Interpret the coefficient of 'gestation'.

8. Did your model become a better model?  Justify your answer using appropriate summary stats and plots.

---

9. Now build a simple model by using only the 'gestation' variable as a prodictor .
    ``That is: lm( bwt ~ gestation)``
If predicting the birtweight is your objective, which model (the simple one with one variable 'gestation' or the one with 4 variables in part 7 (above) do you prefer?  Please justify your answer.

