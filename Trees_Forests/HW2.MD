## The purpose of this HW is to understand some aspects of Classification Trees.  In particular, the Gini score and the "Variable of Importance" metric.

**Definition:** 
Gini = $1 - \sum_{j=1}^k p_j^2$

where $p_j$ is probability of class 'j' and k is the number of classes.  For example, k = 2 for binary outcomes.

Answer the following questions:

1. For binary outcomes, show that Gini = $p_1(1-p_1) + p_2(1-p_2)$.

2. For outcomes with 3 classes (eg. Cancer, No Cancer, Maybe), show that

Gini = $p_1(1-p_1) + p_2(1-p_2)+ p_3(1-p_3)$.


3. When we create a Classification Tree, we get a set of values called "variable of importance" scores. Briefly explain how this metric is calculated.  Perhaps drawing some picture by hand would help to construct your answer.  
