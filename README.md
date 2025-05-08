# Regression and Classification Analysis with Scikit-learn

This project implements two core machine learning tasks—regression and classification—using Scikit-learn on real-world datasets.

## 📁 Project Structure

- `Stopping.csv` – Dataset for regression task (speed vs stopping distance)
- `CancerClassification.csv` – Dataset for classification task (benign vs malignant cells)
- `6906678_Coursework.ipynb` – Jupyter notebook containing all model implementations, evaluations, and visualizations

---

## Part 1: 🚗 Regression – Predicting Stopping Distance

### 📊 Dataset
- Features: `Speed` (mph)
- Target: `Distance` (feet)

### ✅ Models Implemented
- Linear Regression
- Polynomial Regression (Degree 2 and 3)

### 📈 Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

### 🔍 Key Observations
- Polynomial Regression (Degree 3) performed best with highest R² (0.90+) and lowest error rates.
- Visualizations include scatter plots and fitted curves for all models.

---

## Part 2: 🧬 Classification – Predicting Cancer Class

### 📊 Dataset
- Features: 9 medical measurements (e.g., Clump Thickness, Cell Size)
- Target: `Class` (0 = Benign, 1 = Malignant)

### ✅ Model Implemented
- Logistic Regression

### 📈 Evaluation Metrics
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)
- ROC Curve

### 🔍 Key Observations
- Overall accuracy: 68.6%
- Model struggles with malignant (Class 1) recall (only 38%)
- Imbalance in classes affects performance
- Highest priority metric: Recall for Class 1 to minimize false negatives

---

## 📊 Visualizations
- Scatter and line plots for regression models
- Confusion matrix heatmap
- Classification bar chart (Precision, Recall, F1-score)
- ROC Curve with AUC
- Class distribution pie chart

---

## 💻 Libraries Used
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn`: LinearRegression, PolynomialFeatures, LogisticRegression, evaluation metrics

---

## 📝 How to Run
1. Upload both datasets (`Stopping.csv` and `CancerClassification.csv`)
2. Open `6906678_Coursework.ipynb` in Jupyter Notebook or Google Colab
3. Run all cells sequentially to reproduce the analysis and visualizations

---

## 📌 Author
- [`AadityaArunSingh`](https://github.com/AadityaArunSingh)
