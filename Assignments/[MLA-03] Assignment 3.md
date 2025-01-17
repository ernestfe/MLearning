# [MLA-03] Assignment 3

## Introduction

This assignment is a continuation of the analysis performed in the example MLE-04, focused on the selection of the contacts for a direct marketing campaign of **term deposits**. Here, we take a different approach to the problem of **class imbalance**. With a 11.7% **conversion rate**, the data from the bank show a moderate class imbalance, which was addressed in the example with a **scoring** approach. In this assignment, we use a **resampling** approach, training our predictive models in a modified data set in which the class imbalance has been artificially corrected.

Though there is a Python package, called `imblearn`, devoted to **imbalanced learning**, the suggestion for the assignment is to extract the random samples directly from the Pandas data frames, with the method `.sample()`, which is supersimple. 

## Questions

Q1. Perform a **random split** of the data set, taking one half for training and the other half for testing. You will use this partition for all the questions of this assignment. Suppose that we use our predictive model as suggested in question Q5 of example MLE-04, but calling 20% of the clients. How would you validate the model for that application, based on your train-test split?

Q2. **Undersample** the training subset, by randomly dropping as many negative units as needed to match the positive units, so that you end up with a pefectly balanced training data set. Leave the test data set as it is, without correcting there the class imbalance. Train a **logistic regression model** on the undersampled training data set and evaluate it on the test data set, based on a confusion matrix. 

Q3. **Oversample** the training subset, by randomly adding as many duplicates of the positive units as needed to match the negative units, so that you end up with a pefectly balanced training data set. Leave the test data set as it is, without correcting there the class imbalance. Train a logistic regression model on oversampled training data set and evaluate it on the test data set, based on a confusion matrix.

## Submission

1. Submit, through Blackboard, a readable and printable report responding these questions and explaining what you have done, including Python input and output. This can be a Word document, a PDF document or a Jupyter notebook (.ipynb).

2. Put your name on top of the document.

## Deadline

February 25 (Sunday), 24:00.
