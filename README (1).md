
# 🛳 Titanic EDA + Classification

This repository contains an Exploratory Data Analysis (EDA) and predictive modeling pipeline using the Titanic dataset from Kaggle. The objective is to analyze the dataset, extract insights, and build classification models to predict passenger survival.

---

## 📊 Project Structure

- `Titanic_EDA_Colab.ipynb`: Google Colab notebook with full EDA, preprocessing, visualization, model training, and evaluation.
- `submission.csv`: Final predictions on the test set using the trained model.
- `README.md`: Overview of the project.

---

## 🔍 Dataset

Dataset source: [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data)

Files used:
- `train.csv` — used for training the model and EDA.
- `test.csv` — used for generating predictions.
- `submission.csv` — output file with predicted survival.

---

## 🧪 Methods Used

- **EDA & Visualization**
  - Survival distribution by gender and passenger class
  - Age and fare distribution
  - Handling missing data
- **Feature Engineering**
  - Created `FamilySize` feature
  - Label Encoding for categorical variables
- **Modeling**
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier

---

## 🧠 Model Performance

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression| ~76%     |
| Decision Tree      | ~81%     |
| Random Forest      | ~81%     |

---

## ✅ Final Output

The `submission.csv` file contains predicted survival values for passengers in the test set using the best-performing model.

---

## 📌 How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Upload `train.csv` and `test.csv`
3. Run all cells
4. A `submission.csv` file will be generated

---

## 👩‍💻 Author

- **Name:** Bhumika Hazra
- **Institution:** UIT

