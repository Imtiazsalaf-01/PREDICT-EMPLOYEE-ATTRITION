# 🧠 Predict Employee Attrition  
### *(This project was developed as **Week 3 Internship Project** for **WeIntern**)*

A machine learning project that analyzes HR data to **predict which employees are likely to leave the company**.  
This project includes data preprocessing, feature selection, model building, and feature-importance visualization.

---

## 📌 Project Description
This project focuses on building a predictive model for **employee attrition** using historical HR data.  
By applying machine learning techniques, the goal is to help organizations identify high-risk employees and take preventive actions.

---

## 🎯 Objectives
- Perform feature selection and preprocessing  
- Apply encoding techniques for categorical features  
- Train models using **Decision Tree** and **Random Forest Classifier**  
- Evaluate model performance  
- Visualize feature importance for insights  
- Build a clean, reproducible machine learning workflow  

---

## 🛠 Tech Stack
- **Python**
- **Pandas**
- **Scikit-learn**
- **Matplotlib/Seaborn**
- **Jupyter Notebook**

---

## 📂 Workflow
1. Import and explore HR dataset  
2. Handle missing values  
3. Encode categorical features  
4. Perform feature selection  
5. Split data into training and testing sets  
6. Train Decision Tree & Random Forest classifiers  
7. Evaluate using accuracy, confusion matrix, classification report  
8. Plot and interpret feature importance  

---

## 📊 Visualizations
- Feature importance bar charts  
- Correlation heatmap  
- Attrition distribution  

---

## 📁 Project Structure
```
├── data/
│   └── hr_data.csv
├── notebooks/
│   └── employee_attrition.ipynb
├── src/
│   ├── preprocess.py
│   ├── model_training.py
│   └── feature_importance.py
└── README.md
```

---

## ▶️ How to Run
```bash
# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook
```

---

## 📈 Expected Output
- Accuracy score of trained models  
- Confusion matrix for performance comparison  
- Ranked feature importance chart  
- Insights on which factors most strongly influence attrition  

---

## 🧩 Example Features Used
- Age  
- JobRole  
- MonthlyIncome  
- Overtime  
- JobSatisfaction  
- TotalWorkingYears  
- YearsAtCompany  
- MaritalStatus  
- Education  

---

## 🏁 Conclusion
This project provides a complete workflow for predicting employee attrition using machine learning.  
The insights generated can assist HR departments in designing better retention strategies.

---

## 🤝 Contributions
Feel free to fork this repository and submit pull requests for improvements!

---

## 📜 License
This project is released under the MIT License.
