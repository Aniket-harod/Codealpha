# Iris Flower Classification — CodeAlpha Internship

This is my submission for **Task 1: Iris Flower Classification** as part of the CodeAlpha Data Science Internship.


# Objective

Build a machine learning model to classify Iris flower species (`Iris-setosa`, `Iris-versicolor`, `Iris-virginica`) using their physical features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

# Tools & Libraries Used

- Python
- Pandas
- Scikit-learn (`RandomForestClassifier`)
- VSCode / Jupyter Notebook

---

# Dataset Source

- **Name:** `Iris.csv`
- **Source:** [Kaggle – Iris Dataset](https://www.kaggle.com/datasets/saurabh00007/iriscsv)
- **Usage:** The dataset was manually downloaded from Kaggle and loaded using a local path.
- **Samples:** 150
- **Target Classes:** 3 (`Iris-setosa`, `Iris-versicolor`, `Iris-virginica`)

---

# How It Works

1. Load the dataset using `pandas`
2. Clean the data and drop the unnecessary `Id` column
3. Split the dataset into:
   - **Features (X):** sepal/petal measurements
   - **Target (y):** species
4. Split data into training (80%) and testing (20%)
5. Train the model using `RandomForestClassifier`
6. Predict on the test set
7. Evaluate using `accuracy_score` and `classification_report`

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
