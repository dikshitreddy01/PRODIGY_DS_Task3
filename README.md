# Prodigy InfoTech Data Science Internship — Task 03

## Task
Build a Decision Tree Classifier to predict whether a customer will subscribe to a product/service.

## Dataset
UCI Bank Marketing dataset:
https://archive.ics.uci.edu/dataset/222/bank+marketing

## What this project does
- Loads and explores the bank marketing dataset.
- Checks the target distribution and missing values.
- Encodes categorical features with one-hot encoding.
- Splits the data into training and test sets.
- Trains a Decision Tree Classifier.
- Evaluates accuracy and a classification report.
- Displays a confusion matrix.
- Visualizes the decision tree.

`duration` is excluded because it is known only after the call and is not appropriate for a pre-call prediction.

## Tools
Python, Pandas, Matplotlib, Scikit-learn, Jupyter/VS Code

## Install
```bash
python -m pip install pandas matplotlib scikit-learn jupyter
```

## Run
Open `PRODIGY_DS_03.ipynb` in VS Code, select a Python/Jupyter kernel, and run cells from top to bottom.

## Conclusion
The project demonstrates a Decision Tree approach for binary customer-response prediction and evaluates the model using multiple metrics.
