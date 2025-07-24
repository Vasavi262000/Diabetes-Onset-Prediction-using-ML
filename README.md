# Diabetes Prediction using Machine Learning
This project applies various supervised machine learning algorithms to predict the likelihood of diabetes in patients based on diagnostic measurements from the Pima Indians Diabetes dataset.
---
## 📊 Dataset

# Dataset Setup

Please download the `diabetes.csv` dataset from the following source (e.g., UCI repository or Kaggle):

- [Diabetes Dataset - Kaggle](https://www.kaggle.com/uciml/pima-indians-diabetes-database)

Once downloaded, place the file `diabetes.csv` into the folder named `data` within this project directory.

The expected file path is:  
`./data/diabetes.csv`

---
## 🛠️ Steps Performed

1. **Load and inspect data**  
2. **Replace zeroes with column means** for fields where zero is invalid (e.g., Glucose, BMI)
3. **Train-test split** and standardization
4. **Model training**: Logistic Regression, Random Forest, Gradient Boosting, SVM, XGBoost
5. **Evaluation** using Accuracy, F1-score, ROC-AUC
6. **Visualizations**: Confusion Matrix, ROC curves
7. **Model saving** using Joblib

---
## ✅ Best Model

The best performing model is saved under the `results/` directory as a `.pkl` file and can be reloaded for inference without retraining.

---

## 🚀 Getting Started

### 1. Clone the repository

git clone https://github.com/Vasavi262000/Diabetes-Onset-Prediction-using-ML.git
cd Diabetes-Onset-Prediction-using-ML


### 2. Install Dependencies
pip install -r requirements.txt

### 3. Run the Notebook
Open the notebook in Jupyter:

jupyter notebook Diabetes onset prediction.ipynb

🧪 Dependencies
See requirements.txt

📧 Contact
For questions or suggestions, contact kurravasavi2@gmail.com
