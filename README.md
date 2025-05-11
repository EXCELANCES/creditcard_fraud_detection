# Credit Card Fraud Detection 🕵️‍♂️💳

This project is focused on detecting fraudulent credit card transactions using machine learning classification models. It demonstrates the full workflow from data preprocessing to model evaluation on a highly imbalanced dataset.

## 📊 Project Overview

* 📁 Dataset: European credit card transactions (September 2013)
* 🧪 Problem: Only 0.17% of transactions are fraudulent
* 📉 Challenge: Severe class imbalance
* 💡 Goal: Build a model that minimizes false positives while catching most frauds

## ⚙️ Technologies Used

* Python (Jupyter Notebook)
* Pandas, NumPy, Matplotlib, Seaborn
* Scikit-learn (Logistic Regression, Random Forest)
* XGBoost (optional)
* Git LFS (for large dataset handling)

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/EXCELANCES/creditcard_fraud_detection.git
   ```

2. Navigate to the project directory:

   ```bash
   cd creditcard_fraud_detection
   ```

3. (Optional) Create a virtual environment and activate it

4. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Launch the notebook:

   ```bash
   jupyter notebook Credit_Card_Fraud_Detection.ipynb
   ```

## 🔗 Dataset Source

Due to file size, the dataset is not included in the repository.
You can download it manually from:
👉 [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

Then place it in the `/data` folder.

## 📈 Model Evaluation

| Model               | Precision | Recall | F1 Score | ROC AUC |
| ------------------- | --------- | ------ | -------- | ------- |
| Logistic Regression | 0.86      | 0.62   | 0.72     | \~0.96  |
| Random Forest (?)   | 0.06      | 0.88   | 0.12     | —       |
| XGBoost (optional)  | TBD       | TBD    | TBD      | TBD     |

> These values are based on the actual output from the notebook. You can replace or update them as the project evolves.

## 📌 Features

* Exploratory Data Analysis (EDA)
* Feature Scaling (StandardScaler)
* Train/Test split
* Confusion Matrix, ROC Curve, Classification Report
* Class imbalance handling (SMOTE or undersampling)

## 🧑‍💻 Author

**Ertugrul Asliyuce**
MSc Data Analytics Student | Industrial Engineer | Data Enthusiast
📢 [ertuaslyc@gmail.com](mailto:ertuaslyc@gmail.com)
🌐 [easolid.com](https://easolid.com)
🔗 [LinkedIn](https://www.linkedin.com/in/ertugrul-asliyuce-a6140a143/)

## 📄 License

This project is licensed under the MIT License.
