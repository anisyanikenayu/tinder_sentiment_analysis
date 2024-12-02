# Indonesian Sentiment Analysis from Tinder App

Tinder is one of dating application used by the global user. This project is aimed to perform sentiment analysis whether positive, negative, or neutral responds from spesifically Indonesian people.

## About

This project related to machine learning course. Here we are going to cleaning, preprocessing, and building various models from different algorithms. We would like to know more the quality of the model by evaluation of data testing accuracy.

## Constributor
- Anisya Niken Ayu Ningtyas

## Data

The raw datasets contains 10k data from individually scrapped from Google Play API. The datasets has dominant negative labels that is followed up by balancing each of label equally using Resampling (Oversampling).

Data loaded and preprocessed:
- Removing punctuation
- Converting to lowercase
- Tokenizing
- Removing stopwords
- Applying stemming

## Models
- RandomForestClassifier
- Current Neural Network (CNN)
- Long Short Term Memory (LSTM)

## Word Embedding Models
- TF-IDF
- FastText

## Training

Data is splitted into training dan testing data on presentation whether 80:20 or 70:20. The neural network model trained by Adam optimizer and Sparse Categorical Crossentropy/Categorical Crossentropy.

## Evaluation
The best performance for now on is achieved by RandomForestClassifier by using TF-IDF, reach the test accuracy approximatelly 0.94.

## Recommendation & Future Steps (for better models)
- Reanalyze and optimize preprocessing text: is the data really clean and labeling unbiased, is normalization/standardization appropriate and is the algorithm appropriate?
- Use more advanced text preprocessing techniques: feature extraction using pre-trained such as word2vec, glove, fastext, BERT; labeling using BERT
- Model optimization: hyperparameter tuning to find optimal parameters in the training process.
- Perform inference or testing with output (categorical class)
