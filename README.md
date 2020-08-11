# Stellar Classification

A classification task to predict star type based on temperature, luminosity, radius and absolute magnitude.

## Objective
In the Jupyter Notebook included in this page, we will using a Star Dataset to predict the type of a star based on its properties.

The dataset can be found here:
* https://www.kaggle.com/deepu1109/star-dataset

The notebook can be found [here](https://github.com/tatianabarbone/stellar-classification/blob/master/stellar_classification.ipynb), or you can open it Google Colaboratory here: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tatianabarbone/stellar-classification/blob/master/stellar_classification.ipynb)

## Steps
In this notebook, we’ll perform:
- Exploratory data analysis
- Machine learning with sklearn
- Accuracy, Precision, Recall, and F1 calculations


## Results

After comparing the accuracy scores of various models including Logistic Regression, KNN, Decision Tree, LDA, SVM and Gaussian Naive Bayes, the Decision Tree model was the most accurate, but KNN and LDA were not far behind. **In fact, most of the algorithms were very accurate due to the small dataset size.**

The decision tree produced had a max depth of 5 nodes, and was able to classify each star with 99% accuracy (test set) as a Brown Dwarf, Red Dwarf, White Dwarf, Main Sequence, Supergiant, or Hypergiant.

![image](https://github.com/tatianabarbone/stellar-classification/blob/master/decision_tree.png)

With the decision tree model, only one error was made, incorrectly classifying a Main Sequence star as a Red Dwarf.
