# 🚢 Titanic Survival Prediction

A Machine Learning classification project that predicts whether a passenger survived the Titanic disaster based on demographic and travel-related features. The project includes data preprocessing, visualization, and model training using Logistic Regression.

---

## 📌 Problem Statement

The goal is to build a classification model that predicts survival (`0 = No`, `1 = Yes`) using features such as:

* passenger class
* sex
* age
* number of siblings/spouses
* number of parents/children
* fare
* embarkation port

---

## 📂 Dataset

* Dataset: Titanic dataset
* Target variable: `Survived`

### Features used:

* Pclass
* Sex
* Age
* SibSp
* Parch
* Fare
* Embarked

### Dropped columns:

* Name
* Ticket
* Cabin
* PassengerId

---

## 🔍 Exploratory Data Analysis (EDA)

Performed analysis to understand feature relationships:

* Count plots:

  * survival distribution
  * survival vs sex
  * survival vs passenger class
* Histograms:

  * age distribution
  * fare distribution
* Heatmap:

  * correlation between numerical features

These helped identify key patterns such as higher survival rates for females and first-class passengers.

---

## ⚙️ Data Preprocessing

### 1. Handling Missing Values

* `Age` filled using central tendency
* `Embarked` filled with most frequent value

---

### 2. Encoding

* Converted categorical variables using encoding techniques:

  * Sex
  * Embarked

---

### 3. Feature Separation

* `X` → features
* `y` → target (`Survived`)

---

### 4. Train-Test Split

* 80% training
* 20% testing
* `random_state = 42`

---

### 5. Feature Scaling

* Applied `StandardScaler` on numerical features

---

## 🤖 Model Training

### Model Used:

* Logistic Regression

The model was trained on processed data and used to classify survival outcomes.

---

## 📊 Model Evaluation

### Metrics Used:

* Accuracy Score
* F1 Score

These metrics evaluate overall classification performance and balance between precision and recall.

---

## 📈 Results

* The model achieved strong performance on the test dataset
* Features like sex, passenger class, and fare showed significant influence on survival

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

---

## 📁 Project Structure

```id="t3f9xa"
model.ipynb      # EDA, preprocessing, and model training
README.md        # Documentation
```

---

## 🚀 Key Learnings

* Handling missing values in real datasets
* Encoding categorical variables for ML models
* Applying logistic regression for classification problems
* Using evaluation metrics like accuracy and F1 score

---

## ⚠️ Limitations

* Only one model used (Logistic Regression)
* Limited evaluation metrics
* No cross-validation or hyperparameter tuning

---

## 🔮 Future Improvements

* Compare multiple classification models
* Add confusion matrix and ROC-AUC analysis
* Perform feature engineering
* Use cross-validation for better generalization

---
