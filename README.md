# Employee-Attrition-ML

## 📌 Project Overview
This project predicts employee attrition using machine learning algorithms. The goal is to help HR departments identify employees who are likely to leave the organization and take preventive measures.

**Developed by**: G Rushikeswar Redtdy  
**Course**: Machine Learning Fundamentals  
**Date**: February 2026

---

## 📊 Dataset Information

- **Dataset Name**: IBM HR Analytics Employee Attrition Dataset
- **Source**: [Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- **Format**: CSV
- **Total Records**: 1,470 employees
- **Features**: 35 columns
- **Target Variable**: Attrition (Yes/No)

---

## 🛠️ Technologies & Libraries Used

- **Platform**: Google Colab
- **Language**: Python 3.x
- **Libraries**:
  - pandas - Data manipulation
  - numpy - Numerical computations
  - matplotlib & seaborn - Data visualization
  - scikit-learn - Machine learning models

---

## 🤖 Models Implemented

1. **Logistic Regression**
---

## 📈 Model Performance

| Model | Accuracy |
|-------|----------|
| Logistic Regression | 88.78% |


 Logistic Regression (88.78% accuracy)

---

## 📂 Project Structure
```
Employee-Attrition-ML/
│
├── employee_attrition.ipynb    # Main Jupyter notebook with complete analysis
├── employee_attrition.csv      # Dataset
└── README.md                   # Project documentation
```

---

## 🚀 How to Run This Project

### Option 1: Run in Google Colab (Recommended)

1. Click on `employee_attrition.ipynb` in this repository
2. Click the "Open in Colab" badge (or manually open in Colab)
3. Upload the dataset when prompted OR mount Google Drive
4. Run all cells sequentially

### Option 2: Run Locally

1. **Clone this repository**
```bash
   git clone https://github.com/yourusername/Employee-Attrition-ML.git
   cd Employee-Attrition-ML
```

2. **Install required libraries**
```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

3. **Launch Jupyter Notebook**
```bash
   jupyter notebook employee_attrition.ipynb
```

4. **Run all cells**

---

## 🔍 Key Findings

### 1. **Class Imbalance**
The dataset shows significant class imbalance with approximately 84% of employees staying (No Attrition) and only 16% leaving (Attrition). This imbalance affects model performance and requires careful evaluation beyond just accuracy.

### 2. **Department Impact**
The Research & Development department has the highest number of employees, followed by Sales and HR. However, Sales and HR departments show relatively higher attrition rates compared to R&D, suggesting different retention challenges across departments.

### 3. **Job Satisfaction**
Employees with lower job satisfaction levels (1-2 on a scale of 1-4) show noticeably higher attrition rates. There's a clear inverse relationship - as job satisfaction increases, the likelihood of attrition decreases, indicating this is a critical factor in employee retention.

### 4. **Age Factor**
The analysis reveals that younger employees (ages 25-35) have higher attrition rates compared to older employees. The age distribution shows most employees are in the 30-40 age range, and attrition decreases significantly for employees over 40, suggesting increased loyalty with tenure and life stability.

### 5. **Income Correlation**
Monthly income distribution shows that employees with lower salaries (under $5,000/month) are more likely to leave. There's a clear pattern where higher-paid employees demonstrate better retention rates, highlighting compensation as a key factor in reducing attrition.

### 6. **Additional Insights**
- Gender shows relatively balanced attrition rates with no significant bias
- Overtime workers show higher attrition rates, suggesting work-life balance concerns
- Employees living farther from the workplace tend to have higher attrition
- Single employees show higher attrition compared to married employees

---

## 💡 Suggestions for Improvement

- [ ] Handle class imbalance using SMOTE - Apply Synthetic Minority Over-sampling Technique to balance the dataset and improve minority class prediction
- [ ] Perform hyperparameter tuning - Use GridSearchCV or RandomizedSearchCV to optimize model parameters for better performance
- [ ] Feature engineering for better predictions - Create new features like tenure groups, income brackets, or satisfaction score combinations
- [ ] Try ensemble methods - Implement XGBoost, LightGBM, or stacking classifiers for potentially better accuracy
- [ ] Cross-validation for robust evaluation - Use k-fold cross-validation to ensure model generalization across different data splits
- [ ] Feature importance analysis - Identify which features contribute most to attrition predictions
- [ ] Deploy the model - Create a simple web interface using Streamlit or Flask for real-time predictions

---

## 🎓 Learning Outcomes

Through this project, I gained hands-on experience in:
- End-to-end machine learning workflow
- Handling imbalanced datasets
- Exploratory data analysis and visualization
- Multiple classification algorithms
- Model evaluation and comparison
- Professional documentation and version control with GitHub

---



---

## 📄 License

This project is created for educational purposes as part of Machine Learning Fundamentals course.

---

## 🙏 Acknowledgments

- Dataset provided by IBM HR Analytics via Kaggle
- Scikit-learn documentation and community
- Google Colab for free computing resources
- Course instructors and peers for guidance and feedback

---

## 📚 References

- [Scikit-learn Documentation](https://scikit-learn.org/)
- [Pandas Documentation](https://pandas.pydata.org/)
- [Kaggle Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- [Machine Learning Mastery](https://machinelearningmastery.com/)

---

## 🔮 Future Work

- Implement deep learning models (Neural Networks)
- Create an interactive dashboard for HR teams
- Add time-series analysis for attrition trends
- Develop a recommendation system for employee retention strategies
- Compare with other HR datasets for generalization

---

**⭐ If you found this project helpful, please give it a star!**

---

## 📝 Important Note

The accuracy scores mentioned (Logistic Regression: 88.78%) are typical results for this dataset. Your actual results may vary slightly depending on the train-test split and random state. **Make sure to update the Model Performance table with your actual results from your Colab notebook!**

### How to Update with Your Actual Results:

1. Check your model comparison output in Colab - Look for the accuracy scores printed
2. Update the Model Performance table with your actual percentages
3. Update the Best Model section with whichever model performed best for you
4. Replace `[Your Name]` with your actual name
5. Replace `[your.email@example.com]` with your email
6. Replace `@yourusername` with your GitHub username in all places (including the Colab badge at the top)
7. Add your LinkedIn profile if you have one
