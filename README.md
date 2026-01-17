# Cardiovascular Disease (CVD) Risk Prediction 🫀

This project uses machine learning to predict the risk level of cardiovascular diseases based on medical and lifestyle data.

## 📋 Dataset Overview
The dataset contains several health indicators such as:
- **Demographics:** Age, Sex.
- **Physical Metrics:** BMI, Weight, Abdominal Circumference.
- **Medical Tests:** Cholesterol (HDL, LDL), Blood Sugar, Systolic & Diastolic BP.
- **Lifestyle:** Smoking Status, Physical Activity Level.

**Target:** `CVD Risk Level` (Classified into High Risk vs Low/Intermediate).

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, Scikit-learn, Seaborn, Matplotlib.

## ⚙️ Data Preprocessing Highlights
- Handled missing values using mean imputation for numerical columns.
- Encoded categorical variables (Sex, Smoking, Diabetes, Family History).
- Created dummy variables for Physical Activity Levels.
- Applied **StandardScaler** for feature normalization.

## 📊 Model Performance
Two models were trained and compared:

| Model | Accuracy |
| :--- | :---: |
| **Logistic Regression** | ~74% |
| **Random Forest** | ~75% |

## 🔍 Key Risk Factors (Feature Importance)
According to the Random Forest model, the top 5 factors influencing the risk are:
1. **HDL (Good Cholesterol)**
2. **Estimated LDL (Bad Cholesterol)**
3. **Age**
4. **BMI**
5. **Smoking Status**

## 🚀 How to Use
1. Clone the repo.
2. Ensure you have `scikit-learn` and `pandas` installed.
3. Run the `task.ipynb` notebook to see the analysis and model evaluation.
