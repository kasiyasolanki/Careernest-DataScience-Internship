# Careernest-DataScience-Internship
Supermarket Sales EDA, Modeling &amp; Analysis – Careernest Internship


**Project:** Supermarket Sales — Exploratory Data Analysis  
**Intern:** Kasiya Solanki  

## Task 1 – Beginner: EDA
- Explored Supermarket Sales dataset  
- Performed data cleaning, summary statistics, and categorical analysis  
- Created visualizations: histogram, bar charts, pairplots  
- Key insights on customer behavior, product lines, and payments  

## How to Run
1. Open notebook in Google Colab or Jupyter.  
2. Install required libraries: `pip install pandas matplotlib seaborn numpy`  
3. Run all cells sequentially.

## GitHub Repo Structure
notebooks/
data/
README.md


---

## 🧠 Task 2: Customer Type Prediction using Classification

### 📌 Objective:
To predict whether a customer is a **Member** or **Normal Customer** using classification models like Logistic Regression and Random Forest.

### ⚙️ Process:
- Preprocessed data from the Supermarket Sales dataset.
- Applied **Label Encoding** to convert categorical variables.
- Trained models: Logistic Regression and Random Forest.
- Evaluated model performance using **accuracy score, confusion matrix, and classification report**.

### 📊 Results:
- The regression model was giving unrealistically perfect accuracy (overfitting due to data leakage).
- Hence, the problem was reframed as a **classification task**, which fits the dataset better.

