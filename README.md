# Student Pass/Fail Prediction using Logistic Regression

A beginner-friendly machine learning project that uses **Logistic Regression** to classify whether a student is likely to pass or fail based on study hours.

## Project overview

The notebook demonstrates a binary classification workflow:

- `0` = Fail
- `1` = Pass

The example dataset is created directly inside the notebook. It contains 10 study-hour values, from 1 to 10, with corresponding pass/fail labels.

## What the notebook does

1. Imports NumPy, Matplotlib, and scikit-learn.
2. Creates the study-hours dataset and binary labels.
3. Splits the data into training and testing sets using `train_test_split`.
4. Trains a `LogisticRegression` classifier.
5. Evaluates the model using accuracy, a confusion matrix, and a classification report.
6. Accepts a study-hours value from the user.
7. Predicts Pass or Fail and displays the estimated pass probability.
8. Plots the training and testing points, the logistic regression probability curve, the user's prediction, and the 50% decision boundary.

## Project structure

```text
Logistic_Regression/
├── Logistic_Regression.ipynb
├── README.md
└── requirements.txt
```

## Requirements

- Python 3
- NumPy
- Matplotlib
- scikit-learn
- Jupyter Notebook or JupyterLab to open and run the `.ipynb` file

## Installation

Open a terminal in the project folder and install the dependencies:

```bash
pip install -r requirements.txt
```

## Run the notebook

Start Jupyter:

```bash
jupyter notebook
```

Then open `Logistic_Regression.ipynb` and run the cells in order. When prompted, enter a number of study hours.

## Important limitations

This is a small educational example with only 10 manually specified observations. Its accuracy and predictions are not reliable estimates of real student performance. Study hours alone are not enough to determine whether a student will pass. A practical model would require a larger, representative dataset, additional relevant features, and evaluation on genuinely unseen data.

## License

Add a license file if you want to specify how others may use, modify, or distribute this project.
