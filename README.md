# Codealpha
# Iris Flower Classification — CodeAlpha Internship

This is my submission for **Task 1: Iris Flower Classification** as part of the CodeAlpha Data Science Internship.

# Objective

Classify Iris flower species (`Iris-setosa`, `Iris-versicolor`, `Iris-virginica`) using their physical features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

# Tools & Libraries Used
- Python
- Pandas
- Scikit-learn (RandomForestClassifier)
- Jupyter/VSCode

# Dataset

I used the [Kaggle Iris Dataset](https://www.kaggle.com/datasets/saurabh00007/iriscsv).  
This dataset includes 150 samples of iris flowers.

# How It Works

1. Load the dataset using `pandas`
2. Clean the data and drop the `Id` column
3. Split into features (X) and target (y)
4. Train using `RandomForestClassifier`
5. Predict and evaluate using test data

# Output

```text
Accuracy: 1.00

Classificat
Classification Report:
                  precision    recall  f1-score   support

    Iris-setosa       1.00      1.00      1.00        10
Iris-versicolor       1.00      1.00      1.00         9
 Iris-virginica       1.00      1.00      1.00        11

       accuracy                           1.00        30
      macro avg       1.00      1.00      1.00        30
   weighted avg       1.00      1.00      1.00        30
