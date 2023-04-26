# Stress detection
This program aims to classify texts as stressed or not using nltk and sklearn.

## Required Libraries
- pandas
- numpy
- sklearn
- nltk
- re
- wordcloud
- unidecode

## Dataset
The dataset used in this analysis was taken from Kaggle, an online data science platform that offers public and private datasets, as well as tools for data analysis and modeling. The specific dataset used in this project can be found at https://www.kaggle.com/datasets/kreeshrajani/human-stress-prediction.

## Data pre-processing
The data was loaded using the pandas library and some pre-processing steps were done, such as removing special characters, converting to lowercase, removing stopwords.

## Modeling
The dataset was divided into training and test sets. The Naive Bayes algorithm was used to train the model and performance was evaluated using metrics such as accuracy, precision, recall and F1-score. In addition, a confusion matrix was created to better understand the results.

## Conclusion
The Naive Bayes model performed well in classifying texts as stressed or not. Accuracy was greater than 80%, indicating good generalization ability of the model. Importantly, early detection of high levels of stress can help prevent stress-related health problems.
