# classification-in-R

## Equity Premium Prediction in R using machine learning
* Using [dataset](http://www.hec.unil.ch/agoyal/docs/PredictorData2016.xlsx) from [Prof. Amit Goyal](http://www.hec.unil.ch/agoyal/), attempt to predict quarterly equity outperformance based on fundamental data like interest rates, valuation. 
* This should be viewed as exploratory data analysis and a demo of R regression and classification using [caret](http://caret.r-forge.r-project.org/), which offers a consistent interface to many [inference models](http://topepo.github.io/caret/available-models.html).
* No predictive value from regression.
* Binary classification predicting whether next quarter's equity premium will be above or below long term average is more successful, with some machine learning classifiers achieving > 60% accuracy out of sample.
* explore.pdf contains preliminary exploratory data analysis.
* predict.pdf contains predictions using regression and classification.
* explore.Rmd and predict.Rmd contain the R markdown code to generate the PDfs
