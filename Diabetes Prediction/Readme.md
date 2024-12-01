# 🎯 **Diabetes Prediction**  
Predict whether a person has diabetes using a **Support Vector Machine (SVM)** with a linear kernel.

---

## 📝 **Problem Statement**
Diabetes is a chronic condition affecting millions worldwide. Early prediction can help in managing the disease effectively. This project aims to predict the likelihood of a person having diabetes based on health metrics using machine learning.

---

## 📂 **Dataset**
- **Source**: [Pima Indians Diabetes Database (Kaggle)](https://www.kaggle.com/uciml/pima-indians-diabetes-database)  
- **Description**:
  - **768 samples**: Each representing health records of individuals.
  - **8 features**: Including glucose level, BMI, age, etc.
  - **Labels**:  
    - `1`: Diabetes-positive  
    - `0`: Diabetes-negative  

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
   - Handle missing values (if any) and inspect data structure.
   - Normalize numerical features for consistent scaling.

2. **Exploratory Data Analysis (EDA)**:
   - Analyze distributions of features.
   - Identify correlations between features and the target variable.

3. **Model Building**:
   - Split the data into training and testing sets.
   - Train an SVM model with a linear kernel.
   - Evaluate performance using metrics like accuracy, precision, recall, and F1-score.

4. **Prediction**:
   - Test the model on unseen data.
   - Predict whether an individual is diabetes-positive or negative.

---

## 📊 **Results**
- **Model Used**: SVM with a linear kernel  
- **Accuracy**: Achieved **78%** accuracy on test data  

---

## 🌐 **Run on Google Colab**
You can run this project directly on Google Colab without setting up anything locally.  

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1N3UAbrdmAUFYd_1NspIo3RPGJPi1ituc?usp=sharing)

---

### Steps to Run on Google Colab:
1. Click the **"Open in Colab"** button above.
2. Upload the required dataset (if not already provided in the notebook).
3. Run all the cells sequentially.
4. View the results directly in your browser!

---

### Note
- Ensure the dataset is accessible within the notebook.
- Save trained models or results locally as needed.

---

## 🔮 **Future Enhancements**
- Experiment with different kernels and hyperparameters in SVM.
- Test other machine learning models like Random Forest or Neural Networks.
- Perform feature selection to improve model accuracy.

---

## 📚 **References**
- [Pima Indians Diabetes Dataset](https://www.kaggle.com/uciml/pima-indians-diabetes-database)  
- [Scikit-learn Documentation](https://scikit-learn.org/)
