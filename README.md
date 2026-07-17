# Multiple Linear Regression from Scratch using NumPy

## 📌 Objective
This project implements Multiple Linear Regression from scratch using NumPy and compares its performance with Scikit-Learn.

## 📂 Dataset
- Health Insurance Dataset
- Target Variable: Charges
- Input Features:
  - Age
  - BMI
  - Children
  - Sex
  - Smoker
  - Region

## 🚀 Implementation
- Data Preprocessing
- One-Hot Encoding
- Train-Test Split
- Feature Scaling
- Weight Initialization
- Bias Initialization
- Prediction Function
- Mean Squared Error (MSE)
- Gradient Calculation
- Gradient Descent
- Model Training

## 📊 Results

### NumPy Model
- Test MSE: **33608763.19**

### Scikit-Learn Model
- MAE: **4181.19**
- MSE: **33596915.85**

The NumPy implementation produced results very close to Scikit-Learn, validating the correctness of the model.

## 📈 Visualizations
- Loss vs Epochs
- Actual vs Predicted Values

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- Google Colab
