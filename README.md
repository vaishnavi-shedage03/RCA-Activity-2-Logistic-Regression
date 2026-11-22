# Activity 2: Binary Classification Using Logistic Regression

## Subject
Regression and Classification Algorithms

## Objective
To build a Logistic Regression model for a binary classification problem, understand predicted probabilities and decision thresholds, and evaluate the model using classification evaluation metrics.

## Dataset Details
- **Dataset Name:** Breast Cancer Wisconsin Dataset
- **Dataset Source:** Scikit-learn
- **Source Link:** https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html
- **Total Records:** 569
- **Input Features:** 30 numerical features
- **Target Variable:** Binary classification
- **Class 0:** Benign
- **Class 1:** Malignant

## Algorithm Used
- Logistic Regression

## Libraries Used
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Implementation
The following tasks were performed:
1. Dataset loading and inspection
2. Missing value and duplicate checking
3. Class distribution visualisation
4. Data preprocessing
5. Stratified train-test split (80:20)
6. Feature scaling using StandardScaler
7. Sigmoid function visualisation
8. Logistic Regression model training
9. Intercept and coefficient analysis
10. Probability and class prediction
11. Decision threshold comparison (0.3, 0.5 and 0.7)
12. Confusion matrix analysis
13. Accuracy, Precision, Recall, Specificity and F1-score calculation
14. Classification report
15. Majority-class baseline comparison
16. ROC curve and ROC-AUC evaluation
17. Decision behaviour visualisation
18. Training and testing performance comparison
19. New example prediction

## Evaluation Metrics
- Accuracy
- Precision
- Recall (Sensitivity)
- Specificity
- F1-score
- ROC-AUC

## Files Included
- `breast_cancer_dataset.csv` – Dataset used for the experiment.
- `Activity_2_Logistic_Regression.ipynb` – Jupyter Notebook containing the complete implementation and outputs.

## Faculty Reference
**Faculty GitHub Profile:** [Complexiota](https://github.com/complexiota)

## Conclusion
Logistic Regression was successfully implemented using the Breast Cancer Wisconsin dataset. The model was evaluated using classification metrics, a confusion matrix, ROC curve and different decision thresholds. The experiment helped understand binary classification and model performance.

**Note:** This project is for educational purposes only and should not be used for medical diagnosis.
