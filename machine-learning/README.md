# Machine Learning Labs

A structured collection of Jupyter Notebooks implementing fundamental Machine Learning algorithms, statistical analyses, and data preprocessing techniques. This repository serves as a hands-on reference for key ML models implemented from scratch and using standard scientific libraries.

---

## Lab Directory

| Lab No. | Notebook File | Problem Statement / Algorithm Implemented |
| :---: | :--- | :--- |
| 01 | [`01_lab_1.ipynb`](labs/01_lab_1.ipynb) | **Data Preprocessing & Outlier Detection:** Analyzing feature distributions and detecting outliers using the Interquartile Range (IQR) method on the California Housing dataset. |
| 02 | [`02_lab_2.ipynb`](labs/02_lab_2.ipynb) | **Exploratory Data Analysis (EDA):** Visualizing summary statistics, correlation matrix heatmaps, feature histograms, and pairplots for the California Housing dataset. |
| 03 | [`03_lab_3.ipynb`](labs/03_lab_3.ipynb) | **Dimensionality Reduction (PCA & SVD):** Principal Component Analysis and Singular Value Decomposition on the Iris dataset with 3D projection and covariance analysis. |
| 04 | [`04_lab_4.ipynb`](labs/04_lab_4.ipynb) | **Find-S Concept Learning:** Implementing the Find-S concept learning algorithm from scratch to find the most specific hypothesis for a set of training instances. |
| 05 | [`05_lab_5.ipynb`](labs/05_lab_5.ipynb) | **k-Nearest Neighbors (k-NN) Classification:** Implementing and tuning scikit-learn's k-NN classifier on a generated dataset, demonstrating the effect of different k values on model accuracy. |
| 06 | [`06_lab_6a.ipynb`](labs/06_lab_6a.ipynb) | **Regression Comparison:** Implementing and comparing Linear Regression, Locally Weighted Regression (LWR) using a Gaussian kernel, and Polynomial Regression. |
| 07 | [`07_lab_7a.ipynb`](labs/07_lab_7a.ipynb) | **Multiple Linear Regression:** Training and evaluating a multiple linear regression model (MSE, RMSE, R² metrics) on the Boston Housing dataset. |
| 08 | [`08_lab_7b.ipynb`](labs/08_lab_7b.ipynb) | **Polynomial Regression:** Evaluation and visualization of polynomial regression (predicting MPG from horsepower) on the Auto MPG dataset. |
| 09 | [`09_lab_8.ipynb`](labs/09_lab_8.ipynb) | **Decision Tree Classification (ID3/CART):** Building and evaluating a decision tree classifier with entropy and information gain criteria on the Breast Cancer dataset. |
| 10 | [`10_lab_10.ipynb`](labs/10_lab_10.ipynb) | **k-Means Clustering & PCA:** Finding the optimal number of clusters using the Elbow Method and Silhouette Analysis on the Breast Cancer dataset reduced with PCA. |

---

## Setup & Usage

### Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/Sarvan-12/machine-learning-labs.git
   cd machine-learning-labs
   ```

2. Install the required packages:
   ```bash
   pip install jupyter numpy pandas scikit-learn matplotlib seaborn scipy
   ```

3. Start the Jupyter notebook server:
   ```bash
   jupyter notebook
   ```

### Running on Google Colab

1. Go to [Google Colab](https://colab.research.google.com/).
2. Select the **GitHub** tab and enter `Sarvan-12/machine-learning-labs`.
3. Open the desired notebook from the `labs/` folder.
4. Upload the corresponding dataset from the `datasets/` folder if the notebook requires local data.

---

## Related Project

An advanced implementation of the k-NN classification algorithm with adaptive modifications — optimizing `k` and distance metrics dynamically based on local data density.

[github.com/Sarvan-12/knn-adaptive-algorithm](https://github.com/Sarvan-12/knn-adaptive-algorithm)
