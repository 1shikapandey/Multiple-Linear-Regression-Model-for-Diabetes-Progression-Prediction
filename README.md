# Multiple-Linear-Regression-Model-for-Diabetes-Progression-Prediction
A machine learning project using Multiple Linear Regression (MLR) on the Scikit-learn Diabetes dataset to predict disease progression based on 10 medical features. The model is trained, tested, and evaluated using performance metrics like MSE, RMSE, and R² score, with visualizations for better insight.


## 📌 Overview
This project applies **Multiple Linear Regression (MLR)** to the Scikit-learn **Diabetes dataset** to predict the progression of diabetes based on medical and physiological data.  
It demonstrates data exploration, preprocessing, model building, evaluation, and visualization.

---

## 📂 Dataset
- **Source:** `sklearn.datasets.load_diabetes`
- **Samples:** 442
- **Features:** 10 numerical predictors (e.g., BMI, blood pressure, age)
- **Target:** Disease progression after one year

---

## ⚙️ Methodology
1. Load and explore dataset
2. Convert to DataFrame and analyze correlations
3. Train-test split (80-20)
4. Fit MLR model using `LinearRegression`
5. Evaluate with:
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)
   - R² Score
6. Visualize predictions and residuals

---

## 📊 Results
- **R² Score:** ~0.51
- **MSE & RMSE:** Show prediction error magnitude
- **Insights:** BMI and blood pressure are strong predictors

---

## 📌 Requirements
```bash
pip install numpy pandas matplotlib seaborn scikit-learn

▶️ How to Run
Clone this repository:

bash
Copy
Edit
git clone https://github.com/yourusername/diabetes-mlr.git
Navigate to the project directory:

bash
Copy
Edit
cd diabetes-mlr
Run the Jupyter Notebook or Python file:

bash
Copy
Edit
jupyter notebook diabetes_mlr.ipynb
or

bash
Copy
Edit
python diabetes_mlr.py
