<b>PROJECT OVERVIEW</b>

This project focuses on weather prediction using the Facebook Prophet algorithm, designed to automatically capture seasonality and trends for accurate forecasts.

<b>Project Steps:</b>

The project entails several key steps:

<b>1. Load and Clean Data:</b> Prepare the weather data by addressing missing values and outliers.

<b>2. Define Targets and Predictors:</b> Identify the target variable (e.g., temperature) and predictor variables (e.g., time, humidity) for modeling.

<b>3. Train Model:</b> Utilize the Prophet algorithm to build a predictive model based on identified trends and seasonality.

<b>4. Scale Model with Cross-Validation: </b>Enhance model accuracy by training on the entire dataset using cross-validation.

<b>5. Make Future Predictions: </b>Generate future weather predictions using the trained model.

<b>File Overview:</b>

The primary project files include the <b>Project Code.ipynb</b> notebook, containing the prediction code, and the <b>weather.csv</b> file, designated for dataset to be used.

Installing Required Libraries:

Before beginning, ensure you have the necessary libraries installed: <b>pandas, prophet, tqdm, plotly, scikit-learn.</b> You can install these libraries using the following commands:

<b>Install pandas: pip install pandas</b>
<b>Install prophet: pip install prophet</b>
<b>Install tqdm: pip install tqdm</b>
<b>Install plotly: pip install plotly</b>
<b>Install scikit-learn: pip install scikit-learn</b>

<b>Alternative Dataset:</b>

If you prefer a different dataset, consider accessing weather data from sources such as <b>NOAA</b> or <b>NASA POWER Data Access Viewer.</b> By substituting the provided data, you can tailor the project to your chosen dataset. Adjust the data loading and cleaning steps in the code to accommodate the structure and format of your new data.

This project offers flexibility in utilizing diverse weather datasets while leveraging the predictive power of the Facebook Prophet algorithm.
