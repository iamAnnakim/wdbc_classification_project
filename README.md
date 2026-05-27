# Breast Cancer Classification Project

## 1. Project Title
Breast Cancer Classification using Machine Learning Classifiers

---

## 2. Project Purpose
The purpose of this project is to compare multiple machine learning classifiers for breast cancer diagnosis prediction.  
The program trains several classifiers, evaluates their performance, finds the best classifier based on accuracy, and visualizes the results using a confusion matrix and scatter plot.

---

## 3. Dataset Used
- Wisconsin Diagnostic Breast Cancer (WDBC) Dataset
- Features are computed from digitized images of breast mass cell nuclei.
- Classification labels:
  - Malignant
  - Benign

Dataset source:
https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html

---

## 4. How to Install Requirements

Install required Python libraries:

```bash
pip install numpy matplotlib scikit-learn
```

---

## 5. How to Run the Code

Run the Python file:

```bash
python main.py
```

Make sure:
- Python is installed
- Required libraries are installed
- The dataset loading code exists in the program

---

## 6. Output Files

The program generates:

- `wdbc_classification_matrix.png`
  - Confusion matrix image of the best classifier

The program also displays:
- Accuracy results for all classifiers
- Best classifier information
- Scatter plot visualization

---

## 7. Best Classifier Result

Example:

| Classifier | Accuracy |
|---|---|
| SVM | 0.9737 |
| Decision Tree | 0.9211 |
| KNN | 0.9561 |
| Random Forest | 0.9649 |

Best Classifier:
- **SVM**
- Accuracy: **0.9737**

(Note: results may vary depending on train/test split.)
