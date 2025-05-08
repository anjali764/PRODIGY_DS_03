![image](https://github.com/user-attachments/assets/14fd3ab4-a657-45d1-a3ab-be19ee1c9fdb)


# 🧠 Task 3: Decision Tree Classifier – Bank Marketing Prediction

This project was developed as part of my internship at **Prodigy InfoTech**. The objective of the task was to build a **Decision Tree Classifier** to predict whether a client will subscribe to a term deposit (yes/no) using the **Bank Marketing dataset** from the UCI Machine Learning Repository.

---

## 📁 Dataset

- **Source**: [UCI ML Repository – Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
- **File Used**: `bank-additional.csv`
- **Target Variable**: `y` – indicates if the client subscribed to a term deposit.
- **Attributes**: Includes client demographics, past marketing interactions, and socio-economic context.

---

## 🧰 Tools & Libraries

- `Python`
- `pandas`, `numpy`
- `seaborn`, `matplotlib`
- `scikit-learn`

---

## 🔄 Project Workflow

1. **Data Loading** – Read the CSV file into a pandas DataFrame.
2. **Exploratory Data Analysis (EDA)** – Basic understanding of shape, types, and sample data.
3. **Preprocessing**
   - Label encoding for categorical features.
   - Handling of missing values.
4. **Model Building**
   - DecisionTreeClassifier from `sklearn.tree`
   - Training on 80% of the dataset and testing on 20%.
5. **Model Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
6. **Tree Visualization**
   - Using `plot_tree` to visualize decision paths.

---

## ✅ Key Learnings

This task taught me how to:

- Work with real-world datasets.
- Encode categorical variables.
- Use Decision Trees to classify binary outcomes.
- Interpret model performance using key metrics.
- Visualize tree-based models for explainability.

---

## 📊 Sample Output

- **Model Accuracy**: Achieved a high accuracy on test data.
- **Confusion Matrix**: Presented for detailed prediction analysis.
- **Tree Plot**: Helps understand how features contribute to decision-making.

---

## 👤 Author

Internship Project – Task 3  
By **Anjali Patwa**  
Prodigy InfoTech
