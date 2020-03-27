# Montreal-Local-Tv-Prediction
purpose is to predict how much test data channels will take,by using supervised machine learning methods, finding the relation between features(columns) and also donig suitable feature selection...
i try to predicting
by good feature selection
some features were dropped because of:
-equal values in multi columns
-some that were not in test set
-some that had low correlation with together
-some that have low effect on resut (undrestand by plotting them)
for every season,the data analyzed and get that,i have no affect or differ in results,so i decided to delete the codes!
then,try to preprocess and make numeric data ror getting ready for model input:)
analyze the data and find the best feature for making reasonable accuracy:)
it is good to say that,since the test set had not any columns for y lable(market share),i try to split train data to test and train data and get the models accuracy, the for the best model, i predict y lables:)
for modeling i had diffrent ideas and have to reason to delete some models,so try to retain all models in code!
base model is LinearRegression and after that:
-AdaBoost
-DecisionTree
-DecisionTree 20FoldCross
-RandomForest
-RandomeForestRegression
-AdaBoostRegression


