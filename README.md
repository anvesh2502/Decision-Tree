# Decision-Tree
A decision tree classifier to predict the prices of houses using the Zillow Api

In this analysis,the dataset being investigated is the Zillow api for housing.The Zillow api provides various features of a house such as 
number of bedrooms,number of bathrooms,square feet,total rooms and many other features.To predict house prices with such features,one of the
better options is Decision Trees.In this analysis,a decision tree is built using the features.The trees are recursively divided by gini 
impurity and calculating entropy.The tree is also pruned just to make sure that the tree does not suffer from overfitting i.e it does not 
make decisions very specifically by calculating the information gain of each level
