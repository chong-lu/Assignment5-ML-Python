# Assignment 5: Machine Learning in Python

This project demonstrates a simple machine learning workflow using the Iris dataset in Python. Multiple classification algorithms are trained. The workflow is implemented and visualized in a Jupyter Notebook.

## Project Structure

```
Assignment5-ML-Python/
├── environment.yml                  # Conda environment definition
├── machine-learning-in-python.ipynb # Main notebook with modeling code
├── iris.csv                         # input data file
└── README.md                        # Project documentation
```

## Goals

* Load and explore the Iris dataset
* Apply a set of linear, nonlinear, and ensemble classification algorithms
* Use stratified k-fold cross-validation for model evaluation
* Compare model performance using accuracy as the metric and visualization

## Models Implemented

* Linear Discriminant Analysis (LDA)
* Classification and Regression Trees (CART)
* K-Nearest Neighbors (kNN)
* Support Vector Machines with Radial Basis Kernel (SVM-RBF)
* Random Forest

## Evaluation Method

* Stratified K-Fold Cross-Validation (k=10)
* Accuracy used as the evaluation metric
* `cross_val_score` from `sklearn.model_selection`

## Python Packages Used

The following packages are used in this project:

* `matplotlib`
* `numpy`
* `scikit-learn`
* `pandas`
* `scipy`

## Getting Started

### Requirements

You can set up the project environment using the provided `environment.yml` file:

```bash
conda env create -f environment.yml
conda activate ml-python
```
### Running the Notebook

1. Clone the repository:

```bash
git clone https://github.com/chong-lu/Assignment5-ML-Python.git
cd Assignment5-ML-Python
```

2. Launch Jupyter Lab:

```bash
jupyter lab
```

3. Run each cell sequentially to reproduce the full analysis.

## License

This repository is intended for educational use only.

## Acknowledgments

- Based on Jason Brownlee on September 26, 2023 in Python Machine Learning

Source: https://machinelearningmastery.com/machine-learning-in-python-step-by-step/
