# Heart Disease Prediction using Machine Learning

An end-to-end machine learning pipeline built to predict the likelihood of heart disease using classification algorithms

Dataset Information
* **Dataset Name:** Heart Disease Prediction Dataset 2026
* **Source:** Kaggle (Published by Mohan Krishna Thalla)
* **Description:** A binary classification dataset containing patient demographics, lifestyle indicators, clinical history, and physiological markers (`0` = No Heart Disease, `1` = Heart Disease).
* **Size:** 100,000 records across 25 features.

 Models Evaluated & Results
| Model Name | Accuracy | Precision | Recall | F1 Score |
| :--- | :--- | :--- | :--- | :--- |
| **Logistic Regression** | **76.88%** | 76.84% | 76.88% | **76.83%** |
| **Random Forest** | 75.77% | 75.74% | 75.77% | 75.69% |
| **KNN** | 72.31% | 72.25% | 72.31% | 72.21% |
| **Decision Tree** | 66.67% | 66.70% | 66.67% | 66.68% |

Conclusion & Recommendation
**Logistic Regression** outperformed the other models, achieving the highest accuracy (**76.88%**) and F1 Score (**76.83%**). It generalized better on the test split without overfitting and provides high clinical transparency through interpretable feature coefficients.
