# Practical Machine Learning Course Project

This project applies machine learning techniques to classify human activity using accelerometer data collected from six individuals performing barbell lifts. The goal is to predict the `classe` variable, representing how well the exercise was performed.

## Files included
- `prediction_project.Rmd`: R Markdown file containing full analysis, data cleaning, model training, and predictions
- `prediction_project.html`: Compiled HTML report for viewing
- Data source: [UCI HAR Dataset](http://groupware.les.inf.puc-rio.br/har)

## Model used
Random forest classifier with 5-fold cross-validation using the `caret` package. Achieved >99% accuracy on the validation set.

## Author
Submitted as part of the Johns Hopkins Data Science Specialization on Coursera.
