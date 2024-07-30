# Isolation Forest and Extended Isolation Forest

## Project Overview
This project explores the Isolation Forest and Extended Isolation Forest algorithms, which are used for anomaly detection. The notebooks provided implement both methods and compare their performance on various datasets.

## Isolation Forest
### Description
The Isolation Forest algorithm isolates observations by randomly selecting a feature and then randomly selecting a split value between the maximum and minimum values of the selected feature. This method is particularly effective for anomaly detection because anomalies are few and different.

### Implementation
The `Isolation Forest.ipynb` notebook contains the implementation of the Isolation Forest algorithm. It demonstrates how to:
- Load and preprocess the dataset.
- Fit the Isolation Forest model.
- Predict anomalies.

## Extended Isolation Forest
### Description
The Extended Isolation Forest (EIF) improves on the Isolation Forest by using hyperplanes instead of axis-parallel splits, making it more effective in high-dimensional spaces and with skewed data distributions.

### Implementation
The `Extended Isolation Forest.ipynb` notebook contains the implementation of the Extended Isolation Forest algorithm. It demonstrates how to:
- Load and preprocess the dataset.
- Fit the EIF model.
- Predict anomalies.

## Comparative Analysis
### Key Differences
- **Splitting Method**: Isolation Forest uses axis-parallel splits, while Extended Isolation Forest uses hyperplanes.
- **Dimensionality Handling**: EIF handles high-dimensional data better than the standard Isolation Forest.
- **Bias Reduction**: EIF reduces bias in detecting complex anomalies.

### Performance Comparison
The `Comparing Isolation Forest and Extended Isolation Forest.ipynb` notebook compares the performance of both algorithms on the same datasets, highlighting their strengths and weaknesses.

## Dependencies
- Python 3.x
- scikit-learn
- numpy
- pandas
- matplotlib

## Usage
### Running the Notebooks
1. Clone the repository.
   ```bash
   git clone https://github.com/yourusername/isolation-forest-comparison.git
   cd isolation-forest-comparison

1. Download the CSV file.
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
