# Personal Identifiable Information (PII) Data Detection ML Model

This project is a part of the ADS-599 Capstone in the Applied Data Science Program at the University of San Diego.

--**Project Status: [Complete]**

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

## Purpose
Data continues to evolve, as do the security practices needed to safeguard them. The education sector is currently facing a growing responsibility of maintaining the confidentiality of student and faculty personal information while fostering an environment instrumental to progressing research and science. Organizations such as The Learning Agency Lab rely on real student submissions such as essays to develop learning-based tools and programs to benefit both students and teachers. However, educational datasets are difficult to acquire due to concerns regarding the exposure of PII. Datasets are normally reviewed manually to remove PII, which is costly and time-consuming. By implementing a solution through data science and machine learning, a more reliable method to identify and remove PII could significantly improve data privacy and allow public educational data sets to be more readily available.

## Data Science Objectives:
This project aims to train and evaluate several robust machine-learning models to detect and efficiently remove PII from large datasets. A final model will be selected based on the expectation that it can maintain high recall and precision scores, minimizing false positives or negatives. Additionally, the model should have a low runtime to be more scalable in future applications. A successful model would significantly alleviate the education sector's challenge in maintaining data privacy. This would enable researchers to use high-quality public datasets and enhance student privacy. Should the proposed model fail to meet the expectations of this project, further hyperparameter tuning, refinement, and exploration would be necessary to address PII detection.


## Methods Used
- **Logistic Regression**
- **Random Forest**
- **K-Nearest Neighbors**
- **Extreme Gradient Boosting**
- **Natural Language Processing**
- **Predictive Modeling**

## Modeling:
The project wanted to select machine learning algorithms that would be able to perform text processing and classification tasks with minimal processing time. A baseline model was created to identify baseline predictors and metrics that would be monitored. This was then followed by more complex NLP models that would undergo hyperparameter tuning. The original datasets included a train and test data set, but for the purpose of training models, the train dataset was further partitioned. A train and validation set were created, with an 80/20 split from the preprocessed train dataset.

## References
- Anwar, M. (2021). Supporting privacy, trust, and personalization in online learning. International Journal of Artificial Intelligence in Education, 31, 769–783. https://doi.org/10.1007/s40593-020-00216-0 
- Dash, B., Sharma, P., & Ali, A. (2022, July). Federated learning for privacy-preserving: A review of PII data analysis in fintech. International Journal of Software Engineering & Applications, 13(4), 1–13. https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4323967 
- Donadel, A. (2023, September 28). This data breach has compromised nearly 900 institutions. University Business. https://universitybusiness.com/in-just-3-months-this-data-breach-has-compromised-nearly-900-institutions/ 
- Ersinesen, A. (2023). Discovery, classification, and protection of PII: Current state, problems,  solution proposals. Journal of Privacy and Security, 15(2), 127–142. https://medium.com/@ersinesen/discovery-classification-and-protection-of-pii-current-state-problems-and-solution-proposals-3627e16f2d8b 
- Holmes, L., Crossley, S., Baffour, P., King, J., Burleigh, L., Demkin, M., Holbrook, R., Reade, W., & Howard, A. (2024). The Learning Agency Lab - PII data detection. Kaggle. https://kaggle.com/competitions/pii-detection-removal-from-educational-data 
- Kulkarni, P., & Cauvery, N. K. (2021). Personally Identifiable Information (PII) Detection in the Unstructured Large Text Corpus using Natural Language Processing and Unsupervised Learning Technique. International Journal of Advanced Computer Science & Applications (Online), 12(9). https://doi.org/10.14569/ijacsa.2021.0120957
- Nowicki, J., & Young, C. (2020, October 15). Data security: Recent K-12 data breaches show that students are vulnerable to harm. U.S. Government Accountability Office. https://www.gao.gov/products/gao-20-644
- Poornima, K., & Cauvery, N. K. (2021). Personally identifiable information (PII) detection in the unstructured large text corpus using natural language processing and unsupervised learning technique. International Journal of Advanced Computer Science and Applications, (12)9, 508–517. https://thesai.org/Downloads/Volume12No9/Paper_57-Personally_Identifiable_Information_PII_Detection.pdf 
- Prakash, P. (2020, March 18). Extend named entity recogniser (NER) to label new entities with spaCy. Towards Data Science. https://towardsdatascience.com/extend-named-entity-recogniser-ner-to-label-new-entities-with-spacy-339ee5979044 
- Ratinov, L., & Roth, D. (2009). Design challenges and misconceptions in named entity recognition. In S. Stevenson & X. Carreras (Eds.), Proceedings of the thirteenth conference on computational Natural language learning ([CoNLL-2009];  pp. 147–155). https://aclanthology.org/W09-1119 
- Roy, S., & Mitra, M. (2018). Identification and processing of PII data, applying deep learning models with Improved accuracy and efficiency. 
- Saluja, B., Kumar, G. S., Sedoc, J., & Callison-Burch, C. (2019). Anonymization of sensitive information in medical health records. IberLEF@SEPLN, 2421, 647–653. http://ceur-ws.org/Vol-2421/MEDDOCAN_paper_2.pdf 
- Ulven, J. B., & Wangen, G. (2021). A systematic review of cybersecurity risks in higher education. Future Internet, 13(2), 39. https://doi.org/10.3390/fi13020039 
