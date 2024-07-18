Title: Video Game Sales Prediction using ML

Description of the Proposed System:
The project aims to analyze video game sales data to predict global sales based on various regional sales figures. The dataset includes sales data from North America (NA_Sales), Europe (EU_Sales), Japan (JP_Sales), and other regions (Other_Sales). The goal is to build a model that can accurately forecast global sales (Global_Sales) using these regional sales data points.	Models:

1. Linear Regression:
Linear Regression is used for predicting a continuous outcome variable (global sales) based on one or more predictor variables (regional sales). The model assumes a linear relationship between these variables.

2. Random Forest Regression:
Random Forest Regressor builds multiple decision trees and merges them to get a more accurate and stable prediction. Each tree is trained on a random subset of the data, and the final prediction is made by averaging the predictions of all trees.

3. K-Nearest Neighbors (KNN) Regression:

KNN Regression is a non-parametric, instance-based learning algorithm. It predicts the outcome for a test instance based on the 'k' closest training examples in the feature space.
Training Phase: KNN does not explicitly learn a model. Instead, it stores all the training data.
Prediction Phase: The algorithm finds the 'k' nearest neighbors and predicts the value as the average of the values of these neighbors.


•	Data Collection and Preprocessing:
The data set includes essential features required for predicting sales. The features it includes:

1.	Year
2.	NA_Sales
3.	EU_Sales
4.	JP_Sales
5.	Other_Sales
6.	Global_Sales

