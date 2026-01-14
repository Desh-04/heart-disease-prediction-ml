# heart-disease-prediction-ml
Machine learning project to predict heart disease using clinical data and classification algorithms.

### Machine Learning Approach

The objective of this project is to predict the presence of heart disease
using clinical and medical attributes through supervised machine learning
classification techniques.

---

### Data Preprocessing
- Handled data loading and basic cleaning
- Selected relevant medical features for prediction
- Split the dataset into training and testing sets

---

### Models Trained
Multiple classification models were trained and compared to identify the
best-performing algorithm:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier
- K-Nearest Neighbors (KNN)
- Naive Bayes
- XGBoost Classifier

---

### Model Evaluation
The models were evaluated using the following metrics:
- Accuracy
- Confusion Matrix
- Classification Report

---

### Model Performance Summary

| Model | Accuracy |
|------|----------|
| **XGBoost** | **0.903** |
| Random Forest | 0.891 |
| Gradient Boosting | 0.881 |
| Decision Tree | 0.847 |
| KNN | 0.812 |
| Logistic Regression | 0.741 |
| Naive Bayes | 0.684 |

---

### Final Model Selection
Among all the trained models, **XGBoost Classifier** achieved the highest
accuracy (approximately 90.3%) and demonstrated superior predictive
performance compared to other classifiers.

---

### Conclusion
This project highlights the importance of comparing multiple machine
learning algorithms before finalizing a model. Ensemble-based methods
such as XGBoost and Random Forest showed stronger performance, reinforcing
their effectiveness in healthcare analytics and predictive modeling.

