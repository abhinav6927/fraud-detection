
# Credit Card Fraud Detection

This project aims to detect fraudulent credit card transactions using machine learning techniques. 
It uses various algorithms including Logistic Regression, Isolation Forest, and Local Outlier Factor (LOF) to identify fraudulent transactions from a highly imbalanced dataset.

## Dataset
The dataset consists of 284,807 credit card transactions, with only 492 labeled as fraudulent. Download Link = https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/code

## Models Used
1. **Logistic Regression**: Achieved a high accuracy (99.9%) but struggled to detect fraud cases with a recall of 56%.
2. **Isolation Forest**: Performed slightly better in identifying fraud cases with a recall of 59%.
3. **Local Outlier Factor (LOF)**: Achieved a recall of 15%, making it less effective for this problem.

## Key Insights
- Logistic Regression models may not be the best choice for highly imbalanced datasets where the priority is detecting rare events like fraud.
- Anomaly detection methods such as Isolation Forest and LOF require careful tuning to improve recall and precision.
- Future improvements could include using ensemble methods, cost-sensitive learning, or techniques like SMOTE to handle the imbalance effectively.

## Setup Instructions

### Requirements

You can install the required dependencies by running:

```bash
pip install -r requirements.txt
```

### Running the Notebook

Once the dependencies are installed, simply open the `advanced_fraud_detection.ipynb` notebook in Jupyter and run all the cells.

## Future Enhancements
- Implement ensemble techniques for improved fraud detection.
- Apply cost-sensitive learning or SMOTE to balance the dataset and improve detection rates for rare fraud cases.

## License
This project is licensed under the MIT License.
