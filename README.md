# Heart Disease Prediction

## Project Overview
The **Heart Disease Prediction** project aims to build a predictive model that can classify whether an individual is at risk of heart disease based on various health parameters. The project involves **exploratory data analysis (EDA)** and **machine learning model building** to enhance prediction accuracy.

## Dataset Description
The dataset consists of several health-related features, including:
- **Age**: The age of the patient.
- **Gender**: Male or Female.
- **Chest Pain Type (CP)**: Types of chest pain experienced.
- **Resting Blood Pressure (Trestbps)**: The patient’s resting blood pressure in mm Hg.
- **Cholesterol (Chol)**: Serum cholesterol levels in mg/dl.
- **Fasting Blood Sugar (FBS)**: Whether fasting blood sugar is greater than 120 mg/dl.
- **Resting ECG (RestECG)**: Results of resting electrocardiographic measurements.
- **Maximum Heart Rate Achieved (Thalach)**: The highest heart rate reached during exercise.
- **Exercise-Induced Angina (Exang)**: Indicates whether the patient experienced exercise-induced angina.
- **Oldpeak**: ST depression induced by exercise relative to rest.
- **Slope**: The slope of the peak exercise ST segment.
- **Number of Major Vessels (Ca)**: Number of major vessels colored by fluoroscopy.
- **Thalassemia (Thal)**: A blood disorder affecting oxygen transport.
- **Target Variable**: Indicates the presence (1) or absence (0) of heart disease.

## Analysis Conducted
1. **Data Preprocessing**:
   - Handling missing values and data inconsistencies.
   - Encoding categorical variables.
   - Feature scaling using normalization techniques.
2. **Exploratory Data Analysis (EDA)**:
   - Distribution analysis of key health metrics.
   - Correlation heatmaps to identify significant predictors.
   - Visualizations like histograms, box plots, and bar charts for insights.
3. **Machine Learning Model Development**:
   - **Logistic Regression**: Baseline classification model.
   - **Random Forest Classifier**: Improved accuracy using ensemble learning.
   - **K-Nearest Neighbors (KNN)**: Distance-based classification.
   - **Support Vector Machine (SVM)**: Effective in high-dimensional spaces.
   - **Model Evaluation**: Comparing accuracy, precision, recall, and F1-score.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: pandas, NumPy, scikit-learn, Matplotlib, Seaborn
- **Visualization**: Histograms, correlation heatmaps, box plots
- **Machine Learning Models**: Logistic Regression, Random Forest, KNN, SVM

## Key Insights
- Higher cholesterol and blood pressure levels are strongly correlated with heart disease.
- Individuals with exercise-induced angina and high ST depression are at higher risk.
- Random Forest achieved the best accuracy among tested models.
- Proper feature selection and scaling improved model performance.

## Future Enhancements
- Expanding the dataset with more diverse demographics for better generalization.
- Implementing **deep learning models** for more accurate predictions.
- Integrating a **real-time prediction dashboard** for healthcare applications.

## How to Use the Project
1. Load the dataset into **Jupyter Notebook**.
2. Execute data preprocessing scripts to clean and prepare data.
3. Train machine learning models and evaluate their performance.

