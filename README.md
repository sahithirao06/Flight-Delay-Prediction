# Flight-Delay-Prediction
Flight delays can disrupt travel plans and impact the aviation industry's efficiency. This project focuses on developing a machine learning model to predict flight delays based on historical flight data and relevant features. By accurately anticipating delays, travelers and stakeholders can make informed decisions and take appropriate actions. This repository contains the code and resources for the Flight Delay Prediction project.

I have collected the dataset from kaggle. 

source link: https://drive.google.com/drive/folders/1-U17SOSSX2crwlWUP1z98Ng42nYuJJOD?usp=sharing

## Explorations

### Exploratory Data Analysis
I have collected the data, cleaned it and performed univariate and Bivariate analysis i.e. analysis of features with target variable to answer some interesting questions on the dataset through visualization. Analyzed the dataset to identify patterns, correlations, and insights that impact flight delays.

Data Cleaning : Removal of missing values, Label Encoding, Normalization, Splitting data to train and test datasets.

**Target to be predicted is if a flight is delayed or not based on the weather. Features from weather and flight data are considered for prediction**

Split the flight delay dataset into training and testing subsets using an 80-20 ratio. The training subset, consisting of training samples, will be used to train and validate the predictive models. The testing subset, with testing samples, will remain unseen during training and will be utilized to assess the models' performance on new data.

 
##### Models used:
Logistic Regression is incredibly easy to implement and very efficient to train. 

(Logistic Regression implementation is best instead of Linear Regression because the target variable in the dataset is of type categorical, not continuous. So, my dataset is not suitable for linear regression.)
-> After using logistic regression, I have implemented through decision tree classifier, which did not meet the accuracy of logistic regression.But definitely, both models have shown that they can be very successful in solving classification problems.

**Decision Tree Classifier**: A decision tree  learnt from historical flight data to make decisions about whether a flight is likely to be delayed or not based on different attributes like departure time, weather conditions, etc.
It's an interpretable algorithm helped to identify important factors contributing to flight delays.

**Support vector Classifier**: SVM analyzed features of flights and determine whether they are likely to be delayed or not and also handled high-dimensional data well and are effective in cases where classes are not linearly separable.

**Random Forest Classifier**: Aggregate the predictions of individual decision trees to provide a more robust and accurate prediction of flight delays and handled complex relationships between features and predicting delays more accurately.

**Neural Networks**: Neural network learnt complex relationships between flight attributes and delays, potentially leading to highly accurate predictions.
However, neural networks might require more data and computational resources for training.

### Links to Notebooks
-[Initial Exploration](initial_exploration.ipynb)

-[linear_regression](linear_regression.ipynb)

-[Classification](classification.ipynb)

-[Clustering & NN](clustering.ipynb)

Visualizations can be found in Initial Exploration.

### Results and Analysis
-[Results and Analysis](results.md)

