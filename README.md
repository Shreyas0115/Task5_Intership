# 🧠 Task 5: Decision Trees and Random Forests

## 📌 Objective  
Learn and apply tree-based machine learning models (Decision Trees and Random Forests) for classification and regression tasks using Scikit-learn.

---

## 🔧 Tools & Libraries Used
- Python
- Scikit-learn
- matplotlib
- Pandas / NumPy
- Seaborn

---

## 📊 Dataset  
Used the **Heart Disease Dataset** to predict the presence of heart disease based on patient attributes.  

---

## ✅ What I Learned

### 🔹 Decision Tree Classifier
- Trained a `DecisionTreeClassifier` using Scikit-learn.
- Visualized tree structure using `plot_tree` and Graphviz.
- Learned about splitting based on Gini impurity or entropy.
- Interpreted decision paths and leaf nodes.

### 🔹 Overfitting and Tree Depth Control
- Identified overfitting with unrestricted trees.
- Controlled model complexity with:
  - `max_depth`
  - `min_samples_split`
  - `min_samples_leaf`

### 🔹 Random Forest Classifier
- Implemented `RandomForestClassifier`.
- Improved accuracy by aggregating multiple decision trees.
- Reduced variance and overfitting through bagging.

### 🔹 Feature Importance
- Extracted and visualized feature importances from the trained random forest.
- Understood which features contribute most to predictions.

### 🔹 Model Evaluation with Cross-Validation
- Applied `cross_val_score` for evaluating model performance.
- Measured accuracy, precision, recall, and F1-score.

---

## 💬 Key Interview Concepts

- **How does a decision tree work?**  
  A decision tree splits data recursively on feature values to reach predictions through decision rules.

- **What is entropy and information gain?**  
  Entropy measures impurity; information gain measures the reduction in entropy after a split.

- **Why is Random Forest better than a single tree?**  
  It combines multiple trees for better generalization, reducing variance and overfitting.

- **What is overfitting and how is it prevented?**  
  Overfitting occurs when the model learns noise. Prevent using depth control, pruning, or ensemble methods.

- **What is bagging?**  
  Bagging (Bootstrap Aggregating) trains models on different subsets of the data and combines their outputs.

- **How do you visualize a decision tree?**  
  Using `sklearn.tree.plot_tree()` or `export_graphviz()` for more advanced visualization.

- **How do you interpret feature importance?**  
  By checking which features cause the largest reduction in impurity across the trees.

- **Pros/Cons of Random Forests**  
  - Pros: High accuracy, handles missing values, avoids overfitting  
  - Cons: Less interpretable, more resource-intensive

---
