# 🎯 **Gold Price Prediction Model**  
Predict the price of gold based on various financial and economic indicators using machine learning.

---

## 📝 **Problem Statement**  
Gold price is influenced by numerous factors, including global economic trends, currency values, and market indices. This project aims to predict the price of gold using a **Random Forest Regressor** for better financial decision-making and investment strategies.

---

## 📂 **Dataset**  
- **Source**: [Kaggle - Gold Price Dataset](https://www.kaggle.com/)
- **Description**:  
  - **Features**:  
    - `SPX`: S&P 500 Index  
    - `USO`: Crude Oil Prices  
    - `SLV`: Silver Prices  
    - `EUR/USD`: Exchange Rate  
    - Other economic indicators  
  - **Target**: `Gold Price`  

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
   - Normalize or standardize numerical features for better model performance.  

2. **Exploratory Data Analysis (EDA)**:  
   - Analyze the relationships between features and gold price.  
   - Visualize trends using line plots, scatter plots, and heatmaps.  

3. **Model Building**:  
   - Split the data into training and testing sets.  
   - Train a **Random Forest Regressor** on the training data.  
   - Evaluate model performance using metrics like **R-squared, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE)**.  

4. **Prediction**:  
   - Test the model with unseen data.  
   - Predict the gold price for given financial indicators.  

---

## 📊 **Results**  
- **Model Used**: Random Forest Regressor  
- **Performance Metrics**:  
  - **R-squared**: 0.92  

---

## 🌐 **Run on Google Colab**  
You can run this project directly on Google Colab without setting up anything locally.  

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ZevnTC7nje3cYUC4o0DjN3T-cmLr5YHD?usp=sharing)

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
- Incorporate additional features such as geopolitical data or inflation rates for improved accuracy.  
- Perform hyperparameter tuning to optimize the Random Forest Regressor.  

---

## 📚 **References**  
- [Scikit-learn Documentation](https://scikit-learn.org/)  
- [Kaggle Gold Price Dataset](https://www.kaggle.com/)  
- [Investopedia - Gold Price Factors](https://www.investopedia.com/)  
