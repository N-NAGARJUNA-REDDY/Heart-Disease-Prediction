# Heart Disease Prediction using Ensemble Learning

This project predicts heart disease based on clinical features using ensemble machine learning models including MLP, Random Forest, XGBoost, LightGBM, and Stacking Classifier.

## 🧬 Dataset

- Source: Internal dataset (`heart.csv`)
- Target Variable: `target` (1 = disease, 0 = no disease)
- One column `country` was dropped due to irrelevance.

## 🔍 Feature Selection

The project uses:
- **KL Divergence**
- **Fisher Index**

Top features are selected using the average score of both techniques.

## 📚 Models Used

- MLPClassifier
- RandomForestClassifier
- XGBClassifier
- LGBMClassifier
- Final Estimator: LogisticRegression (inside Stacking Classifier)

## 🎯 Metrics Reported

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1 Score

## Cite
N. N. Reddy, L. Nipun, M. U. Baba, N. Rishindra, and T. Shilpa, "Optimizing heart disease prediction through ensemble and hybrid machine learning techniques," Int. J. Electr. Comput. Eng. (IJECE), vol. 14, no. 5, p. 5744, Oct. 2024. doi: 10.11591/ijece.v14i5.pp5744-5754.

## 🛠 Requirements

```bash
pip install pandas numpy scikit-learn xgboost lightgbm
