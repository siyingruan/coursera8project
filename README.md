# Coursera8project
Coursera Data Science Practical Machine Learning Project

## Brief

This is an anlysis using machine learning in R to classify the movement recorded by accelerometers on the belt, forearm, arm, and dumbell of 6 participants. It is an effort to quantify how well people exercise.

The analysis will divide the training data into training and validation. Since it is a classification project, the analysis will fit 2 models (random forest and boosted tree) and stack them to get the better model after comparing the accuracy from the validation dataset. 

Lastly, the analysis uses the best model to predict the class of the 20 observations in the test dataset. 

The data used in the anlysis is from 
Here is the training data for this project:
<https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv>.

Here is the test data:
<https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv>

For more details see <http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har>.  
As a result, the combine predictors model has lower accuracy than the random forest model, where the boosted tree model has the lowest accuracy. This analysis uses the random forest model to predict the test dataset.

## Here is the Link to see the HTML version:

<http://htmlpreview.github.io/?https://github.com/siyingruan/coursera8project/blob/master/preview-125438176e4.html>