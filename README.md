# Team-6-Wisper-of-Flavor
Code, data and readme file for 540 project. 

Dependencies:

- Python 3.6 or higher
- TensorFlow 2.x
- PyTorch
- Transformers library
- scikit-learn
- tqdm

Install dependencies using pip install name. Replace "name" with the actual name of the package in dependencies list above.

## Order of Running codes
Please run codes in folders Word2Vec_TFIDF_traditionalML_RNN, BERT, EDA_cluster_time_series one by one. The raw datasets and intermediate datasets needed to run the code are in included in each file, no need to change anything in the code.

## Word2Vec_TFIDF_traditionalML_RNN
This folder contains code for using TF-IDF and Word2Vec to deal with text data. The subsequent steps involve applying traditional machine learning models ( Decision Tree, Naive Bayes, Linear SGD Classifier, Logistic Regression, Random Forest, and SVC) and applying RNN (Recurrent Netural Network) and evaluating models' performance.

## Multilabel classification using BERT
This folder contains code for training a text multilabel classification model using BERT (Bidirectional Encoder Representations from Transformers). The model is designed to classify Yelp reviews into five categories: 'food_quality', 'environment', 'service', 'convenience', 'cost_effectiveness'.

This folder contains code for reading a labeled raw data Excel file ('labeled_raw_data.xlsx') and 1 million test data ('test_data_text.csv'). The primary purpose is to load the data into a Pandas DataFrame for further processing or analysis.

## EDA_cluster_time_series
This folder used the result predicted from BERT. We combined the numeric predictors and text predictors to conduct k-means clustering, and then plot the stack bar chart of the time series trend for five labels we've defined before.

dataset:
- df_labeled_test.csv: the whole 1000000 data with predicted labels using BERT(comes from file BERT). 
- labeled_review_id.xlsx: manually labeled 1979 records of reviews. It is our sample for training and testing.
- yelp_academic_dataset_business.json: raw data downloaded from yelp official website.
- yelp_academic_dataset_review.json: raw data downloaded from yelp official website.



