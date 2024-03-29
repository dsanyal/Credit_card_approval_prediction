# Credit card approval prediction
In this notebook, we will build an automatic credit card approval predictor using machine learning techniques.
We'll use the <a href="http://archive.ics.uci.edu/ml/datasets/credit+approval">Credit Card Approval dataset</a> from the UCI Machine Learning Repository and build a machine learning model that can predict if an individual's application for a credit card will be accepted.

I have used different classifiers to model the approval behaviour of banks towards credit card applications, including logistic regression, support vector machines and k-nearest neighbours.

#### Data Set Information:

 - All attribute names and values have been changed to meaningless symbols to protect confidentiality of the data. 

 - This dataset is interesting because there is a good mix of attributes -- continuous, nominal with small numbers of values, and nominal with larger numbers of values. There are also a few missing values.


Attribute Information:

- A1:	b, a. 
- A2:	continuous. 
- A3:	continuous. 
- A4:	u, y, l, t. 
- A5:	g, p, gg. 
- A6:	c, d, cc, i, j, k, m, r, q, w, x, e, aa, ff. 
- A7:	v, h, bb, j, n, z, dd, ff, o. 
- A8:	continuous. 
- A9:	t, f. 
- A10:	t, f. 
- A11:	continuous. 
- A12:	t, f. 
- A13:	g, p, s. 
- A14:	continuous. 
- A15:	continuous. 
- A16: +,- (target variable)