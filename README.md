# Big Data: Wine Quality Analysis

This project performs a comparative performance analysis of three machine learning models: **k-Nearest Neighbors (k-NN)**, **Support Vector Machine (SVM)**, and **Linear Discriminant Analysis (LDA)**.

## Model Performance Summary
Based on the analysis of the `winequality-white.csv` dataset, the results were as follows:

| Metric    | k-NN Model | SVM Model | LDA Model |
|-----------|------------|-----------|-----------|
| Accuracy  | 0.6136     | 0.5653    | 0.5306    |
| Precision | 0.6157     | 0.5502    | 0.5102    |
| Recall    | 0.6136     | 0.5653    | 0.5306    |
| F1-Score  | 0.6140     | 0.5293    | 0.5070    |

### Key Findings
- **Best Performer:** The **k-NN model** (with $k=1$) achieved the highest values across all evaluation metrics.
- **Efficiency:** While k-NN is accurate, it is more computationally costly for larger datasets. **LDA** is the fastest and least time-consuming, though it had the lowest accuracy in this specific test.
- **SVM:** Performed efficiently for compound relations using the 'rbf' kernel but was more time-consuming than LDA.
