# ML: Supervised Learning

In this challenge, I trained and evaluated models with imbalanced classes and identified the creditworthiness of borrowers based on lending data. 

First, I used the LogisticRegression algorithm to predict high and low risk loans, and analyzed the results using a confusion matrix and a classification report.

Later, I re-ran the regression and analysis after applying the RandomOverSampler module to evenly balance classes.

## Technologies

[scikit-learn](https://scikit-learn.org/stable/) - For machine learning algorithms.

`from sklearn.linear_model import LogisticRegression`

`from sklearn.metrics import balanced_accuracy_score`

`from sklearn.metrics import confusion_matrix`

[imbalanced-learn](https://imbalanced-learn.org/stable/) - For dealing with imbalanced classes.

`from imblearn.metrics import classification_report_imbalanced`

[pandas](https://pandas.pydata.org/docs/) - For data structuring and analysis.

## Lessons learned

- Defined a supervised learning model.

- Described and applied the model-fit-predict pattern.

- Created, trained, used, and evaluated supervised classification models, such as logistic regression.

- Splited data into training and testing datasets to evaluate whether the model is in any way unbiased.

- Calculated and applied advanced evaluation metrics to determine the performance of a classification model.

- Applied resampling techniques to enhance model performance for imbalanced class.

## Contributors

Aquiba Benarroch, CFA
aquiba.me