Machine Learning Lab
Build a classfier to predict the label field (substitute or not substitute) of the product substitute dataset.

Final Project Problem: Product Substitute Prediction
Problem Definition: Given a pair of products, (A, B), we say that B is a "substitute" for A if a customer would buy B in place of A -- say, if A were out of stock.

The goal of this project is to predict a substitute relationship between pairs of products. Complete the tasks in this notebook and submit your notebook via Colab

Read the datasets (Given)
Data Processing (Implement)
Exploratory Data Analysis
Select features to build the model (Suggested)
Train - Validation - Test Datasets
Data Processing with Pipeline
Train (and Tune) a Classifier on the Training Dataset (Implement)
Make Predictions on the Test Dataset (Implement)
Datasets and Files:

training.csv: Training data with product pair features and corresponding labels:
ID: ID of the record
label: Tells whether the key and candidate products are substitutes (1) or not (0).
key_asin ...: Key product ASIN features
cand_asin ...: Candidate product ASIN features
public_test_features.csv: Test data with product pairs features without labels:
ID: ID of the record
key_asin ...: Key product ASIN features
cand_asin ...: Candidate product ASIN features
metadata-dataset.xlsx: Provides detailed information about all key_ and cand_ columns in the training and test sets. Try to select some useful features to include in the model, as not all of them are suitable. |Region Id|MarketPlace Id|ASIN|Binding Code|binding_description|brand_code|case_pack_quantity|, ...
