# Comparing Classifiers

## Summary
This exercise includes the evaluation of 4 machine learning models to be able to predict whether the customer's of a Portugues Bank will subscribe to a specific investment vehicle in the form of an savings account.  The machine learning models that were evaluated are as follows:
- Logistic Regression
- K-Nearest Neighbor (KNN)
- Decision Tree Classifier
- Support Vector Machine (SVC)

The data used for this exercise can be found in the following file: [data/bank-additional-full.csv](data/bank-additional-full.csv).

Jupiter notebook link: [prompt_lll.ipynb](/prompt_III.ipynb)

Analysis:

Per the results stated in the section labeled "Final Comparison of Results" it was determined that a model derived using the decision tree classifier along with the following feature set produced the best results.  This is with regards to determining if a potential or current customer would subscribe to a savings account that was being advertised during the mentioned campains.

The list of features that were either used directly or transformed from the original catagorical information into numeric information are as follows:
- age
- duration
- pdays
- cons.price.idx
- cons.conf.idx
- euribor3m
- nr.employed

More details on the features and how they were used can be found in the attached python notebook.