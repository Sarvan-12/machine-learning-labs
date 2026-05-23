# Machine Learning

A collection of Jupyter Notebooks covering core Machine Learning algorithms and data analysis techniques, from preprocessing and exploratory analysis to supervised and unsupervised learning.

---

## Lab Index

| Lab No. | Notebook | Algorithm / Topic |
| :---: | :--- | :--- |
| 01 | [`01_lab_1.ipynb`](01_lab_1.ipynb) | Data Preprocessing & Outlier Detection using IQR on the California Housing dataset. |
| 02 | [`02_lab_2.ipynb`](02_lab_2.ipynb) | Exploratory Data Analysis — correlation heatmaps, histograms, and pairplots. |
| 03 | [`03_lab_3.ipynb`](03_lab_3.ipynb) | Dimensionality Reduction using PCA and SVD on the Iris dataset. |
| 04 | [`04_lab_4.ipynb`](04_lab_4.ipynb) | Find-S Concept Learning Algorithm — most specific hypothesis from training instances. |
| 05 | [`05_lab_5.ipynb`](05_lab_5.ipynb) | k-Nearest Neighbors (k-NN) Classification — effect of varying k on accuracy. |
| 06 | [`06_lab_6a.ipynb`](06_lab_6a.ipynb) | Regression comparison — Linear, Locally Weighted (Gaussian kernel), and Polynomial. |
| 07 | [`07_lab_7a.ipynb`](07_lab_7a.ipynb) | Multiple Linear Regression on the Boston Housing dataset (MSE, RMSE, R²). |
| 08 | [`08_lab_7b.ipynb`](08_lab_7b.ipynb) | Polynomial Regression — predicting MPG from horsepower on the Auto MPG dataset. |
| 09 | [`09_lab_8.ipynb`](09_lab_8.ipynb) | Decision Tree Classifier (ID3/CART) with entropy criteria on the Breast Cancer dataset. |
| 10 | [`10_lab_10.ipynb`](10_lab_10.ipynb) | k-Means Clustering with Elbow Method and PCA on the Breast Cancer dataset. |

---

## Datasets

All required datasets are available in the [`datasets/`](datasets/) folder. Upload the relevant CSV to your environment before running a notebook.

| Dataset | Used In |
| :--- | :--- |
| `housing_exp1_exp2.csv` | Lab 01, Lab 02 |
| `IRIS_exp3.csv` | Lab 03 |
| `Find_S_training_data_exp4.csv` | Lab 04 |
| `linear_dataset.csv`, `lwr_dataset.csv`, `polynomial_dataset.csv` | Lab 06 |
| `Boston housing dataset.csv` | Lab 07 |
| `Breast cancer.csv` | Lab 09, Lab 10 |

---

## Running on Google Colab

1. Open [Google Colab](https://colab.research.google.com/) and upload the notebook.
2. Upload the corresponding dataset from the `datasets/` folder using the Colab file panel.
3. Run all cells.

---

## Related Project

An advanced implementation of the k-NN classification algorithm with adaptive modifications — optimizing `k` and distance metrics dynamically based on local data density.

[github.com/Sarvan-12/knn-adaptive-algorithm](https://github.com/Sarvan-12/knn-adaptive-algorithm)
