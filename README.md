# Regression with an Abalone Dataset

# Overview
Welcome to the 2024 Kaggle Playground Series! We plan to continue in the spirit of previous playgrounds, providing interesting an approachable datasets for our community to practice their machine learning skills, and anticipate a competition each month.

Your goal:
The goal of this competition is to predict the age of abalone from various physical measurements.

# Evaluation
The evaluation metric for this competition is Root Mean Squared Logarithmic Error. The RMSLE is calculated as:
√−−−−−−−−−−−−−−−−−−−−−−−−−−
1n∑i=1n(log(1+y^i)−log(1+yi))2

where:
- n is the total number of observations in the test set
- y^i is the predicted value of the target for instance (i)
- yi is the actual value of the target for instance (i)
- log is the natural logarithm
