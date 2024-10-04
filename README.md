# Algerian-Forest-Fire-Prediction

This project focuses on predicting forest fires in Algeria using machine learning techniques, specifically analyzing the Fire Weather Index (FWI) dataset. The primary objective is to build a predictive model that can assess the likelihood of forest fires based on various weather conditions.sing Logistic Regression, I applied cross-validation and hyperparameter tuning to assess performance. After developing the model, I saved it as pickle files and tested it on unseen data for validation.


# Dataset
The dataset used in this project contains data related to forest fires in Algeria, specifically from two regions: Bejaia and Sidi-Bel Abbes. It includes several weather-related variables that influence fire occurrences, such as:

Temperature (°C)
Relative Humidity (%)
Wind Speed (km/h)
Rain (mm)
Fine Fuel Moisture Code (FFMC)
Duff Moisture Code (DMC)
Drought Code (DC)
Initial Spread Index (ISI)
Fire Weather Index (FWI)
Classes: Fire/No Fire
# Project Workflow
**1. Data Preprocessing**
Cleaning: Handling missing values, outliers, and formatting issues.
Exploratory Data Analysis (EDA): Generated visualizations to gain insights into the dataset's features and distribution.
Feature Engineering: Normalizing and transforming features for better model performance.
**2. Modeling**
The project uses Logistic Regression to classify whether a fire will occur based on the provided weather conditions.
Cross-validation and Hyperparameter Tuning were performed to evaluate and optimize model performance.
**3. Evaluation**
The model was evaluated using standard metrics like accuracy, precision, recall, and F1-score.
Cross-validation was employed to validate the model’s robustness.
Results were compared across different hyperparameter settings to determine the best configuration.
**4. Deployment**
The trained model was saved as a pickle file for future use.
It was tested on unseen data to ensure generalization and accuracy.
**Insights Derived**
- Temperature and FWI: A positive correlation between higher temperatures and fire occurrences.
- Wind and Fire Spread: Wind speed was found to significantly influence fire spread.
- Seasonality: Most fires occurred in the dry summer months, highlighting the critical role of seasonal weather patterns.
**Tools and Libraries Used**
Python
Pandas for data manipulation
Matplotlib and Seaborn for visualizations
Scikit-learn for modeling and evaluation
Logistic Regression as the classification model
Pickle for model serialization
Cross-validation for model robustness assessment


# Conclusion
This project demonstrates the use of logistic regression in predicting forest fires based on weather data. The findings emphasize the importance of weather patterns in fire management, providing insights that could help in preventing and mitigating forest fires.

# Future Improvements
- Experiment with other classification models such as Random Forest, SVM, and Neural Networks to improve performance.
- Implement additional feature engineering techniques.
- Deploy the model in a real-time environment for dynamic prediction.
