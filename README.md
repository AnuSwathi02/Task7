# Anu Swathi - Task7
 Support Vector Machines (SVM) - Breast Cancer Classification

This project demonstrates the use of Support Vector Machines (SVM) for binary classification using the Breast Cancer Wisconsin dataset. The objective is to compare linear and non-linear (RBF kernel) SVMs and evaluate their performance using cross-validation.

## 📁 Dataset

- **Source:** Breast Cancer Wisconsin Diagnostic Dataset
- **Target variable:** `diagnosis` (M = Malignant, B = Benign)
- **Features:** 30 numeric features computed from digitized images of a breast mass

## 🧰 Tools and Libraries

- Python
- Scikit-learn
- NumPy
- Matplotlib
- Seaborn
- Pandas

## 🚀 Tasks Performed

1. **Data Preprocessing**
   - Encoding categorical labels
   - Feature scaling using `StandardScaler`

2. **Model Training**
   - Trained SVM with linear kernel
   - Trained SVM with RBF kernel

3. **Visualization**
   - PCA used to project high-dimensional data to 2D
   - Decision boundaries visualized using `matplotlib`

4. **Hyperparameter Tuning**
   - Used `GridSearchCV` to find optimal `C` and `gamma` for the RBF SVM

5. **Model Evaluation**
   - Classification report and confusion matrix
   - Cross-validation scores and average accuracy

## 📊 Results

- RBF SVM achieved higher accuracy after hyperparameter tuning.
- PCA visualization provided a clear view of the decision boundary in 2D.

