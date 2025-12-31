# Support Vector Machine Experiments and SMO Implementation

This repository contains experimental implementations and visual analyses of **Support Vector Classifiers**

## Contents

The repository includes two main Jupyter notebooks

- `SVM_Experiments.ipynb`  
  Experiments using scikit-learn SVC:
  - Understaning of Soft-margin SVM Effect of regularization parameter C.
  - Kernel trick demonstration on circular dataset (linear vs. RBF kernel)

- `SVM_Optimization-SMO.ipynb`  
  From-scratch implementation of Sequential Minimal Optimization (SMO) using only NumPy:
  - Training on noisy "moons" dataset (N=2000, RBF kernel)
  - Visualization of decision boundary, support vectors, convergence plots, and confusion matrix
  - Achieved 98.8% accuracy
  - 
## Experimental Setup

- Language: Python  
- Libraries: NumPy, scikit-learn, Matplotlib, Plotly  
- Datasets: Synthetic datasets generated programmatically (circles, moons, Gaussian clusters with outliers)

## Purpose

The goal of this project is to:
- Understand the impact of **regularization** in soft-margin SVMs
- Illustrate how the **kernel trick** enables non-linear decision boundaries
- Gain insight into the **optimization mechanics** of SVM training through a custom SMO implementation

## Usage
Open the `.ipynb` files in Jupyter Notebook or JupyterLab to reproduce the experiments and figures.
