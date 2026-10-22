# Unsupervised Wine Clustering

## Project Overview

This project compares three unsupervised machine learning approaches: K-Means, Hierarchical Clustering, and Gaussian Mixture Models (GMM).

The analysis uses the UCI Wine Recognition dataset, which contains 178 observations and 13 chemical features. The objective is to discover patterns in the data without using known class labels during clustering.

## Methods

- Exploratory Data Analysis (EDA)
- Feature standardization
- Principal Component Analysis (PCA)
- K-Means clustering
- Hierarchical clustering with Ward linkage
- Gaussian Mixture Models using Expectation-Maximization
- Elbow method and silhouette analysis
- External validation using Adjusted Rand Index (ARI)

## Results

| Algorithm | Silhouette Score | Adjusted Rand Index |
|---|---:|---:|
| K-Means | 0.285 | 0.897 |
| Hierarchical (Ward) | 0.277 | 0.790 |
| Gaussian Mixture Model | 0.284 | 0.880 |

K-Means achieved the highest Adjusted Rand Index, indicating the strongest agreement with the known wine cultivars in this experiment. All three methods produced similar silhouette scores, suggesting moderate internal cluster separation.

## Technologies

Python, Jupyter Notebook, NumPy, pandas, Matplotlib, Seaborn, SciPy, and scikit-learn.

## Dataset

UCI Wine Recognition Dataset, available through `sklearn.datasets.load_wine`.

## How to Run

1. Install Python and Jupyter Notebook.
2. Install the required packages:

   `pip install numpy pandas matplotlib seaborn scipy scikit-learn notebook`

3. Open `Project4_Unsupervised_Pattern_Grace_Afful.ipynb` in Jupyter Notebook.
4. Run the analysis cells in order.

## Author

Grace Afful

MSc Data Science, University of Ghana.
