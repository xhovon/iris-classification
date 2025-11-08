<<<<<<< HEAD
# iris-classification
=======
# 01-Iris-Classification

This is my first project in my 20-day AI/ML portfolio. The goal is to perform a complete Exploratory Data Analysis (EDA) on the classic Iris dataset and then build a machine learning model to classify the flower species.

## 📊 Project Goal

The main objective was to analyze the Iris dataset to understand the relationships between features (sepal length, petal width, etc.) and the target (species). Based on these insights, I built and evaluated two common classification models: Logistic Regression and K-Nearest Neighbors (KNN).

## 🚀 Key Findings (from EDA)

The notebook `iris_analysis.ipynb` contains the full analysis, but here are the highlights:

1.  **Perfectly Clean Data:** The dataset contains 150 samples with no missing values.
2.  **Perfectly Balanced Classes:** There are exactly 50 samples for each of the three species: `setosa`, `versicolor`, and `virginica`.
3.  **The "Golden" Insight:** The `setosa` species is **linearly separable** from the other two. You can see this in the pair plot—a simple line can be drawn to separate it.
4.  **Strongest Predictors:** `petal_length` and `petal_width` are *highly* correlated with the species (0.95+), making them excellent features for prediction. `sepal_length` and `sepal_width` are much less effective.

## 🤖 Model Performance

I split the data into an 80% training set and a 20% test set (30 samples) to get an unbiased evaluation.

Both models achieved **100% accuracy** on the unseen test data.

* **Logistic Regression:** 100% Accuracy
* **K-Nearest Neighbors (K=5):** 100% Accuracy

This perfect score is rare in the real world and confirms our EDA finding that this dataset is very clean and the classes are easily separable.

## 🏃 How to Run This Project

1.  Clone this repository: `git clone https://github.com/YourUsername/iris-classification.git`
2.  Navigate to the folder: `cd iris-classification`
3.  Install the required libraries (if you don't have Anaconda):
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn jupyter
    ```
4.  Open the notebook:
    ```bash
    jupyter notebook iris_analysis.ipynb
    ```
>>>>>>> c49d4df (feat: EDA and ML Models)
