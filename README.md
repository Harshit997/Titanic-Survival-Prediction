# 🚢 Titanic Survival Prediction

A Machine Learning project that predicts whether a passenger survived the Titanic disaster based on demographic and travel features. This project demonstrates end-to-end ML workflow including data preprocessing, feature engineering, model training, and evaluation.

---

## 📌 Problem Statement

The goal is to build a classification model that predicts survival (0 = No, 1 = Yes) of passengers on the Titanic using features like age, sex, ticket class, fare, etc.

---

## 📂 Dataset

* Dataset: Titanic dataset (commonly used in ML competitions)
* Features include:

  * Passenger demographics (Age, Sex)
  * Ticket details (Pclass, Fare)
  * Family information (SibSp, Parch)
  * Embarkation port (Embarked)

---

## ⚙️ Workflow

### 1. Data Preprocessing

* Handled missing values:

  * Age → filled using central tendency
  * Embarked → filled with most frequent value
* Dropped irrelevant features:

  * Name, Ticket, Cabin
* Converted categorical variables using encoding techniques

---

### 2. Feature Engineering

* Created meaningful structured dataset from raw inputs
* Prepared features suitable for ML models

---

### 3. Model Training

Multiple models were trained and compared:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Naive Bayes
* Decision Tree
* Support Vector Machine (SVM)

---

### 4. Evaluation Metrics

Models were evaluated using:

* Accuracy Score
* F1 Score

Best performance achieved:

* **Accuracy:** ~84%
* **F1 Score:** ~82%

---

## 📊 Results

The models performed well on the test dataset, with Logistic Regression providing a strong balance between simplicity and performance.

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* Jupyter Notebook

---

## 📁 Project Structure

```
├── model.ipynb        # Main notebook (EDA, preprocessing, training)
├── dataset.csv        # Dataset used
├── README.md          # Project documentation
```

---

## 🚀 Key Learnings

* Importance of data cleaning and preprocessing
* Handling missing values effectively
* Comparing multiple ML models
* Evaluating models using appropriate metrics

---

## ⚠️ Limitations

* Basic evaluation metrics used (no cross-validation)
* Limited feature engineering
* No hyperparameter tuning applied

---

## 🔮 Future Improvements

* Add cross-validation for robust evaluation
* Perform hyperparameter tuning (GridSearchCV)
* Include ROC-AUC and confusion matrix analysis
* Build a deployment interface (Streamlit / Web App)

---

## 🤝 Contributing

Feel free to fork this repository and improve the project!

---

## 📬 Contact

If you have any suggestions or feedback, feel free to reach out.

---
