# NLP_Exercise
# SMS Spam Classifier

This repository contains code for building a SMS spam classifier using Naive Bayes algorithm. The classifier is trained on a dataset of SMS messages labeled as spam or non-spam. The goal of the classifier is to accurately predict whether a given message is spam or not.

## Dataset
The dataset used for training and evaluation is available in the `sms_spam_data` directory. It contains a CSV file named `SMSSpamCollection.csv`, which includes two columns: `labels` and `messages`. The `labels` column indicates whether a message is spam or not, and the `messages` column contains the text of the messages.

## Prerequisites
To run the code in this repository, you need to have the following dependencies installed:
- Python 3.x
- pandas
- scikit-learn
- nltk

You can install the required packages by running the following command:
```
pip install pandas scikit-learn nltk
```

## Usage
1. Clone this repository to your local machine:
```
git clone https://github.com/<your-username>/sms-spam-classifier.git
```

2. Change into the cloned directory:
```
cd sms-spam-classifier
```

3. Run the `spam_classifier.py` script:
```
python spam_classifier.py
```

4. The script will train the Naive Bayes classifier on the SMS spam dataset and display the evaluation results.

## License
This project is licensed under the [MIT License](LICENSE).

Feel free to use and modify the code according to your needs.

## Acknowledgments
- The SMS spam dataset used in this project is sourced from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection).

Please note that this is a simplified README file, and you may need to provide additional information or details specific to your project.
