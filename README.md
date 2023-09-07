## Codsoft internship projects

This repo lists the projects I worked on while doing the internship for Codsoft.

The projects are:
- Customer Churn Prediction
- Movie Genre Classification
- SMS Spam Detection

### Customer Churn Prediction
The Dataset used: https://www.kaggle.com/datasets/shantanudhakadd/bank-customer-churn-prediction

In this project, using the powerful Random Forest Classifier, we leveraged
historical data like usage behavior and demographics of customers to predict
customer churn.
Initially, the model achieved an impressive 0.87 accuracy. However, when
addressing class imbalance via random under-sampling, accuracy dipped to 0.76,
highlighting the balance challenge. In contrast, random over-sampling boosted
accuracy to a remarkable 0.94!
The feature analysis identified Age as the top predictor, followed by Balance,
Estimated Salary, and Credit Score, in that order. These insights underscore
their pivotal roles in predicting customer churn.
In summary, the analysis of customer churn prediction yielded valuable insights.
The choice between under-sampling and over-sampling depends on the balance-
accuracy trade-off, with these key features playing crucial roles in customer
retention analysis.

### Movie Genre Classification
The Dataset used: https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb

In this project, I compared three popular classifiers – SGD, Multinomial NB,
and Logistic Regression – to classify movies into 27 different genres based
on the movie synopsis.
The results show that Logistic Regression outperforms the other models for
this task. With an accuracy of 0.60, precision at 0.58, recall of 0.60, and
a solid F1-score of 0.56, it consistently showcases balanced performance across
various metrics.
This means the Logistic Regression model effectively handles the complexities
of the data, making it the optimal choice for this multi-class classification
task.

### SMS Spam Detection
The Dataset used: https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

In this project, I put the spotlight on two trusty classifiers – SGD and
Multinomial NB – to tackle the task of identifying spam messages with precision.
The testing and evaluation reveal the following verdict: both the SGD Classifier
and Multinomial NB models delivered exceptional performance! With identical high
scores of 0.96 for accuracy, precision, recall, and F1-score, it's safe to say
that these models are equally well-equipped for the task.
In summary, the SGD Classifier and Multinomial NB models stand shoulder to
shoulder, showcasing excellent classification capabilities and proving their
mettle in SMS spam detection.


These are projects I have worked on for the project-based Machine Learning Internship by Codsoft.
