# 🧠 Breast Cancer Prediction — Decision Tree (Small Project)

## 📌 Overview
This project demonstrates the use of a **Decision Tree Classifier** to predict whether a patient has breast cancer based on medical attributes.  
The dataset (`data.csv`) contains labeled instances, and the project walks through data preprocessing, model training, evaluation, and visualization.

---

## 📂 Files in this Repository
- `breast_cancer_small_project.ipynb` → Jupyter Notebook with full code, training, and evaluation.
- `data.csv` → Breast cancer dataset used in this project.


---

## ⚙️ Workflow
1. **Data Loading & Exploration**
   - Loaded dataset from `data.csv`
   - Checked for missing values, class distribution, and basic statistics.

2. **Preprocessing**
   - Split into features (`X`) and target (`y`)
   - Train-test split (80-20)

3. **Model Training**
   - Decision Tree Classifier from `scikit-learn`
   - Hyperparameters tuned (depth, split criteria)

4. **Evaluation**
   - Accuracy score
   - Confusion Matrix
   - Classification Report
   - ROC-AUC Curve

---

## 📊 Results
- **Accuracy:** ~ (insert your accuracy here, e.g., `0.95`)
- **Confusion Matrix & Report:** Included in the notebook
- **ROC-AUC Curve:** Plotted to visualize classifier performance

---

## 🚀 Tech Stack
- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 📌 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/ishanegi5/breast-cancer-prediction-decision-tree.git
   cd breast-cancer-prediction-decision-tree
   
Install dependencies:


pip install -r requirements.txt

Open the notebook:

jupyter notebook breast_cancer_small_project.ipynb

📜 License
This project is open-source and available under the MIT License.

