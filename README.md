# 🌸 Iris Flower Classification with KNN

This project implements a K-Nearest Neighbors (KNN) classifier on the classic Iris dataset, one of the most famous datasets in machine learning.

## 📊 Project Description

### The goal is to predict the species of Iris flowers (Setosa, Versicolor, Virginica) based on four measured features:

Sepal length

Sepal width

Petal length

Petal width

The KNN algorithm from scikit-learn is used for classification.

### ⚙️ Steps in the Notebook

Load dataset – Import Iris dataset directly from sklearn.datasets.

Exploratory Data Analysis (EDA) – Preview the data, visualize distributions, and inspect the target classes.

Preparation – Split features (X) and target (y), apply train/test split.

Model Training – Train a KNN classifier with different values of k.

Evaluation –

Accuracy score

Confusion matrix

Classification report (Precision, Recall, F1-score)

Hyperparameter Tuning – Find the best k using an error rate plot.

### 📈 Results

The model achieved an accuracy of 100% on the test set.

The confusion matrix shows that all classes were correctly classified.

The error analysis demonstrated that the classifier performs almost perfectly across most k values, with only minor variations.

### 🛠️ Technologies Used

Python 3

Jupyter Notebook

scikit-learn

pandas

matplotlib

seaborn
