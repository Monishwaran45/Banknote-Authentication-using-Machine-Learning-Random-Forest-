# 💰 Banknote Authentication using Machine Learning

This project uses Machine Learning to classify banknotes as **genuine (real)** or **forged (fake)** based on statistical features extracted from images.

---

## 🚀 Project Overview

Banknote authentication is a **binary classification problem** where the model predicts whether a note is real or fake.
This project uses a **Random Forest Classifier** to achieve high accuracy and reliable performance.

---

## 📊 Dataset Features

The dataset contains the following features: 

* **Variance** – variation of pixel values
* **Skewness** – asymmetry of distribution
* **Curtosis (Kurtosis)** – peak of distribution
* **Entropy** – randomness in the image
Dataset: https://www.kaggle.com/datasets/ritesaluja/bank-note-authentication-uci-data
### 🎯 Target:

* `0` → Fake
* `1` → Real

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Scikit-learn

---

## 🧠 Model Details

* Algorithm: Random Forest Classifier 🌳
* Train-Test Split: 70% / 30%
* Train Accuracy: **100%**
* Test Accuracy: **98.78%**
* Cross-Validation Score: **99.49%**

---

## 📈 Evaluation Metrics

| Metric    | Score       |
| --------- | ----------- |
| Accuracy  | 0.99        |
| Precision | 0.98 – 0.99 |
| Recall    | 0.99        |
| F1-Score  | 0.99        |

✔ The model shows **high performance and strong generalization** with minimal overfitting.

---

## 🔄 Workflow

1. Data Preprocessing
2. Train-Test Split
3. Model Training (Random Forest)
4. Prediction on Test Data
5. Model Evaluation
6. Hyperparameter Tuning

---

## 💻 How to Run

```bash
# Clone repository
git clone https://github.com/Monishwaran45/banknote-authentication.git

# Navigate to project folder
cd banknote-authentication

# Install dependencies
pip install -r requirements.txt

# Run the model
python main.py
```

---

## 🔧 Future Improvements

* Hyperparameter tuning using GridSearchCV
* Deploy as a web app (Streamlit / Flask)
* Add real-time prediction UI
* Use advanced models (XGBoost, LightGBM)

---

## 📌 Key Insight

> “A well-trained ensemble model like Random Forest can achieve near-perfect accuracy on structured datasets like banknote authentication.”

---

## ⭐ Support

If you found this project useful, give it a ⭐ on GitHub!

---
