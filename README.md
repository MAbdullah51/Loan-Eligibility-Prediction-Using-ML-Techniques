# Loan Eligibility Prediction Using Machine Learning Techniques.

## 📌 Overview
This project predicts loan approval status based on applicant demographic and financial information.  
The goal is to help financial institutions automate the loan approval process, making it faster, more accurate, and fairer.

## 📊 Dataset
The dataset contains information such as:
- Applicant Income
- Coapplicant Income
- Loan Amount & Term
- Credit History
- Gender, Marital Status, Education, Employment Status
- Loan Status (Target variable: Y/N)


## 🔍 Methodology
1. **Data Preprocessing**
   - Handling missing values
   - Feature engineering (`TotalIncome`, log transformations)
   - Encoding categorical variables
   - Scaling numerical features

2. **Exploratory Data Analysis**
   - Distribution plots
   - Boxplots to detect outliers
   - Cross-tab analysis for categorical relationships

3. **Model Training**
   - Decision Tree Classifier
   - Naive Bayes Classifier

4. **Evaluation**
   - Accuracy comparison between models
   - Naive Bayes achieved the best performance

## 📈 Results
| Model              | Accuracy |
|--------------------|----------|
| Decision Tree      | 70%      |
| Naive Bayes        | 82% ✅   |

## 🛠 Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib
- scikit-learn

---

## 📄 For Further Details
For the complete explanation, analysis, and full code with outputs, please check the **Project Report** included in this repository.
