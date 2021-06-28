# NLP-Projects

This is a comparision study for three NLP models(Logistic Regression, RNN, BERT).

The primary study material is AWS Machine Learning University @Youtube. The original data from Amazon Customer Reviews Dataset (https://s3.amazonaws.com/amazon-reviews-pds/readme.html).

## Logistic Regression
Key Steps:
1. Clean texts and exclude stop words through stopwords in NLTK library
2. Use TD-IDF to vectorize to vectors of len 750.
3. Build and train a double layer Logistic Regression Model
4. Predict with test data

## RNN
Key Steps:
1. use GloVe for Word2vec pretraining
2. build and train 2-layers RNN model
3. Predict with test data

## BERT (Bidirectional Encoder Representations from Transformers)
Key Steps:
1. Pretraining and get tokenizer for BERT
2. Fine-tuning BERT



