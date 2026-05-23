# Machine Learning Labs

A comprehensive repository containing implementation notebooks and datasets for Machine Learning, Statistical Machine Learning, and Deep Learning / Reinforcement Learning labs.

---

## Repository Structure

The repository is structured as a monorepo containing three main sections:

### 1. [Machine Learning](machine-learning/)
Covers implementation of core Machine Learning algorithms from scratch and using libraries:
* Data Preprocessing & Outlier Detection
* Exploratory Data Analysis (EDA) & Dimensionality Reduction (PCA, SVD)
* Supervised Learning: Decision Trees, k-NN, Linear/Polynomial/Locally Weighted Regression
* Unsupervised Learning: k-Means Clustering
* Concept Learning: Find-S Algorithm

### 2. [Statistical Machine Learning](statistical-ml/)
Focuses on mathematical models, probability distributions, regression modeling, and hypothesis testing:
* Statistical Computations: Percentiles, Interquartile Range, Crosstabs
* Probability & Sampling: Central Limit Theorem
* Hypothesis Testing: One-sample, Two-sample, Welch's, One-tailed, Two-proportion Z-tests
* Advanced Regression: Spline Regression, Poisson Regression, Logistic Regression, Multiple Linear Regression

### 3. [Deep Learning & Reinforcement Learning](deep-learning-rl/)
Covers neural network architectures, sequence modeling, computer vision, and environment simulations:
* Word Representations: Word2Vec embeddings
* Standard Architectures: Multi-Layer Perceptrons (MLPs), Autoencoders, CNN Classifiers
* Sequence & Time Series: Sentiment Analysis and Time Series Forecasting using LSTMs
* Transfer Learning: Image classification with MobileNetV2
* Reinforcement Learning: Custom GridWorld environment simulation

---

## Getting Started

All laboratories are implemented as Jupyter Notebooks (`.ipynb`). You can run them either directly in your browser using Google Colab, or locally on your machine.

### Option 1: Running on Google Colab (Recommended)

1. Open [Google Colab](https://colab.research.google.com/).
2. Select the **GitHub** tab, type `Sarvan-12/machine-learning-labs`, and select this repository.
3. Open the desired notebook file.
4. For notebooks in the `machine-learning/` directory, upload any corresponding datasets from the respective `datasets/` folder using the Colab file explorer.
5. For deep learning notebooks, ensure GPU acceleration is enabled if training models (Edit > Notebook Settings > Hardware accelerator > T4 GPU).

### Option 2: Running Locally

If you prefer to run the notebooks locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Sarvan-12/machine-learning-labs.git
   cd machine-learning-labs
   ```

2. **Set up a virtual environment:**
   ```bash
   python -m venv venv
   # On Windows:
   .\venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. **Install the required packages:**
   ```bash
   pip install jupyter numpy pandas scikit-learn tensorflow torch torchvision nltk gensim matplotlib seaborn scipy
   ```

4. **Start the Jupyter notebook server:**
   ```bash
   jupyter notebook
   ```

---

## Featured / Related Projects

Here are some advanced implementations related to these labs:

* **[KNN Adaptive Algorithm](https://github.com/Sarvan-12/knn-adaptive-algorithm)**: An optimization of the k-NN classification algorithm using local data density to dynamically select k and distance metrics.
* **[Food Calorie Estimator](https://github.com/Sarvan-12/food-calorie-estimator)**: A deep learning web application that classifies food images and estimates their calorie counts.

---

## Connect With Me

If you find this repository helpful or want to discuss AI/ML development, feel free to reach out!

⭐ **Don't forget to star this repository if you found it useful!**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sarvan12/)