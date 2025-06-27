# Logistic_Regression
 Task 4: Classification with Logistic Regression

Objective
Build a binary classification model using logistic regression to predict breast cancer (malignant or benign).



 Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib

 
 Dataset
Breast Cancer Wisconsin Dataset 
- Loaded directly using `sklearn.datasets.load_breast_cancer()`  
- Contains 569 samples with 30 numerical features and a target column (0 = malignant, 1 = benign)

---

 Steps

1. Load Dataset
- Used `load_breast_cancer()` from `sklearn.datasets`
- Converted to a Pandas DataFrame for easy analysis

2. Data Preprocessing
- Split data into features (`X`) and target (`y`)
- Performed train-test split (80% train, 20% test)
- Standardized features using `StandardScaler`

3. Model Building
- Trained a `LogisticRegression()` model from `sklearn.linear_model`

4. Evaluation
- Evaluated using:
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-score)
  - ROC-AUC Score
  - ROC Curve Plot



Results
- High Accuracy and ROC-AUC Score
- ROC curve plotted to visualize model performance

---

 What I Learned
- How logistic regression works for binary classification
- Importance of feature scaling
- Interpretation of ROC curves and metrics like precision/recall
- How sigmoid function maps outputs to probabilities



