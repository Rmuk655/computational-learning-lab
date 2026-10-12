# Computational Learning Lab

Notebooks from machine-learning coursework (FOML) and self-study: core ML algorithms implemented with NumPy, then compared with their scikit-learn counterparts, plus a small graph-algorithms notebook. Everything is runnable end to end.

## Contents

### ML Foundations (`ML Foundations/`)

| Notebook | What it covers |
|---|---|
| `Perceptron Algorithm/Perceptron.ipynb`, `Perceptron_train_test.ipynb` | Perceptron learning rule from scratch, then a train/test evaluation with scikit-learn data utilities |
| `Linear Classifier/` | A random linear classifier baseline, and a linear classifier evaluated on held-out data |
| `Logical Regression/2D.ipynb` | Logistic regression on 2-D data |
| `Gradient Descent/1D.ipynb`, `2D.ipynb` | Gradient descent on one- and two-variable functions, with plots of the descent path |
| `Cross Entropy Loss/` | Cross-entropy loss visualized |
| `Sigmoid Visual/` | The sigmoid function and its saturation |
| `Regularization/` | Effect of regularization on a fitted model |
| `K Nearest Neighbours/knn.ipynb` | k-NN classification with scikit-learn, pandas and seaborn |
| `Classification/classifier_comparison.ipynb` | Decision boundaries of several classifiers on toy datasets (based on the scikit-learn example) |
| `One-Hot Encoding/` | One-hot encoding of categorical features |

### Supervised learning (`Supervised learning/`)

| Notebook | What it covers |
|---|---|
| `IntroTask.ipynb` | Introductory task from the Epoch Spring Camp 2025: text/data preprocessing with NLTK, pandas and NumPy |
| `Problem 1.ipynb`, `Problem 2.ipynb` | Practice problems with NumPy and Matplotlib |
| `Supervised_ML.ipynb` | Supervised learning workflow with scikit-learn: fit, predict, evaluate |

### Graph algorithms (`Graph Algorithms/`)

`Graphs.ipynb`: graph construction and traversal with NumPy and Matplotlib.

## Run

```bash
git clone https://github.com/Rmuk655/computational-learning-lab.git
cd computational-learning-lab
pip install -r requirements.txt
jupyter notebook
```

Open any notebook and run the cells in order.

## Notes

- Several notebooks are adapted from scikit-learn documentation examples; those are marked in their first cell.
- Notebook outputs are stored, so results can be read without re-running.
