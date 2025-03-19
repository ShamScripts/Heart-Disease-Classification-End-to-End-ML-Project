# Heart Disease Classification - End-to-End Machine Learning Project

## Overview
This project builds an end-to-end machine learning pipeline to classify heart disease presence based on structured patient data. The dataset consists of various clinical features, and the model predicts whether a patient has heart disease.

## Dataset
The dataset used in this project is the **Heart Disease UCI dataset**, available on Kaggle or UCI Machine Learning Repository. It contains structured data about patients, including:
- Age
- Sex
- Chest Pain Type (cp)
- Resting Blood Pressure (trestbps)
- Cholesterol (chol)
- Fasting Blood Sugar (fbs)
- Resting Electrocardiographic Results (restecg)
- Maximum Heart Rate Achieved (thalach)
- Exercise-Induced Angina (exang)
- ST Depression Induced by Exercise (oldpeak)
- Slope of Peak Exercise ST Segment (slope)
- Number of Major Vessels Colored by Fluoroscopy (ca)
- Thalassemia (thal)

## Project Workflow
1. **Data Exploration and Preprocessing**
   - Load the dataset
   - Handle missing values
   - Encode categorical variables
   - Scale numerical features
   
2. **Exploratory Data Analysis (EDA)**
   - Visualizing data distributions
   - Correlation analysis
   - Feature importance analysis

3. **Model Selection and Training**
   - Train multiple models (Logistic Regression, Random Forest, SVM, etc.)
   - Perform hyperparameter tuning using GridSearchCV
   - Evaluate models based on accuracy, precision, recall, and F1-score

4. **Model Evaluation and Interpretation**
   - Generate classification reports and confusion matrices
   - Use ROC-AUC for model performance analysis

5. **Deployment (Optional)**
   - Save the trained model using `joblib` or `pickle`
   - Create a simple API using Flask or FastAPI for predictions

## Dependencies
To run this project, install the required Python libraries:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn joblib
```

## Running the Notebook
1. Clone this repository:
   ```bash
   git clone https://github.com/mrdbourke/zero-to-mastery-ml.git
   ```
2. Navigate to the project folder:
   ```bash
   cd zero-to-mastery-ml/section-3-structured-data-projects
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook end-to-end-heart-disease-classification.ipynb
   ```

## Results
The final model achieves **[accuracy score]**, with key metrics as follows:
- Precision: **[value]**
- Recall: **[value]**
- F1-score: **[value]**

## Future Improvements
- Implement feature selection techniques to improve model performance
- Try deep learning models for better accuracy
- Deploy the model as a web application

## Author
This project is based on the work by [Daniel Bourke](https://github.com/mrdbourke) from the Zero to Mastery Machine Learning course.

## License
This project follows the MIT License as per the original repository.

