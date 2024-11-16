The following data is about colleges in th US. The data was collected in 2016.

*Use the following command to access the data.*

``colleges <- read.csv('https://raw.githubusercontent.com/gitcnk/Data/master/colleges2016.csv')``


* The goal of this homework is to understand interaction terms.  That is, where the effect of one variable dependes on the values of another variable.

* For example, in class we discussed the example where the efect of job difficulty  on salary was dependend on the female-dominated job categories.  


The specific goal of this analysis is to see how student debt is related to tuition and what type interactions does it have with private vs. public colleges.


1. Draw a scatterplot of x = tuition, y = median_debt.  Do not add any reression lines. Color the points based on private or public nature of the institute.  If you do this right you'll see a familar trend and also a  strange relationship.  Briefly explain what you observe especially the 'strange' part of the plot.


2. To make life easier, create a separate dataset with tuition values less than $40,000.
Name this dataset as 'Typical_colleges'.  Our alanlysis will be focused only on the typical ones (not on the strange part).  We need a separate analysis for the non-typical ones, but's that's separate HW.

3. Now redo the plot in #1 with this new dataset. Add the regression lines, one for public and one for private.


4. Find the equations of the two regression lines using the lm() command.  Make sure to add the interaction term, otherwise your answer will be incorrect.  Write down the two equations separately, one for public and one for private.


5. Using a confidence interval explain whether the effect of tuition on debt is similar between private and public colleges.


6. Do you trust your confidence interval in #5?  Please say yes or no first, then justify your answer by providing appropriate evidence.









