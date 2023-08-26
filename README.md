*PROJECT OVERVIEW*

This project focuses on weather prediction using the Facebook Prophet algorithm, designed to automatically capture seasonality and trends for accurate forecasts.

Project Steps:

The project entails several key steps:

1. Load and Clean Data: Prepare the weather data by addressing missing values and outliers.

2. Define Targets and Predictors: Identify the target variable (e.g., temperature) and predictor variables (e.g., time, humidity) for modeling.

3. Train Model: Utilize the Prophet algorithm to build a predictive model based on identified trends and seasonality.

4. Scale Model with Cross-Validation: Enhance model accuracy by training on the entire dataset using cross-validation.

5. Make Future Predictions: Generate future weather predictions using the trained model.

File Overview:

The primary project files include the Project Code.ipynb notebook, containing the prediction code, and the Data/ directory, designated for data storage.

Installing Required Libraries:

Before beginning, ensure you have the necessary libraries installed: pandas, prophet, tqdm, plotly, scikit-learn. You can install these libraries using the following commands:

Install pandas: pip install pandas
Install prophet: pip install prophet
Install tqdm: pip install tqdm
Install plotly: pip install plotly
Install scikit-learn: pip install scikit-learn
Alternative Dataset:

If you prefer a different dataset, consider accessing weather data from sources such as NOAA or NASA POWER Data Access Viewer. By substituting the provided data, you can tailor the project to your chosen dataset. Adjust the data loading and cleaning steps in the code to accommodate the structure and format of your new data.

This project offers flexibility in utilizing diverse weather datasets while leveraging the predictive power of the Facebook Prophet algorithm.
