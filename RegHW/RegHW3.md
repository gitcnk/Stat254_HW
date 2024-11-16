# HW3

Use this link to access data:
  
BW <-  read.csv('https://academics.hamilton.edu/mathematics/ckuruwit/Data/Birth_Weights1960.csv')


(a)  Construct a multiple regression model to predict the birthweight (bwt) measured in oz's of babies using the following variables:
age ,
height ,
weight.  
Note that these variables are about the mother.

(b)  Interpret the R^2 (R-sqaured) of your model.  Read the document on Bb related to R^2.  Give two interpretations of this metirc.


(c)  Interpret the residual standar error of your model.  Do you think this value is reasonable or is it too high/low?  Briefly explain. 

(d)  Construct two residual plots (histogram and qq plot) and briefly explain why we need to examine them.

(e)  Is the variable 'age'(mother's age) an important predictor of the weight of the baby?  Please answer this using a confidence interval.


(f)  Interpret the coefficient of 'height'.


(g)  Now add the variable 'gestation' into the model. Interpret the coefficient of 'gestation'.

(h) Did your model become a better model?  Justify your answer using appropriate summary stats and plots.

(i) Now build a simple model by using only the 'gestation' variable as a prodictor .  That is: lm( bwt ~ gestation).
If predicting the birtweight is your objective, which model (the simple one with one variable 'gestation' or the one with 4 variables in part(e) above) do you prefer?  Please justify your answer.

