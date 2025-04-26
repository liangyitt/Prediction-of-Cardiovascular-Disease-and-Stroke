# DS3000-Final-Project---Cardiovascular-Disease

### 1. Problem Statement and Objective:
The project aimed to predict the probability of cardiovascular diseases (CVD) and strokes by analyzing health data, particularly focusing on identifying significant risk factors. The motivation stemmed from recognizing CVD and stroke as major health burdens globally, with stroke notably being the third leading cause of death in the United States.

### 2. Data Source and Description:
- **Data Sources**: Two Kaggle datasets were used:
  - Cardiovascular Disease Dataset.
  - Stroke Prediction Dataset.
- **Data Features**: The datasets included health indices such as age, gender, height, weight, hypertension, cholesterol levels, BMI, average glucose levels, and lifestyle habits to assess their relationships with CVD and stroke occurrences.

### 3. Research Methods:
The project proceeded in three main phases:

- **Data Exploration and Cleaning (EDA)**:
  - Checked and cleaned data (removed invalid rows, converted age from days to years, ensured blood pressure was positive, and categorized blood pressure levels).
  - Visualized correlations between risk factors (age, weight, blood pressure, gender) and disease occurrences.

- **Model Development and Training**:
  - Employed several machine learning methods:
    - Random Forest Classifier (RFC)
    - Random Forest Regression (RFR)
    - K-fold Cross-Validation
    - Support Vector Machine (SVM), including hyperparameter tuning.
  - Important risk factors selected for modeling were age, hypertension, heart disease, glucose level, weight, cholesterol, and blood pressure levels.

### 4. Results and Evaluation:
- **Cardiovascular Disease Predictions**:
  - RFC achieved approximately 65% accuracy, with an F1-score of 0.65.
  - K-fold Cross-Validation also attained 65% accuracy.
  - RFR produced a mean squared error (MSE) of 0.226.
  - Top influential features were age, weight, and blood pressure levels.

- **Stroke Predictions**:
  - RFC accuracy reached approximately 72% with an F1-score of 0.72.
  - K-fold Cross-Validation achieved 70% accuracy.
  - RFR had a relatively low MSE of 0.183.
  - SVM model, after hyperparameter tuning, showed the highest accuracy at 77.5%, improved from an initial 76.1%.

### 5. Key Findings and Impacts:
- **Age** was consistently identified as the most influential risk factor for both CVD and stroke.
- **Glucose level** also emerged as crucial for stroke predictions.
- Gender differences were observed, indicating that females were slightly more susceptible to strokes.
- Developed clinical models demonstrated significant accuracy in identifying individuals at higher risk, potentially aiding preventive care and treatment.

### 6. Conclusions and Future Directions:
- Successfully identified significant health indices linked to CVD and stroke risks.
- The SVM model was notably effective for stroke prediction.
- Suggested future improvements include collecting larger, localized datasets from hospitals (e.g., Mass General Hospital) and developing an SVM model for CVD to enhance accuracy further.
