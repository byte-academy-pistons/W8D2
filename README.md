# W8D2
Ridge and Lasso Regression

The wine.csv data describes chemical and ingredient level wine data (eg. sugar, acidity level). Based on these the quality of the wine is selected (on a scale of 3-8). Your task is to predict the quality of the wine according to the following rule: 'good' (rating > 5) & 'bad' (rating <= 5).

Do the following:

1) conduct exploratory analyis and create hypothesis (which features do you think impact most?)
2) in your exploratory analysis, conclude if data scaling is required or not.
3) Run the model using the following algos: Logistic Regression, KNN, SGDClassifier and Ridge and Lasso Regression
4) Analyse the results of each algos results and report a confusion matrix (with precision and recall
5) For KNN, Ridge and Lasso regression, provide visualizations of your different regressions

Data Variables:

*Variable, Description, Units*

pH,	acidity (below 7) or alkalinity (over 7),	N/A
Density,	density,	grams/cubic centimeter
Sulphates,	potassium, sulfate	grams/liter
Alcohol,	percentage alcohol,	% volume
Residual sugar,	residual sugar,	grams/liter
Chlorides,	sodium chloride,	grams/liter
Free SO2,	free sulphur dioxide,	milligrams/liter
Total SO2,	total sulphur, dioxide	milligrams/liter
Fixed acidity,	tartaric acid,	grams/liter
Volatile acidity,	acetic acid,	grams/liter
Citric acid,	citric acid,	grams/liter
