# -Fraud-Detection-Model

```markdown
# Fraud Detection Project

## Overview

This project focuses on implementing a proactive fraud detection system using machine learning techniques. The dataset used in this project contains information about financial transactions, and the goal is to detect fraudulent transactions.

## Project Structure

```
project-root/
│
├── data/
│   ├── Fraud.csv
│   └── Data_Dictionary.txt
│
├── notebooks/
│   └── Untitled5.ipynb
│
├── src/
│  
│   └── Untitled5.py
│
└── README.md
```

- **data**: Contains the dataset files.
- **notebooks**: Jupyter notebook(s) for data exploration, analysis, and modeling.
- **src**: Source code for utility functions (`Untitled5.py`) and the fraud detection model (`Untitled5.py`).

## Dataset Description

The dataset used in this project contains the following columns:

- `step`: Unit of time in the real world (1 step is 1 hour).
- `type`: Transaction type (CASH-IN, CASH-OUT, DEBIT, PAYMENT, TRANSFER).
- `amount`: Amount of the transaction in local currency.
- `nameOrig`: Customer who started the transaction.
- `oldbalanceOrg`: Initial balance before the transaction.
- `newbalanceOrig`: New balance after the transaction.
- `nameDest`: Customer who is the recipient of the transaction.
- `oldbalanceDest`: Initial balance recipient before the transaction.
- `newbalanceDest`: New balance recipient after the transaction.
- `isFraud`: Binary indicator of fraudulent transactions (1 for fraud, 0 for non-fraud).
- `isFlaggedFraud`: Binary indicator for flagged illegal attempts.

## Project Execution

1. **Data Cleaning**: Handle missing values, outliers, and multicollinearity.
2. **Describe Fraud Detection Model**: Implement a Random Forest Classifier for fraud detection.
3. **Variable Selection**: Identify relevant variables based on feature importance.
4. **Model Performance**: Evaluate the model using confusion matrix, accuracy, and classification report.
5. **Key Predictors of Fraudulent Customer**: Identify important features contributing to fraud detection.
6. **Interpretation**: Validate whether the identified factors make sense in the context of fraud detection.
7. **Prevention Strategies during Infrastructure Update**: Provide recommendations for preventing fraud during system updates.
8. **Evaluation of Implemented Actions**: Discuss how to determine if implemented actions are effective.

## How to Run

1. Install required dependencies: `pip install -r requirements.txt`
2. Run the Jupyter notebook in the `notebooks` directory: `jupyter notebook fraud_detection_notebook.ipynb`
3. Explore the notebook for detailed analysis and results.

## Future Enhancements

- Implement real-time fraud detection capabilities.
- Explore and experiment with different machine learning models.
- Enhance feature engineering for improved model performance.

## Contributors

- Vishal Shukla

