# Prediction-of-Cardiovascular-Disease-and-Stroke
This project aimed to predict cardiovascular disease (CVD) and stroke using two datasets from Kaggle: the Cardiovascular Disease dataset and the Stroke Prediction dataset.

### Team Members:
- Arisara (Pie) Vichitchoti  
- Jiayue (Amaris) Han  
- Yitian (Aaron) Liang  
- Zhaolin (Helen) Li  

### Institution & Course:
- **Northeastern University**, Boston, MA  
- **Data Science 3000** (Instructor: Professor Sophine Clachar)

### Objectives:
- Predict the probability of cardiovascular disease and stroke based on patient health indicators.
- Analyze correlations between various health factors (e.g., age, glucose levels, blood pressure, cholesterol, hypertension) and disease presence.

### Data Sources:
- **Cardiovascular Disease Dataset** (7,000 samples, 13 features) from Kaggle
- **Stroke Prediction Dataset** (5,110 samples, 12 features) from Kaggle

### Methodology:
The project was divided into three phases:

**1. Data Preprocessing and Exploratory Data Analysis (EDA)**
- Cleaned data by removing missing entries and correcting data types.
- Categorized blood pressure levels.
- Analyzed correlations between risk factors and diseases using visualizations.

**2. Model Building and Training**
The following machine learning models were implemented:

**For Cardiovascular Disease (CVD) Prediction:**
- **Random Forest Classifier (RFC)**
  - Accuracy: ~65%
- **Random Forest Regression (RFR)**
  - Mean Squared Error (MSE): 0.226
- **K-fold Cross-Validation**
  - Accuracy: ~65% (with minimal variance)

**For Stroke Prediction:**
- **Random Forest Classifier (RFC)**
  - Accuracy: ~72%
- **Random Forest Regression (RFR)**
  - Mean Squared Error (MSE): 0.183
- **K-fold Cross-Validation**
  - Accuracy: ~70%
- **Support Vector Machine (SVM) with Hyperparameter Tuning**
  - Accuracy improved from 76.1% to 77.5% after tuning

**3. Model Evaluation**
- Used accuracy, F1-score, precision, recall, and MSE metrics to evaluate models.

### Key Findings:
- **Age** was the most significant factor for both cardiovascular diseases and stroke.
- **Glucose levels** and **blood pressure** significantly impacted stroke prediction.
- Gender differences were minimal for CVD but significant for stroke, with females showing higher stroke prevalence.
