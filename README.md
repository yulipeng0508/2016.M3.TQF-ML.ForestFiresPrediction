# 2016.M3.TQF-ML.ForestFiresPrediction
## Project Goal:
> The project is to predict whether there will be forest fires using several factors such as month of the year, day of the week, FFMC (Fine Fuel Moisture Code) index, DMC (Duff Moisture Code) index, DC (Drought Code) index, ISI (Initial Spread) index, temperature, relative humidity, wind speed, outside rain and so on.

## Data Sources:
> http://archive.ics.uci.edu/ml/datasets/Forest+Fires
  
## Methology:
> Mainly use Logistic Regression, SVM, Decision Tree. If possible, I will try random forest and other methods and compare these results.

## Expected Results:
> Visualize the results. Calculate and compare accuracies of different methods. Then choose the best one.

## Test Results:
> First, I have tried logistic regression and SVM methods. \
Comparing the results, I find some methods (svm.poly and svm.rbf) do have a much higher training accuracies with n=11 than n=2 while the test accuracies of all methods do not have an obvious difference between n=11 and n=2, generally around 0.5 to 0.6.


> Then, I have tried some classifier methods.\
Comparing the results, Random Forest has the highest test accuracy（0.635） while KNN method will have the best test results if the number of the training samples increases.
