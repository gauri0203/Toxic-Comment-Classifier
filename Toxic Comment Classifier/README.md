# Toxic-Comment-Classifier
This project applies classification models for detecting toxic comments on social media.

## Modeling:
Three main Machine Learning classification models are used:
* Logistic Regression
* Multinomial Naive Bayes
* Support Vector Machine (SVM)

According to the results, Naive Bayes classifier with TfidfVectorizer came with the best f1 score and recall: 0,85 and 0.88, respectively.
Because of this reason, it was used as the base model of the web application. 

## Full results: 
|       Models       | precision   | recall   | f1 score |
| -----------------  | ------------| ---------|----------|
|Multinomial NB      |    0.82     |   0.88   |   0.85   |
|Logistic Regression |    0.82     |   0.80   |   0.81   |
|SVM                 |    0.82     |   0.83   |   0.83   |

