
# 🌸 Iris Classification using K-Nearest Neighbors (KNN)

This project demonstrates a complete pipeline for classifying Iris flower species using the K-Nearest Neighbors (KNN) algorithm. It includes preprocessing, experimentation with different `K` values, model evaluation, and decision boundary visualization.

---

## 📁 Files

- `Task6.ipynb` — Main Jupyter notebook with all code steps
- `Iris.csv` — Dataset containing features and species of Iris flowers

---

## 🚀 Steps Performed

### 1. Dataset Loading & Preprocessing
- Loaded `Iris.csv` and removed unnecessary columns (`Id`)
- Normalized features using `StandardScaler` to bring them to the same scale

### 2. Model Building
- Applied `KNeighborsClassifier` from `scikit-learn`
- Tried multiple values of **K** (from 1 to 20) to compare accuracies

### 3. Model Evaluation
- Evaluated the model using:
  - **Accuracy score**
  - **Confusion matrix**
- Best `K` is selected based on highest test accuracy

### 4. Decision Boundary Visualization
- Reduced features to 2D using PCA
- Visualized the decision boundaries using matplotlib and color-coded classes

---

## 📊 Example Output

- Best accuracy achieved with `K = 3`
- Clear separation between species in the decision plot

---

## 🧪 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

Or manually:

```bash
pip install pandas scikit-learn matplotlib
```

---

## ✅ How to Run

1. Clone this repository:
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. Launch the notebook:
```bash
jupyter notebook Task6.ipynb
```

---

## 📚 Dataset Source

The [Iris dataset](https://www.kaggle.com/datasets/uciml/iris) is a classic benchmark dataset in machine learning for classification tasks.

---

## 👨‍💻 Author

- abhisheksingh0505
- GitHub: ((https://github.com/abhisheksingh0505))

---


