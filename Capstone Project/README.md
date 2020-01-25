# Capstone Project 1
This repository contains all the documents with regards to building a machine learning model to predict number of cycle hires. The data was provided by TFL(Transport for London) and is stored in an AWS S3 bucket. The project was executed through multiple Jupyter notebooks. Each notebook provides a detailed walkthrough of the process undertaken to get to the final model.

### Description of files
* Part 1: Data Wrangling - This describes how to download the files from the AWS S3 bucket, how to include additional features from a weather API and how to clean the dataset. 
* Part 2: Data Visualisation - This produces some plots to show the relationship between the features and target variable.
* Part 3 & 4: Feature Engineering & Statistical Modelling - This follows thorugh the final steps reuired to engineer our dataset and explores some hypotheses about the dataset using PYMC3.
* Part 5: Machine Learning - This walks through the different machine learning models (also includes a few boosting methods) used and discusses possible future work based on the results.

### Requirements
I used Python 3.7.4 to run the above files. You will need to install the following packages(either pip or conda) to run the code:
* boto3 
* numpy
* pandas
* matplotlib
* seaborn
* holidays
* requests
* bokeh - only for Part 2 and is not needed to reproduce the model
* pymc3 - only for Part 4 and is not needed to reproduce the model
* theano - only for Part 4 and is not needed to reproduce the model
* sklearn
* xgboost

I have had difficulties with having pymc3 and matplotlib in the same environment and would suggest either installing pymc3 before matplotlib or running Part 4 of the project on a different environment.

