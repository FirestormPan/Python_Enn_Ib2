# Data Editing and Reduction with ENN and IB2 (Python)
(Assignment)
This project implements dataset preprocessing and instance reduction techniques using the Edited Nearest Neighbor (ENN) and Instance-Based Learning algorithm IB2. The goal is to reduce noise and redundant instances in datasets before applying machine learning models.

The workflow consists of three main steps:

## 1. Normalization
A program (NormalizeValues) reads a CSV dataset and normalizes all numerical attributes to the [0,1] range. The class attribute is excluded from normalization. The normalized dataset is written to a new CSV file.

## 2. Edited Nearest Neighbor (ENN)
The ENN program applies the Edited Nearest Neighbor data editing algorithm to the normalized dataset. ENN removes instances that are likely to be misclassified by their nearest neighbors, helping reduce noise and improve dataset quality.

## 3. Instance Reduction with IB2
The IB2 program implements the Instance-Based Learning (IB2) reduction algorithm. IB2 incrementally constructs a subset of instances that can represent the training dataset while removing redundant examples.

### Assumptions:
- Input datasets are CSV files.
- All attributes are numerical, except the class label, which is assumed to be the last column.
- Each step outputs a new CSV file with the processed dataset.
- Datasets for Testing

The programs can be tested with common benchmark datasets (included in repo):
- Iris dataset
- Letter Recognition dataset

### Concepts Demonstrated:
- Dataset preprocessing and normalization
- Instance-based learning
- Data editing (ENN)
- Dataset reduction (IB2)
- Nearest neighbor–based algorithms
- CSV data processing in Python
