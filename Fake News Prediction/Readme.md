# 🎯 **Fake News Prediction Model**  
Classify news articles as **real** or **fake** using machine learning.

---

## 📝 **Problem Statement**  
The spread of fake news has significant social and political implications. This project aims to classify news articles as **real** or **fake** using a **Logistic Regression Model**, achieving a test accuracy of **97.9%**.

---

## 📂 **Dataset**  
- **Source**: [Kaggle - Fake News Dataset](https://www.kaggle.com/c/fake-news/data)  
- **Description**:  
  - **Features**:  
    - `Title`: The headline of the news article.  
    - `Text`: The main content of the news article.  
    - `Author`: The author of the news article.  
  - **Target**: `Label`  
    - `1`: Fake News  
    - `0`: Real News  

---

## 🛠️ **Technologies Used**  
- **Programming Language**: Python  
- **Libraries**:  
  - `pandas` - Data manipulation  
  - `numpy` - Numerical computations  
  - `matplotlib` & `seaborn` - Data visualization  
  - `scikit-learn` - Machine learning implementation  
  - `nltk` - Natural language processing  

---

## 🔍 **Project Workflow**  
1. **Data Preprocessing**:  
   - Load the dataset and inspect its structure.  
   - Handle missing values by imputing or dropping them.  
   - Clean the text data (remove stopwords, punctuation, and perform stemming).  
   - Convert text into numerical format using **TF-IDF Vectorization**.  

2. **Exploratory Data Analysis (EDA)**:  
   - Analyze the distribution of labels (`real` vs. `fake`).  
   - Visualize common words in fake and real news articles using word clouds.  

3. **Model Building**:  
   - Split the dataset into training and testing sets.  
   - Train a **Logistic Regression Model** on the training data.  
   - Evaluate model performance using metrics like **accuracy, precision, recall, and F1-score**.  

4. **Prediction**:  
   - Test the model with unseen data.  
   - Predict whether a news article is real or fake.  

---

## 📊 **Results**  
- **Model Used**: Logistic Regression  
- **Accuracy**: 97.9% on test data  

---

## 🌐 **Run on Google Colab**  
You can run this project directly on Google Colab without setting up anything locally.  

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1QLbx1sARhmmf47rzr2e2bymQJsjVMJiz?usp=sharing)

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
- Experiment with advanced machine learning models like **SVM** or **XGBoost**.  
- Incorporate pre-trained deep learning models such as **BERT** for better text understanding.  
- Perform hyperparameter tuning to optimize the Logistic Regression model.  

---

## 📚 **References**  
- [Scikit-learn Documentation](https://scikit-learn.org/)  
- [Natural Language Toolkit (nltk)](https://www.nltk.org/)  
- [Kaggle Fake News Dataset](https://www.kaggle.com/c/fake-news/data)  
