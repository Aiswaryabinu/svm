# Support Vector Machine (SVM) Project

This repository demonstrates the use of Support Vector Machines (SVM) for binary classification using both linear and RBF kernels. The project guides you through the following steps:

1. **Load and prepare a dataset for binary classification**
2. **Train an SVM with linear and RBF kernel**
3. **Visualize the decision boundary using 2D data**
4. **Tune hyperparameters like C and gamma**
5. **Use cross-validation to evaluate performance**

---

## Steps

### 1. Load and Prepare a Dataset

- The code loads a 2D dataset suitable for binary classification (e.g., `make_blobs` or `make_moons` from scikit-learn).
- The data is split into train and test sets, and features are scaled for better SVM performance.

### 2. Train SVM Models

- The repository provides scripts to train SVMs with both linear and RBF (Gaussian) kernels using scikit-learn's `SVC` class.

### 3. Visualize Decision Boundaries

- For 2D datasets, the code visualizes data points and plots the decision boundaries for both kernels.

### 4. Hyperparameter Tuning

- The effects of hyperparameters `C` (regularization) and `gamma` (RBF kernel) are explored.
- Grid search or similar techniques are used for parameter tuning.

### 5. Cross-Validation

- Model performance is evaluated using k-fold cross-validation.
- Metrics such as accuracy, precision, recall, and F1-score are reported.

---

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Aiswaryabinu/svm.git
   cd svm
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the main example:**
   ```bash
   python svm_example.py
   ```

---

## Example Code Outline

- `svm_example.py`  
  Core script that loads data, trains SVMs, visualizes boundaries, tunes hyperparameters, and evaluates with cross-validation.

- `utils.py`  
  Helper functions for plotting and data handling.

---

## References

- [Scikit-learn SVM Documentation](https://scikit-learn.org/stable/modules/svm.html)
- [SVM Theory (Wikipedia)](https://en.wikipedia.org/wiki/Support_vector_machine)
- [SVM Visualization Tutorial](https://scikit-learn.org/stable/auto_examples/svm/plot_iris.html)

---

## License

MIT License. See [LICENSE](LICENSE) for details.

---
