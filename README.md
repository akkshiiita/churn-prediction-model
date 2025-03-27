
# 📊 Customer Churn Prediction for Credit Card Users

## 🚀 Project Overview  
This project focuses on **predicting customer churn** in the credit card industry using **machine learning and deep learning models**. The dataset includes customer demographics, transaction history, and credit behavior.

## 📂 Dataset  
The dataset consists of customer details such as:  
- **Demographics:** Age, gender, education level, income category, marital status  
- **Credit & Transaction Features:** Credit limit, total transactions, utilization ratio, etc.  
- **Target Variable:** `Attrition_Flag` (1 = Churned, 0 = Retained)  

## ⚙️ Data Preprocessing  
- **Handled Missing Values**  
- **Encoded Categorical Variables**  
  - Binary Encoding (e.g., Gender, Attrition Flag)  
  - Ordinal Encoding (e.g., Education Level, Income Category)  
  - One-Hot Encoding (e.g., Marital Status, Card Category)  
- **Feature Scaling** using `StandardScaler`  

## 🛠️ Models Used  
We trained and evaluated the following models:  
✅ **Logistic Regression**  
✅ **Support Vector Machine (SVM)**  
✅ **Decision Tree**  
✅ **Random Forest**  
✅ **Neural Network (Keras & TensorFlow)**  

## 🎯 Results  
| Model                 | Accuracy (%) |
|----------------------|-------------|
| Logistic Regression  | 90.77       |
| Support Vector Machine | 93.43    |
| Decision Tree        | 93.48       |
| Random Forest       | **96.10**   |
| Neural Network (Keras) | 93.53 |

👉 **Random Forest achieved the highest accuracy of 96.10%!**  

## 📌 How to Run  
### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/your-username/customer-churn.git
cd customer-churn
