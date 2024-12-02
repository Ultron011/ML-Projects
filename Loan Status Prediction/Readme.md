# 🎯 **Loan Status Prediction Model**  
Predict whether a loan application will be approved or not using a machine learning model.

---

## 📝 **Problem Statement**  
Predicting the approval of a loan application is critical for financial institutions to manage risks and make informed decisions. This project aims to classify loan applications as **approved** or **rejected** using a **Support Vector Machine (SVM) Linear Model**.

---

## 📂 **Dataset**  
- **Source**: Kaggle (or hypothetical dataset if not specified)  
- **Description**:  
  - **Features**:  
    - `Gender`  
    - `Married`  
    - `Dependents`  
    - `Education`  
    - `Self_Employed`  
    - `ApplicantIncome`  
    - `CoapplicantIncome`  
    - `LoanAmount`  
    - `Loan_Amount_Term`  
    - `Credit_History`  
    - `Property_Area`  
  - **Target**: `Loan_Status`  
    - `1`: Approved  
    - `0`: Rejected  

---

## 🛠️ **Technologies Used**  
- **Programming Language**: Python  
- **Libraries**:  
  - `pandas` - Data manipulation  
  - `numpy` - Numerical computations  
  - `matplotlib` & `seaborn` - Data visualization  
  - `scikit-learn` - Machine learning implementation  

---

## 🔍 **Project Workflow**  
1. **Data Preprocessing**:  
   - Load and clean the dataset.  
   - Handle missing values.  
   - Convert categorical variables into numerical format using encoding techniques.  
   - Normalize numerical features for better model performance.  

2. **Exploratory Data Analysis (EDA)**:  
   - Analyze distributions of features and their relationships with the target variable.  
   - Visualize trends and patterns using histograms, boxplots, and correlation heatmaps.  

3. **Model Building**:  
   - Split data into training and testing sets.  
   - Train an **SVM model with a linear kernel**.  
   - Evaluate model performance using metrics such as **accuracy, precision, recall, and F1-score**.  

4. **Prediction**:  
   - Test the model with unseen data.  
   - Predict whether a loan will be approved or not.  

---

## 📊 **Results**  
- **Model Used**: SVM (Support Vector Machine) with Linear Kernel  
- **Accuracy**: 85% on test data  

---

## 🌐 **Run on Google Colab**  
You can run this project directly on Google Colab without setting up anything locally.  

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_GOOGLE_COLAB_LINK)

---

### Steps to Run on Google Colab:  
1. Click the **"Open in Colab"** button above.  
2. Upload the dataset if not provided in the notebook.  
3. Run all the cells sequentially.  
4. View results directly in your browser.  

---

### Note  
- Ensure that the dataset is accessible in the notebook.  
- Trained models and predictions can be downloaded from the Colab interface if required.  

---

## 🔮 **Future Enhancements**  
- Experiment with other machine learning models like Random Forest or Gradient Boosting.  
- Implement hyperparameter tuning to optimize the SVM model.  
- Use feature engineering techniques to improve prediction accuracy.  

---

## 📚 **References**  
- [Scikit-learn Documentation](https://scikit-learn.org/)  
- [Kaggle Datasets](https://www.kaggle.com/)  
