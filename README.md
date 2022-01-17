# Supervised Learning on loans

## Credit Risk Analysis

In this project I created a logistical regression and random forests classifier model to predict the credit risk of loans from the first quarter of the next year.

By looking at the data briefly, I would hypothesize that the Logistical Regression model would under perform working with this data due to the output variable being continuous and not a discrete categorical outcome like a random forest classifier. The random forest classifier would perform better in this instance because we are targeting two variable out comes, 'high_risk' and 'low_risk'.

## Models with no Scaling

Logistical Regression and Random Forest Classifier models were produced by fitting training data to the models. To see how well the models did with the data, the models were then scored and printed. 

## Analysis

From the printed scores the LR model underperformed when compared to the RFC model. The printed score for LR is '0.5168013611229264', while the RFC printed score is '0.635899617184177'. The higher score of a .64 indicates that the RFC is a better model for predicting the credit risk of loans for the first quarter of the next year.

## Models with Scaling

Further analysis was conducted by revising the data pre-processing stage. I decided to scale the data and see how this effects my models.

## Analysis

The outcomes were printed and it is clear that scaling the data allows the LR model, printed score '0.767333049766057' to outperform the RFC model, printed score '0.6316461080391322'.

## In Summary

Prior to conducting this analysis I hypothesized that scaling would improve both models but the RFC would still perform the best. However, after scaling the data and conducting the analysis it is clear the LR model is superior for predicting the credit risk status of a loan. I believe the nature of the scaled LR model performing better lies within the preprocess step of scaling the data to similar ranges so the model can predict more accurately


