To be, or not to be
==============================

Feature Engineering and Data Classification Project

Project Organization
------------

    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── interim        <- Intermediate data that has been transformed.   	"processed_dataset.csv"
    │   └── raw            <- The original, immutable data dump. 		"Shakespeare_data.csv"
    │
    ├── notebooks          <- "To be, or not to be.ipynb"
    │
    ├── reports            <- Google Facet Screenshot			"Google_facet_Proj2.png"

--------

To be, or not to be Shakespeare data classification

This notebook deals with classification of Shakespeare Plays.

Key Steps:

Data Preprocessing : Loading data into data frame, filtering required columns, removing null values Data Transformation: Using Label Encoding (scikit learn) and One Hot Encoding to encode the object data type columns to integer type Training & Testing Data set Classification models (scikit learn): Decision Trees, Logistic Regression,K-nearest Neighbours

Data Source:

https://www.kaggle.com/kingburrito666/shakespeare-plays

References:

http://pbpython.com/categorical-encoding.html http://contrib.scikit-learn.org/categorical-encoding/ https://towardsdatascience.com/solving-a-simple-classification-problem-with-python-fruits-lovers-edition-d20ab6b071d2

Google Facet: To find categorical features /reports/Google_facet_Proj2.png