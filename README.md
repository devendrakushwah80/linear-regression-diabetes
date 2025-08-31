# linear-regression-diabetes
Linear Regression model on the Diabetes dataset (scikit-learn) to predict disease progression.
# Diabetes Prediction using Linear Regression

This project demonstrates the use of **Linear Regression** on the popular **Diabetes dataset** from `scikit-learn`.  
The goal is to predict disease progression based on clinical features.

---

## 📊 Dataset
The dataset comes preloaded with scikit-learn:
- **Features (X):** 10 clinical variables (age, sex, BMI, blood pressure, etc.)
- **Target (y):** A quantitative measure of disease progression one year after baseline.

---

## ⚙️ Steps Performed
1. **Load Dataset** – Using `load_diabetes()` from scikit-learn  
2. **Data Preparation** – Converted features into a Pandas DataFrame  
3. **Train/Test Split** – 80% training, 20% testing  
4. **Model Training** – Linear Regression from scikit-learn  
5. **Evaluation** – Metrics used:
   - Mean Squared Error (MSE)  
   - R² Score  
6. **Visualization** – Scatter plot of Actual vs Predicted values  

---

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/diabetes-linear-regression.git
cd diabetes-linear-regression
