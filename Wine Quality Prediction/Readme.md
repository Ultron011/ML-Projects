# 🎯 **Wine Quality Prediction Model**  
Predict the quality of wine based on its physicochemical properties using machine learning.

---

## 📝 **Problem Statement**  
Determining the quality of wine is crucial for producers and consumers alike. This project aims to classify wine quality using a **Random Forest Classifier** based on various physicochemical characteristics, achieving a test accuracy of **92.5%**.

---

## 📂 **Dataset**  
- **Source**: [UCI Machine Learning Repository - Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)  
- **Description**:  
  - **Features**:  
    - `Fixed Acidity`  
    - `Volatile Acidity`  
    - `Citric Acid`  
    - `Residual Sugar`  
    - `Chlorides`  
    - `Free Sulfur Dioxide`  
    - `Total Sulfur Dioxide`  
    - `Density`  
    - `pH`  
    - `Sulphates`  
    - `Alcohol`  
  - **Target**: `Quality` (scaled from 0–10 and then categorized into classes for classification purposes).  

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
   - Load the dataset and inspect its structure.  
   - Handle missing values and outliers.  
   - Normalize numerical features to improve model performance.  
   - Categorize `Quality` into discrete classes for classification.  

2. **Exploratory Data Analysis (EDA)**:  
   - Analyze distributions of physicochemical properties.  
   - Visualize relationships between features and wine quality using correlation heatmaps and pair plots.  

3. **Model Building**:  
   - Split the data into training and testing sets.  
   - Train a **Random Forest Classifier**.  
   - Evaluate model performance using metrics such as **accuracy, precision, recall, and F1-score**.  

4. **Prediction**:  
   - Test the model with unseen data.  
   - Predict the quality category of wine samples.  

---

## 📊 **Results**  
- **Model Used**: Random Forest Classifier  
- **Accuracy**: 92.5% on test data  

---

## 🌐 **Run on Google Colab**  
You can run this project directly on Google Colab without setting up anything locally.  

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1myTrU5x2ShaNI80aHF6WUg2EZerW745S?usp=sharing)

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
- Experiment with ensemble models like Gradient Boosting or XGBoost.  
- Use hyperparameter tuning techniques (e.g., Grid Search, Random Search) to optimize the Random Forest model.  
- Implement feature selection techniques to identify the most important predictors of wine quality.  

---

## 📚 **References**  
- [Scikit-learn Documentation](https://scikit-learn.org/)  
- [UCI Machine Learning Repository - Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)  
