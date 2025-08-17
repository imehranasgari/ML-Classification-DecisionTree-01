# Decision Tree (Classification)

## 🧩 Problem Statement and Goal of Project

The goal of this project is to perform classification using the Decision Tree algorithm on a dataset loaded from a CSV file (`Social_Network_Ads.csv`). The classification task involves predicting whether a user purchases a product based on features such as age and estimated salary.

This project applies a **Decision Tree Classifier** to predict whether a user will purchase a product based on social network ad data. The dataset contains user attributes such as **age** and **estimated salary**, and the binary target variable indicates whether the product was purchased (`1`) or not (`0`).

The goal is to:

* Understand how Decision Trees partition feature space.
* Train and evaluate a model on real-world user behavior data.
* Visualize decision boundaries to explain classification.


## 🛠 Solution Approach

The notebook follows a well-structured classification pipeline:

1. **Data Loading**:

   * Read from `Social_Network_Ads.csv`
2. **Preprocessing**:

   * Extract features and labels.
   * Apply `StandardScaler` for feature normalization.
3. **Train-Test Split**:

   * 75% training / 25% test split using `train_test_split`.
4. **Model Training**:

   * Use `DecisionTreeClassifier` with `'entropy'` criterion.
5. **Prediction**:

   * Test prediction for a sample input (`[30, 87000]`)
6. **(Optional)**: Visualizations and interpretability analysis.

## 🧰 Technologies & Libraries Used

* Python 3
* `pandas`, `numpy` – data manipulation
* `scikit-learn` – model training, preprocessing, evaluation
* `matplotlib`, `seaborn` – plotting and visualization

## 🚀 Installation & Execution Guide

**Installation**: Not explicitly provided, but typically requires:

```bash
pip install numpy pandas matplotlib scikit-learn
```

**Execution**:

1. Ensure `Social_Network_Ads.csv` is present in the working directory.
2. Run the notebook `Decision Tree (Classification).ipynb` sequentially.

## 📊 Key Results / Performance

* Confusion matrix used to evaluate performance.
* No specific accuracy metrics (e.g., precision, recall, F1) were calculated.
* Visualizations suggest decent separation of classes by the decision tree.
* Successfully trained a Decision Tree model using entropy criterion.
* Sample test prediction performed for `[Age=30, Salary=87000]`.
* Feature scaling significantly improved decision boundary sharpness.

## 🖼️ Screenshots / Sample Outputs

* Plots included:

  * Decision boundaries for training set
  * Decision boundaries for test set

## 📚 Additional Learnings / Reflections

* Learned how **decision trees split based on information gain** (entropy).
* Emphasized the role of feature scaling in decision-based models.
* Understood basic interpretability of Decision Trees in classification tasks.
* 
## 📁 Dataset Description

* **File:** `Social_Network_Ads.csv`
* **Features**:

  * `Age`: Numerical
  * `EstimatedSalary`: Numerical
* **Target**:

  * `Purchased`: Binary label (0 or 1)
* **Goal**: Predict purchase behavior from demographic features.

---

## ⚙️ Installation & Execution Guide

1. Clone the repository or download the `.ipynb` file.
2. Install dependencies:

   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
3. Make sure `Social_Network_Ads.csv` is in the same directory.
4. Launch the notebook:

   ```bash
   jupyter notebook "Decision Tree (Classification).ipynb"
   ```


## 👤 Author

## mehran Asgari

**Email:** [imehranasgari@gmail.com](mailto:imehranasgari@gmail.com)
**GitHub:** [https://github.com/imehranasgari](https://github.com/imehranasgari)

---

## 📄 License

This project is licensed under the Apache 2.0 License – see the `LICENSE` file for details.

---

> 💡 *Some interactive outputs (e.g., plots, widgets) may not display correctly on GitHub. If so, please view this notebook via [nbviewer.org](https://nbviewer.org) for full rendering.*


