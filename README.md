# Access Classification System

This project implements a machine learning-based access control system that classifies document access requests as either 'grant' or 'deny/flag' based on various user and document attributes.

## Features

- Random Forest Classifier for access control decisions
- Features used for classification:
  - User Role
  - Department
  - Action Type
  - Resource Sensitivity
  - Past Violations

## Dataset

The system uses synthetic access data with the following attributes:

- User information (role, department)
- Resource information (sensitivity level)
- Access request details (action type)
- Historical data (past violations)

## Requirements

- Python 3.8+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter

## Installation

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

## Usage

1. Open the Jupyter notebook:

```bash
jupyter notebook access_classifier.ipynb
```

2. Run all cells in the notebook to:
   - Load and preprocess the data
   - Train the classifier
   - Evaluate model performance
   - Make predictions on new access requests

## Model Performance

The model provides:

- Classification metrics (precision, recall, F1-score)
- Confusion matrix visualization
- Feature importance analysis
- Confidence scores for predictions
