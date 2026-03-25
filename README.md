# Breast Cancer Classification using Machine Learning

## 📌 Project Overview
This project focuses on predicting whether a tumor is **malignant (M)** or **benign (B)** using various machine learning algorithms.  
The dataset is preprocessed and multiple classification models are trained and evaluated.

---

## 📂 Dataset
- File used: `breast_cancer.csv`
- Target column: `diagnosis`
  - M → 1 (Malignant)
  - B → 0 (Benign)

### Preprocessing Steps:
- Removed unnecessary columns: `id`, `Unnamed: 32`
- Converted categorical labels into numeric values
- Split data into features (`X`) and labels (`y`)

---

## ⚙️ Technologies Used
- Python 🐍
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- XGBoost

---

## 🧠 Machine Learning Models Used
The following models were trained and evaluated:

1. Support Vector Machine (SVM)
2. Decision Tree
3. Naive Bayes (GaussianNB)
4. Logistic Regression
5. Random Forest
6. XGBoost

---

## 🔀 Train-Test Split
- 80% Training Data
- 20% Testing Data
- Random State: 122

---

## 📊 Evaluation Metrics
Each model is evaluated using:
- Confusion Matrix
- Accuracy Score
- F1 Score (for both classes)

---

## ▶️ How to Run the Project

1. Clone the repository:
```bash
git clone <-repo-link>
Install required libraries:
pip install numpy pandas matplotlib scikit-learn xgboost
Run the script:
python breast_cancer.py
📈 Output

For each model, the following results are displayed:
Training Accuracy
Testing Accuracy
Confusion Matrix
F1 Scores

⚠️ Notes
1. Make sure breast_cancer.csv is in the same directory as the script.
2. XGBoost requires additional installation:
   pip install xgboost

🚀 Future Improvements
Hyperparameter tuning
Cross-validation
Feature selection
Model comparison visualization

📜 License
This project can be licensed under the MIT License (free to use with attribution).

🙌 Acknowledgements
Scikit-learn documentation
Open-source dataset providers
