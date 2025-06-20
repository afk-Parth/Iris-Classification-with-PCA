# Iris Classification with PCA 

Dimensionality reduction and classification on the classic Iris flower dataset using PCA and Logistic Regression.

---

### 📊 Dataset
- **Source**: `load_iris()` from scikit-learn
- **Classes**: Setosa, Versicolor, Virginica
- **Features**: 4 numeric (sepal & petal length/width)

---

### 🔻 PCA (Principal Component Analysis)
- Reduced original 4D data to 2D using PCA
- Helped visualize how well classes are separated
- Explained variance: ⬜ 95–99% with 2 components

---

### 🧠 Model
- **Algorithm**: Logistic Regression
- **Accuracy**: ⬜ ~0.97 (actual value after training)
- Evaluated using accuracy and classification report

---

### 📈 Visualization
- 2D PCA scatter plot shows class separation
- Colored points by class label

---

### 📁 Tools
- Python, pandas, scikit-learn, matplotlib, seaborn

---

### ✅ How to Run
```bash
pip install pandas scikit-learn matplotlib seaborn
python iris_pca_classifier.ipynb  # or run in Colab
