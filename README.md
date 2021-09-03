# Predicting-Mortality-
This project aims at determining the most important set of existing health pre-conditions that can determine mortality, based upon NHEFS study data.
In particular, we train a series of tree-based regression models to predict survival time from clinical
predictors in the NHEFS data set. We find that the model with the best performance on the test
set is gradient boosted. Subsequently, we perform feature selection on our optimal model and train
further models on data sets restricted to the most impactful predictors in an attempt to balance
predictive power with number of features that a physician must measure.
This kind of study is of course particularly relevant in the age of COVID-19, where we know how disproportionately impactful the virus can be on an individual depending on 
existing preconditions.
