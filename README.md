# SMS Spam Classifier

## Overview:
The SMS Spam Classifier is a machine learning project designed to automatically detect and classify spam messages in SMS (Short Message Service) text data. Leveraging the Multinomial Naive Bayes algorithm, this classifier analyzes the content of SMS messages to determine whether they are spam or legitimate (ham).

## Dataset:
The classifier is trained and tested on a labeled dataset of SMS messages, consisting of examples of both spam and ham messages. The dataset is sourced from kaggle [UCI MACHINE LEARNING - SMS Spam Collection Dataset] and is pre-processed to remove noise, tokenize text, and engineer relevant features.

## Key Features:
- Preprocesses SMS text data to extract relevant features and transform them into a format suitable for machine learning.
- Provides a user-friendly interface for users to input SMS messages and receive instant predictions on whether they are spam or ham.
- Evaluates the performance of the classifier using various metrics such as accuracy, precision, recall, and F1 score.
- Allows for easy deployment and integration into existing applications or workflows.

## Usage:
1. Prepare your SMS text data in a suitable format.
2. Use the provided scripts or Jupyter notebooks to preprocess the data and train the classifier.
3. Provide a user interface for users to interactively classify SMS messages as spam or ham.

## Installation:
To run the SMS Classifier with Streamlit locally, follow these steps:

1. Clone the repository:
```
git clone https://github.com/himanshu-banodha/sms-spam-classifier.git
cd sms-spam-classifier
```
2. Install the required dependencies:
```
pip install -r requirements.txt
```
3. Run the Streamlit app:
```
streamlit run app.py
```

## Thank You !
