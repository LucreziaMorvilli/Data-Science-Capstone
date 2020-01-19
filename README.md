# Data Science Capstone Project
Capstone project for Data Scientist Nanodegree (Udacity). 

Follow this [link](https://medium.com/@lumo17/create-a-customer-segmentation-report-for-arvato-financial-services-cb9f4cdf4ad1?source=friends_link&sk=6eeef28b32726d50ffc8042a9488b556) to read a post about this project on Medium.

## Description
The project has two major steps: the customer segmentation report and the supervised learning model.

**1. Customer Segmentation Report**

At the beginning of the project I use unsupervised learning methods to analyze attributes of established customers and the general population in order to create customer segments.

**2. Supervised Learning Model**

I had access to a third dataset with attributes from targets of a mail order campaign. With the previous analysis, I built a machine learning model that predicts whether or not each individual will respond to the campaign.

## Installation
- Python 3.*
- Python libraries: NumPy, Pandas, Scikit-learn, matplotlib, seaborn

## Files
Used for this project but not available here as property of Arvato Bertelsmann Group:
- Udacity_AZDIAS_052018.csv: Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns).
- Udacity_CUSTOMERS_052018.csv: Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).
- Udacity_MAILOUT_052018_TRAIN.csv: Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).
- Udacity_MAILOUT_052018_TEST.csv: Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).
- AZDIAS_Feature_Summary.csv: description of the data features from a similar project done in term 1
- DIAS Information Levels - Attributes 2017.xlsx: description of features
- DIAS Attributes - Values 2017.xlsx: for each feature, list of values corresponding to "missing" or "unknown" entry

Included here:
- This README.md file
- Arvato Project Workbook.html: HTML version of the project
- Arvato Project Workbook.ipynb: Python project in jupyter notebook
- workspace_utils.py: includes a function to keep the session active (for the clustering for loop that tests different numbers of centroids)

### Acknowledgements
Udacity



