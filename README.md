# Personal Identifiable Information (PII) Data Detection ML Model

This project is a part of the ADS-599 Capstone in the Applied Data Science Program at the University of San Diego.

--**Project Status: [Active]**

## Project Description

This project explored the development and evaluation of several machine learning algorithms designed to perform text classification tasks. These models targeted the detection of personal identifiable information (PII) within academic documents written by students. The objective of this project was to create a machine learning model that would accurately and precisely classify words considered PII while being efficient. Several algorithms were used such as Logistic Regression, Random Forest, Extreme-Gradient Boosting (XGBoost), K-Nearest Neighbors (K-NN), and Presidio. These models were all trained and tested using text data that was pre-processed using tokenization and feature engineering in addition to hyperparameter tuning methods such as RandomizedSearch and GridSearch. Ultimately, this study found that the Random Forest models performed the best in having a high accuracy with minimal false positives. This study was able to provide a demonstration on the usefulness of machine learning to enhance data privacy.

## Installation

1. Clone the repository:

To use this project, first clone the repo on your device using the command below:

```bash
git init
```

```bash
git clone https://github.com/ebadakhter/ADS-599-Capstone-Project.git
```

## Contributors

1. [Ebad Akhter](https://github.com/ebadakhter)
2. [Jacqueline Vo](https://github.com/jvo024)
3. [Jiaqi He](https://github.com/Kayhe93)

## Requirements

To replicate this project, the following technology will be needed:
- [Python](https://www.python.org/) Version 3.9+
- [Anaconda](https://www.anaconda.com/) Version 2024.02-1

## Project Datasets
- [Kaggle - The Learning Agency Lab PII Data Detection](https://www.kaggle.com/competitions/pii-detection-removal-from-educational-data/data)
  - train.json
  - test.json

Data was presented in JSON format which includes a document identifier, the full text of the essay, a list of tokens, information about whitespace, and token annotations.


## Methods Used
- **Logistic Regression**
- **Random Forest**
- **K-Nearest Neighbors**
- **Extreme Gradient Boosting**
- **Natural Language Processing**
- **Predictive Modeling**
