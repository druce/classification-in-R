# classification-in-R

## Equity Premium Prediction in R using machine learning
* Using [dataset](http://www.hec.unil.ch/agoyal/docs/PredictorData2016.xlsx) from [Prof. Amit Goyal](http://www.hec.unil.ch/agoyal/), attempt to predict quarterly equity outperformance based on fundamental data like interest rates, valuation. 
* This should be viewed as exploratory data analysis and a demo of R regression and classification using caret.
* No predictive value from regression.
* Binary classification predicting whether next quarter's equity premium will be above or below long term average is more successful, with some machine learning classifiers achieving > 60% accuracy out of sample.
* explore.pdf contains some preliminary exploratory data analysis
* predict.pdf contains prediction
* explore.Rmd and predict.Rmd contain the R markdown code to generate the PDfs
