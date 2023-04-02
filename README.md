# Disaster tweets detection

The project's goal is to be accurate at detecting tweets that alert of a disaster. An example of such a tweet would be "Forest fire near La Ronge Sask. Canada".
This project was made for the Kaggle competition: [Natural Language Processing with Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started/overview)

## Models created

For this project three models were created:
* Baseline model: A simple model that classifies all the samples with the target that is more frequent in the training set. Validation accuracy: 57.7%.
* Transformer encoder: A one layer transformer-encoder with a classification head, this model has 23.7 million trainable parameters. Validation accuracy: 80.47%.
* Pretrained BERT: This model makes use of a DistilBERT pretrained model with a classifier head. Validation accuracy: 84.11%.

## Usage

Kaggle notebooks were used in this project and the models were trained using a GPU P100.
