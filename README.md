# Loan Status Prediction using Machine Learning

A Machine Learning project that predicts whether a loan application will be **Approved** or **Rejected** based on applicant details such as income, education, credit history, marital status, and loan amount.

This project demonstrates the complete ML workflow including:

- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Encoding
- Model Training
- Model Evaluation
- Loan Status Prediction

---

# 📌 Problem Statement

Financial institutions receive thousands of loan applications daily.  
Manually checking every application is time-consuming and inefficient.

The goal of this project is to build a Machine Learning model that can predict loan approval status automatically using applicant information.

---

# 📂 Dataset Information

The dataset contains information about loan applicants including:

| Feature | Description |
|---|---|
| Gender | Male/Female |
| Married | Marital Status |
| Dependents | Number of Dependents |
| Education | Graduate/Not Graduate |
| Self_Employed | Self-employed or not |
| ApplicantIncome | Applicant income |
| CoapplicantIncome | Co-applicant income |
| LoanAmount | Loan amount |
| Loan_Amount_Term | Loan term |
| Credit_History | Credit history record |
| Property_Area | Urban/Semiurban/Rural |
| Loan_Status | Approved or Rejected |

---

# ⚙️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 📊 Project Workflow

## 1️⃣ Data Collection
- Imported dataset using Pandas
- Checked dataset shape and columns

## 2️⃣ Data Cleaning
- Handled missing values
- Removed unnecessary data issues

## 3️⃣ Data Preprocessing
- Converted categorical values into numerical format
- Applied Label Encoding

## 4️⃣ Exploratory Data Analysis (EDA)
- Visualized:
  - Loan approval distribution
  - Income patterns
  - Credit history impact
  - Property area analysis

## 5️⃣ Model Building
Machine Learning algorithms used:
- Support Vector Machine (SVM)

## 6️⃣ Model Evaluation
- Accuracy Score
- Training Accuracy
- Testing Accuracy

---

# 🧠 Machine Learning Model

The project mainly uses:

## Support Vector Machine (SVM)

SVM is a supervised machine learning algorithm used for classification problems.  
It works by finding the optimal hyperplane that separates data into different classes.

### Why SVM?
- Good accuracy
- Effective for classification
- Works well on medium-sized datasets

---

# 📈 Results

- Successfully trained a loan prediction model
- Achieved good prediction accuracy on test data
- Predicted whether a loan should be approved or rejected

---

# 🚀 How to Run the Project

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/shivamdwivedicse/Loan_status_project_ML.git
```

## 2️⃣ Navigate to Project Folder

```bash
cd Loan_status_project_ML
```

## 3️⃣ Install Required Libraries

```bash
pip install -r requirements.txt
```

## 4️⃣ Open Jupyter Notebook

```bash
jupyter notebook
```

## 5️⃣ Run the Notebook

Open:

```bash
loan_status_project.ipynb
```

and run all cells.

---

# 📌 Future Improvements

- Add multiple ML algorithms comparison
- Hyperparameter tuning
- Deploy using Streamlit or Flask
- Improve accuracy using feature engineering
- Add real-time prediction UI

---

# 📷 Project Highlights

✅ Data Cleaning  
✅ Data Visualization  
✅ Feature Engineering  
✅ Machine Learning Model  
✅ Loan Prediction System  

---

# 🤝 Contributing

Contributions are welcome.

If you'd like to improve this project:

1. Fork the repository  
2. Create a new branch  
3. Make changes  
4. Submit a Pull Request  

---

# 📜 License

This project is open-source and available under the MIT License.

---

# 👨‍💻 Author

## Shivam Dwivedi

- GitHub: https://github.com/shivamdwivedicse
- LinkedIn: https://www.linkedin.com/in/shivam-dwivedi-27661a395

Project Link:  
https://github.com/shivamdwivedicse/Loan_status_project_ML
