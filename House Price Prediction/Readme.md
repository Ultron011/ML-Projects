# 🏡 **House Price Prediction**  
Predict house prices in California using machine learning.

---

## 📝 **Problem Statement**  
Accurately predicting house prices is essential for real estate analysis, investment decisions, and policy-making. This project leverages machine learning to predict house prices based on various factors using the California House Prices dataset.

---

## 📂 **Dataset**  
- **Source**: [Scikit-learn California Housing Dataset](https://scikit-learn.org/stable/datasets/real_world.html#california-housing-dataset)  
- **Description**:
  - **20,640 samples**: Representing California districts.
  - **8 features**: Including median income, housing age, and average occupancy.  
  - **Target**: Median house price in each district.

---

## 🛠️ **Technologies Used**  
- **Programming Language**: Python  
- **Libraries**:
  - `pandas` - Data manipulation  
  - `numpy` - Numerical computations  
  - `matplotlib` & `seaborn` - Data visualization  
  - `scikit-learn` - Preprocessing and evaluation  
  - `xgboost` - Extreme Gradient Boosting for regression  

---

## 🔍 **Project Workflow**  
1. **Data Preprocessing**:
   - Loaded and split the dataset into features (X) and target (y).
   - Checked data for missing values and outliers.
   - Standardized features using `StandardScaler` to ensure consistent scaling.  

2. **Exploratory Data Analysis (EDA)**:
   - Analyzed feature distributions and correlations.
   - Visualized relationships between features and target using scatter plots and heatmaps.  

3. **Model Building**:
   - Split the data into training and testing sets (80/20 split).
   - Trained an `XGBRegressor` model to predict house prices.
   - Tuned hyperparameters for optimal performance.  

4. **Model Evaluation**:
   - Evaluated the model using metrics like Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² score.  

5. **Prediction**:
   - Predicted house prices for test data and validated against actual prices.

---

## 📊 **Results**  
- **Model Used**: XGBRegressor  
- **Performance Metrics**:
  - **Mean Absolute Error (MAE)**: ~\$30,000  
  - **Root Mean Squared Error (RMSE)**: ~\$50,000  
  - **R² Score**: 0.85  

---

## 🌐 **Run on Google Colab**
You can run this project directly on Google Colab without setting up anything locally.  

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1rR5z7ecAcno7e_hPv9K6TGo9iPaxPgBp?usp=sharing)

---

### Steps to Run on Google Colab:
1. Click the **"Open in Colab"** button above.
2. Upload the required dataset (if not already provided in the notebook).
3. Run all the cells sequentially.
4. View the results directly in your browser!

---

### Note
- Ensure that the dataset is accessible within the notebook.
- You can download results or trained models from the Colab interface if needed.


## 🔮 **Future Enhancements**
- Experiment with other ML models.
- Optimize feature selection and hyperparameters.

---

## 📚 **References**
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Connectionist+Bench+%28Sonar%2C+Mines+vs.+Rocks%29)  
- [Scikit-learn Documentation](https://scikit-learn.org/)
