\# Census Income Prediction (Machine Learning Project)



This project predicts whether a person's annual income exceeds \*\*$50K\*\* using demographic and employment-related attributes from the Census dataset.  

The goal is to build a classification model that can accurately identify income level based on the available features.



---



\## 📌 Project Overview

The Census Income dataset includes features like age, education, occupation, marital status, work class, capital gains, and hours-per-week.  

This project explores data preprocessing, feature engineering, model selection, and evaluation using multiple ML algorithms.



---



\## 📂 Dataset

\- \*\*Source:\*\* UCI Adult Census Income Dataset  

\- \*\*Target Variable:\*\* `income` (<=50K or >50K)



---



\## 🛠️ Tech Stack

\- Python  

\- Pandas, NumPy  

\- Matplotlib, Seaborn  

\- Scikit-learn  

\- Jupyter Notebook  



---



\## 📊 Exploratory Data Analysis (EDA)

The following were performed:



\- Distribution analysis (age, hours-per-week, education level)

\- Missing value check

\- Outlier detection

\- Correlation analysis

\- Categorical feature exploration (occupation, marital status, work class, etc.)



---



\## 🔧 Data Preprocessing

\- Handling missing values  

\- Label encoding for categorical features  

\- Train-Test Split  

\- Feature scaling (where necessary)  

\- Converting target values to binary classes  



---



\## 🤖 Machine Learning Models Used

The following models were trained and evaluated:



| Model                | Accuracy |

|----------------------|----------|

| Logistic Regression  | ~78%     |

| Decision Tree        | ~78%     |

| \*\*Random Forest\*\*    | \*\*82%\*\*  |



✅ \*\*Random Forest performed the best with an accuracy of 82%.\*\*



---



\## 📈 Visualizations



\### Income Distribution

!\[Income Distribution](https://raw.githubusercontent.com/PayalKolhe1096/census-income-ml-project/main/Visuals/Annual\_income\_Distribution.png)



\### Correlation Heatmap

!\[Correlation Heatmap](https://raw.githubusercontent.com/PayalKolhe1096/census-income-ml-project/main/Visuals/Correlation.png)



\### Confusion Matrix - Random Forest

!\[Confusion Matrix](https://raw.githubusercontent.com/PayalKolhe1096/census-income-ml-project/main/Visuals/Confusion\_Matrix\_RF.png)



\### Top 10 Feature Importance

!\[Top Features](https://raw.githubusercontent.com/PayalKolhe1096/census-income-ml-project/main/Visuals/Top\_10\_Features.png)



