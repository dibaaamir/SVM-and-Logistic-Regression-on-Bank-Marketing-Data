# 🏦 Bank Marketing Campaign – Term Deposit Prediction

This project analyzes a real-world **bank marketing dataset** to predict whether a customer will subscribe to a **term deposit** based on information collected during telemarketing calls. The analysis is performed in a Jupyter Notebook using Python and popular data science libraries.

---

## 📁 Project Structure

- **Data Preprocessing**  
  - Load dataset (`bank-full.csv`)
  - Convert categorical features to numerical
  - Train-test split (80/20)
  - Normalize features using `StandardScaler`

- **Data Visualization**
  - Visual exploration of features using histograms, scatter plots, and correlation heatmaps

- **Model Training & Evaluation**
  - Train a **Linear Support Vector Machine (SVM)** using `scikit-learn`
  - Use `GridSearchCV` to tune hyperparameters (`C`, `gamma`)
  - Evaluate model performance on test set using accuracy

- **Manual Logistic Regression Implementation**
  - Custom implementation from scratch
  - Cross-Entropy loss function
  - Gradient descent to update weights iteratively

---

## 🧠 Key Features

- **Real-World Dataset**: Data from a marketing campaign by a Portuguese bank
- **End-to-End ML Workflow**: From raw data to custom model
- **Visualization**: Multiple plots used to explore patterns and trends
- **Custom ML**: Logistic Regression built manually without using ML libraries

---

## 📊 Dataset Description

| Feature     | Description                               |
|-------------|-------------------------------------------|
| age         | Age of the customer                       |
| job         | Type of job                               |
| marital     | Marital status                            |
| education   | Education level                           |
| balance     | Yearly account balance                    |
| housing     | Has housing loan (yes/no)                 |
| loan        | Has personal loan (yes/no)                |
| duration    | Last contact duration (in seconds)        |
| campaign    | Number of contacts during this campaign   |
| y (target)  | Subscribed to term deposit? (yes/no)      |

---

## 🛠 Technologies Used

- **Python**
- **Jupyter Notebook**
- **pandas** – data handling
- **matplotlib / seaborn** – visualizations
- **scikit-learn** – SVM model, scaling, GridSearch
- **NumPy** – numerical operations
- **Manual Implementation** – Logistic Regression using pure Python

