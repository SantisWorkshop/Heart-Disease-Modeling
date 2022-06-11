# Heart-Disease-Modeling
Source: https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease?resource=download
So this time I have done yet another modeling project but this time with my friend Santiago. The data set was straightforward: just
a data set with less than 20 variables of potential predictors of heart disease as well as the heart disease indicator variable.
The project was for us to see if we can create a model that can adequately predict heart disease in people using the other varaibles, but
we ran into a couple of issues outside our control. 1: There was no unique id variable to indicate seperate entities among the obseravtions
and also caused issues with checking for duplicates. 2: The data set is heavily compressed. The data set is a heavily modified version of the 
one provided by the CDC, ommitting tons of information. 3: The data set was modified specifically to be used for classification models and 
almost nothing else. 4: The data set doesn't have information such as family history of heart disease. This isn't a problem with the data set
we used, this was a problem seen in the original CDC data set that our set was based on. 
We did find that our models were able to predict whether someone DIDN'T have heart disease accurately, but we had very low prediction rates 
for those that do. Even observing the other models people have done on the Kaggle page, we see that this model was never going to give us
a fair prediction rate for those that do have heart disease. Our project remains inconclusive for now.

Credits for this project: Oscar Monroy https://github.com/omonroy20(hd_analysis_rf; random forest model), Santiago Rodriguez (hd_analysis_log; logistic regression model)
