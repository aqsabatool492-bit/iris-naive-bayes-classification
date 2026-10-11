# Iris Flower Classification Using Gaussian Naive Bayes

## 📌 Project Overview

This project explores the Iris flower dataset through Exploratory Data Analysis (EDA) and applies the Gaussian Naive Bayes machine learning algorithm to classify flowers into their respective species based on their physical measurements.

The project demonstrates a basic machine learning workflow, from data exploration and visualization to model training, prediction, and performance evaluation.

## 🎯 Objectives

- Understand the structure and characteristics of the Iris dataset.
- Perform Exploratory Data Analysis (EDA) to identify patterns and relationships.
- Visualize feature distributions and compare measurements across species.
- Build a classification model using Gaussian Naive Bayes.
- Evaluate model performance using standard classification metrics.
- Predict the species of a new Iris flower from its measurements.

## 📊 Dataset Description

The dataset contains measurements of Iris flowers belonging to three species:

- Iris Setosa
- Iris Versicolor
- Iris Virginica

### Features

| Feature | Description |
|---|---|
| Sepal Length | Length of the sepal |
| Sepal Width | Width of the sepal |
| Petal Length | Length of the petal |
| Petal Width | Width of the petal |
| Species | Target class to be predicted |

The four numerical measurements are used as input features, while the species column is the target variable.

## 🔍 Exploratory Data Analysis (EDA)

The notebook explores the dataset using the following techniques:

- Dataset inspection using Pandas.
- Statistical summaries and descriptive statistics.
- Missing-value and duplicate checks.
- Species distribution analysis.
- Histograms to examine feature distributions.
- Box plots to compare measurements across species.
- Scatter plots to explore relationships between features.
- Correlation analysis and a correlation heatmap.
- Grouped statistical summaries by species.

## 🤖 Machine Learning Algorithm

**Gaussian Naive Bayes**

Gaussian Naive Bayes is a supervised classification algorithm based on Bayes' theorem. It assumes that features are conditionally independent given the class and models continuous features using Gaussian distributions.

In this project, the model learns from the flower measurements and predicts the species of flowers in the test dataset.

## ⚙️ Model Workflow

1. Load and inspect the dataset.
2. Separate input features (X) and target labels (y).
3. Split the data into training and testing sets using an 80:20 ratio.
4. Train the Gaussian Naive Bayes classifier.
5. Predict flower species for the test set.
6. Evaluate the predictions using classification metrics.
7. Test the model on a new flower sample.

## 📈 Model Evaluation

The model is evaluated using:

- **Accuracy:** Overall proportion of correct predictions.
- **Precision:** Proportion of predicted instances of a species that are correct.
- **Recall:** Proportion of actual instances of a species correctly identified.
- **F1-score:** Harmonic mean of precision and recall.
- **Confusion Matrix:** Displays correct and incorrect classifications for each species.

Actual evaluation results are available by running the notebook.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📁 Project Structure

```text
Iris-Naive-Bayes/
│
├── iris.csv
├── iris_naive_bayes.ipynb
└── README.md
```

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with the URL of your repository.

### 2. Navigate to the project folder

```bash
cd iris-naive-bayes-classification
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Open Jupyter Notebook

```bash
jupyter notebook
```

Open `iris_naive_bayes.ipynb` and run the cells in order. Keep `iris.csv` in the same folder and ensure the notebook reads the dataset from the correct path.

## 📚 Key Learning Outcomes

- Understanding the EDA process.
- Working with Pandas and data visualization libraries.
- Preparing features and target labels for machine learning.
- Implementing a Gaussian Naive Bayes classifier.
- Understanding train-test splitting and model evaluation.
- Making predictions on new data.

## 👩‍💻 Project Information

**Project:** Iris Flower Classification  
**Domain:** Data Science and Machine Learning  
**Algorithm:** Gaussian Naive Bayes

