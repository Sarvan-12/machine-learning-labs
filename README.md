# Machine Learning Labs

A structured collection of Jupyter Notebooks implementing fundamental Machine Learning algorithms, statistical analyses, and data preprocessing techniques. This repository serves as a hands-on reference for key ML models implemented from scratch and utilizing standard scientific libraries.

---

## 🚀 Featured Course Project

> [!TIP]
> **[k-NN Classification with Adaptive Modifications](https://github.com/Sarvan-12/knn-adaptive-algorithm)**
> An advanced, adaptive implementation of the k-NN classification algorithm. This project optimizes key parameters like $k$ and selection of distance metrics dynamically based on local data density, improving classifier robustness and classification boundaries on complex or noisy datasets.

---

## 📂 Lab Directory & Index

The following table provides an index of all the lab notebooks, the datasets used, and the specific algorithms/methods implemented:

| Lab No. | Notebook File | Problem Statement / Algorithm Implemented |
| :---: | :--- | :--- |
| **01** | [`01_lab_1.ipynb`](labs/01_lab_1.ipynb) | **Data Preprocessing & Outlier Detection:** Analyzing feature distributions and performing outlier detection using the Interquartile Range (IQR) method on the California Housing dataset. |
| **02** | [`02_lab_2.ipynb`](labs/02_lab_2.ipynb) | **Exploratory Data Analysis (EDA):** Visualizing summary statistics, correlation matrix heatmaps, feature histograms, and pairplots for the California Housing dataset. |
| **03** | [`03_lab_3.ipynb`](labs/03_lab_3.ipynb) | **Dimensionality Reduction (PCA & SVD):** Principal Component Analysis and Singular Value Decomposition on the Iris dataset with 3D projection and covariance analysis. |
| **04** | [`04_lab_4.ipynb`](labs/04_lab_4.ipynb) | **Find-S Concept Learning:** Implementing the Find-S concept learning algorithm from scratch to find the most specific hypothesis for a set of training instances. |
| **05** | [`05_lab_5.ipynb`](labs/05_lab_5.ipynb) | **k-Nearest Neighbors (k-NN) Classification:** Implementing and tuning scikit-learn's $k$-NN classifier on a generated dataset, demonstrating the effect of different $k$ values on model accuracy. |
| **06** | [`06_lab_6a.ipynb`](labs/06_lab_6a.ipynb) | **Regression Comparison:** Implementing and comparing Linear Regression, Locally Weighted Regression (LWR) using a Gaussian kernel, and Polynomial Regression. |
| **07** | [`07_lab_7a.ipynb`](labs/07_lab_7a.ipynb) | **Multiple Linear Regression:** Training and evaluating a multiple linear regression model (MSE, RMSE, R² metrics) on the Boston Housing dataset. |
| **08** | [`08_lab_7b.ipynb`](labs/08_lab_7b.ipynb) | **Polynomial Regression:** Evaluation and visualization of polynomial regression (predicting MPG from horsepower) on the Auto MPG dataset. |
| **09** | [`09_lab_8.ipynb`](labs/09_lab_8.ipynb) | **Decision Tree Classification (ID3/CART):** Building, optimizing, and plotting a decision tree classifier with entropy/information gain metrics on the Breast Cancer classification dataset. |
| **10** | [`10_lab_10.ipynb`](labs/10_lab_10.ipynb) | **k-Means Clustering & PCA:** Finding the optimal number of clusters ($k$) using the Elbow Method and Silhouette Analysis on the Breast Cancer dataset (reduced with PCA). |

---

## 🛠️ Setup & Usage

### 1. Running Locally
To run these notebooks on your machine, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Sarvan-12/machine-learning-labs.git
   cd machine-learning-labs
   ```

2. **Set up a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use: venv\Scripts\activate
   ```

3. **Install the required packages:**
   ```bash
   pip install jupyter numpy pandas scikit-learn matplotlib seaborn scipy
   ```

4. **Start the Jupyter notebook server:**
   ```bash
   jupyter notebook
   ```

---

### 2. Running on Google Colab
You can run any notebook directly in your browser without local installation:
1. Go to [Google Colab](https://colab.research.google.com/).
2. Select the **GitHub** tab.
3. Enter your GitHub username (`Sarvan-12`) or repository URL and select `machine-learning-labs`.
4. Open the desired notebook from the `labs/` folder.
5. Upload corresponding datasets from the `datasets/` folder to Colab's file explorer if the notebook requires local data loads.
