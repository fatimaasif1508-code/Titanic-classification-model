# Titanic Survival Prediction  

## 📌 Project Overview  
This project uses the **Titanic dataset** to build machine learning models that predict whether a passenger survived or not, based on features such as age, gender, ticket class, fare, and family relations.  

The project includes:  
- Data cleaning & preprocessing  
- Exploratory Data Analysis (EDA) with visualizations  
- Multiple ML models (Logistic Regression, Random Forest, SVM)  
- Model evaluation using accuracy, classification report, confusion matrix, ROC curves  
- Feature importance analysis  

---

## 📂 Dataset  
The dataset used is the classic **Titanic dataset**, which contains information about passengers such as:  
- `Pclass` – Ticket class (1st, 2nd, 3rd)  
- `Sex` – Gender  
- `Age` – Age in years  
- `Fare` – Ticket fare  
- `SibSp` – Number of siblings/spouses aboard  
- `Parch` – Number of parents/children aboard  
- `Embarked` – Port of embarkation (C, Q, S)  
- `Survived` – Target variable (0 = Died, 1 = Survived)  

---

## ⚙️ Preprocessing Steps  
- Missing values handled (`Age`, `Fare`, `Embarked`)  
- Label encoding for categorical features (`Sex`, `Embarked`)  
- Train-test split (80/20)  
- Feature scaling (if needed for SVM/Logistic Regression)  

---

## 📊 Exploratory Data Analysis (EDA)  
Some key visualizations include:  
- Survival distribution (count plot)  
- Gender vs Survival  
- Age distribution vs Survival (boxplot)  
- Fare distribution (histogram)  
- Feature importance (Random Forest)  

---

## 🤖 Models Used  
- Logistic Regression  
- Random Forest Classifier  
- Support Vector Machine (SVM)  

---

## 📈 Results & Evaluation  
- Accuracy, precision, recall, F1-score for each model  
- Confusion matrices (heatmaps)  
- ROC-AUC curve comparison  
- Cross-validation scores  

---

## 📌 How to Run  
1. download file
2. run on jupyter notebook
3. don't forget to download given dataset  
