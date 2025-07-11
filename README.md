# YoungDevInterns_Machine_Learning_Task_2
Classify Data with a Decision Tree  Task: Train a decision tree classifier.  Details:  Use scikit-learn to train a decision tree on a dataset like Iris.  Evaluate the model’s performance using accuracy and a confusion matrix

This repository contains the implementation of a Decision Tree Classifier to classify cereals into Low, Medium, and High rating categories based on their nutritional features.
This task is part of the YoungDev AI & ML Internship.
📌 Task Objective
Dataset: preprocessed_cereal.csv

Goal:
Convert the numerical "rating" column into categorical labels and train a classifier to predict these labels using a Decision Tree.

🧠 Key ML Steps
Data Loading & Preprocessing

Converted the rating column into categories using pd.cut()

Dropped the original continuous column

Model Training

Used DecisionTreeClassifier from sklearn

Split data using train_test_split

Evaluation

Evaluated model using accuracy_score

Visualized the performance with a confusion matrix
