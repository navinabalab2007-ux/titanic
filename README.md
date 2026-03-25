# 🚢 Titanic Survival Prediction - Machine Learning Project

## 📌 Overview

This project predicts whether a passenger survived or not using Machine Learning models.
The dataset is cleaned, processed, and improved using feature engineering techniques.

---

## 🔧 Steps Performed

### 🧹 Data Cleaning

* Removed unnecessary columns (PassengerId)
* Handled missing values (Embarked)
* Renamed incorrect column names

### ⚙️ Feature Engineering

* Created **FamilySize** = sibsp + Parch + 1
* Created **IsAlone**:

  * 1 → Alone
  * 0 → Not Alone

These features help the model understand passenger relationships better.

---

## 🤖 Models Used

### 🔹 Logistic Regression

* Suitable for binary classification
* Performed best on this dataset

### 🔹 Random Forest

* Handles complex patterns
* Used for comparison

---

## 📊 Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 0.81 ✅   |
| Random Forest       | 0.76     |

---

## 📉 Confusion Matrix

```
[158  24]
[ 46  34]
```

* TN = 158
* FP = 24
* FN = 46
* TP = 34

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## 📁 Project Structure

```
titanic-ml-project/
│
├── data/
│   └── train_and_test2.csv
├── notebook.ipynb
├── titanic_model.pkl
├── requirements.txt
├── README.md
```

---

## 🚀 How to Run

1. Install dependencies:

```
pip install -r requirements.txt
```

2. Run the notebook or Python file

---

## 🎯 Conclusion

* Feature engineering improved model performance
* Logistic Regression achieved better accuracy
* Family-based features played a key role

---

## 📌 Future Improvements

* Hyperparameter tuning
* Try advanced models like XGBoost
* Deploy as a web application

---

## 🙌 Author

Navinabala
