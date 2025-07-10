# PRODIGY_DS-02
Repository about Prodigy Data Science Task-02

# Overview
This repository presents a comprehensive Exploratory Data Analysis (EDA) on the famous Titanic Dataset. The goal is to uncover hidden trends, understand feature importance, and clean the data for future machine learning applications.

# Key Objectives

-  Handle and clean missing values  
-  Encode categorical features for analysis  
-  Visualize survival trends across various attributes  
-  Understand correlation between features  
-  Prepare dataset for future machine learning tasks

 # Data Cleaning Steps

-  Dropped irrelevant columns: `Name`, `Ticket`, `Cabin`, `PassengerId`
-  Filled missing `Age` values with **median**
-  Filled missing `Embarked` values with **mode**
-  Encoded `Sex` and `Embarked` into numerical format
-  Created new feature: `FamilySize` = `SibSp + Parch + 1`

Visualizations Included

1. **Survival Count**
<img width="917" height="544" alt="image" src="https://github.com/user-attachments/assets/aa9ca072-c62d-46c5-9e04-cc5faae7b52b" />

2. **Survival by Sex**
<img width="914" height="539" alt="image" src="https://github.com/user-attachments/assets/c8830cd8-7419-42ad-9fc1-5736437a087f" />
   
3. **Survival by Passenger Class**
<img width="912" height="549" alt="image" src="https://github.com/user-attachments/assets/54b22738-55dc-4e3e-b3e4-2486ce1c42ea" />
   
4. **Age Distribution vs Survival**
 <img width="916" height="545" alt="image" src="https://github.com/user-attachments/assets/4cc41b40-074e-42c5-90c4-f69ce4141973" />
  
5. **Fare vs Survival**
<img width="919" height="553" alt="image" src="https://github.com/user-attachments/assets/202296ee-4878-41f4-9e00-a30574a5186b" />
   
6. **Embarkation Port vs Survival**
<img width="915" height="546" alt="image" src="https://github.com/user-attachments/assets/86d24893-0139-4629-988b-6f63725b51e2" />
   
7. **Family Size vs Survival**
<img width="919" height="538" alt="image" src="https://github.com/user-attachments/assets/1a23abd5-4f88-4e2a-9a68-ba31c9bf60b0" />
    
8. **Correlation Heatmap**
<img width="864" height="535" alt="image" src="https://github.com/user-attachments/assets/cc782d35-a136-4c7e-af9c-37803eb96a85" />
    
9. **Pairwise Relationships (Pairplot)**
<img width="892" height="800" alt="image" src="https://github.com/user-attachments/assets/e6e40cfa-f7e7-4244-bb5f-4d7a95902b38" />

# Key Insights

-  **Females** had a significantly higher survival rate than males  
-  **1st class passengers** were more likely to survive than those in 2nd or 3rd class  
-  **Children** and younger passengers had slightly better survival rates  
-  Higher **fare** paid was positively associated with survival  
-  **Embarkation port** had a subtle impact on outcomes  
-  Medium-sized families (2–4) had higher survival odds
