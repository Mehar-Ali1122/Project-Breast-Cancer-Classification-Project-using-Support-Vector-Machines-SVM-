## About the Project

This project presents a comprehensive machine learning workflow for **binary breast cancer classification using Support Vector Machines (SVM)**. The objective is to develop and evaluate machine learning models capable of classifying breast tumor observations as **Benign** or **Malignant** based on quantitative diagnostic features.

The project uses the **Breast Cancer Wisconsin dataset**, containing 569 observations and 30 predictive features describing characteristics such as radius, texture, perimeter, area, smoothness, compactness, concavity, symmetry, and fractal dimension. The target variable represents the tumor classification as either Benign or Malignant.

A complete end-to-end machine learning pipeline is implemented, beginning with exploratory data analysis and data-quality assessment, followed by feature preprocessing and standardization. The analysis includes class-distribution examination, statistical summaries, missing-value analysis, correlation analysis, and feature-distribution visualization.

The core focus of the project is a comparative evaluation of different classification approaches. **Logistic Regression**, **Linear SVM**, **RBF Kernel SVM**, and **Polynomial Kernel SVM** are trained and evaluated using multiple performance metrics. For the nonlinear SVM models, **GridSearchCV with 5-fold cross-validation** is used to tune hyperparameters and identify suitable model configurations.

Model performance is assessed using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix
- ROC Curves
- Precision-Recall Curves

The experimental results demonstrate the importance of kernel selection and hyperparameter optimization in SVM-based classification. In the implemented experiment, the **RBF Kernel SVM achieved an accuracy of 97.37%, precision of 100%, recall of 92.86%, F1-score of 96.30%, and ROC-AUC of 99.47%** on the test set. :contentReference[oaicite:2]{index=2}

Overall, this project demonstrates how **Support Vector Machines, feature preprocessing, exploratory data analysis, hyperparameter optimization, and rigorous model evaluation** can be integrated into a reproducible machine learning pipeline for a binary classification problem.
## Key Highlights

- 🧬 **Healthcare-focused machine learning classification**
- 📊 **569 observations with 30 predictive features**
- 🔍 Comprehensive exploratory data analysis
- ⚙️ Feature preprocessing and standardization
- 🤖 Comparison of Logistic Regression and multiple SVM kernels
- 🎯 RBF and Polynomial SVM hyperparameter optimization using GridSearchCV
- 📈 Evaluation using Accuracy, Precision, Recall, F1-score, and ROC-AUC
- 📉 ROC and Precision-Recall curve analysis
- 🔄 Reproducible workflow using a fixed random seed
- 🐍 Implemented entirely in Python using Scikit-learn

> **Note:** This project is developed for academic and machine learning research purposes. The models are not intended to provide clinical diagnosis or replace professional medical assessment.
