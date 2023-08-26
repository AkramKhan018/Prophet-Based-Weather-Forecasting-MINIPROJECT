
<b>Project Overview:</b>

This project aims to predict weather using the Facebook Prophet algorithm, which employs an additive model to forecast based on seasonal effects and trends. Prophet automatically identifies seasonality in weather data, making it advantageous for accurate predictions without extensive feature engineering. It's also suitable for scaling to multiple time series, such as data from adjacent weather stations.

<b>Project Steps:</b>

Load and Clean Data: Prepare the weather data for analysis by handling missing values and outliers.

Define Targets and Predictors: Identify the target variable (e.g., temperature) and predictor variables (e.g., time, humidity) for modeling.

Train Model: Utilize the Prophet algorithm to build a predictive model based on identified trends and seasonality.

Scale Model with Cross-Validation: Validate and refine the model's accuracy by training it on the entire dataset using cross-validation.

Make Future Predictions: Generate weather predictions for future time periods using the trained model.

<b>File Overview:</b>

<ul><li>Project Code.ipynb</li>: Jupyter notebook containing code for weather prediction using the Prophet algorithm.
<li>weather.csv</li>: Excel File containing the necessary data for analysis.</ul>

<b>Installing Required Libraries:</b>

To set up your environment, install the following libraries using the provided commands:

Install pandas: pip install pandas
Install prophet: pip install prophet
Install tqdm: pip install tqdm
Install plotly: pip install plotly
Install scikit-learn: pip install scikit-learn

<b>Note:</b>

If you prefer to use a different dataset for your weather predictions, you have the option to access data from sources like NOAA or NASA POWER Data Access Viewer. These platforms provide a wide range of weather-related datasets that you can utilize for your project.

To obtain your required dataset:

NOAA (National Oceanic and Atmospheric Administration):
Visit the NOAA website and explore their available datasets. You can find historical weather data from various weather stations. Follow the data download instructions provided on their website.

NASA POWER Data Access Viewer:
Access the NASA POWER Data Access Viewer, which offers various meteorological and solar energy data. You can select your location and time period of interest to obtain the relevant dataset. Follow the provided instructions to download the data.

Once you have acquired your desired dataset from either of these sources, you can proceed with the rest of the project using the same steps mentioned earlier. Simply replace the provided data files with your newly obtained dataset to conduct weather predictions using the Facebook Prophet algorithm. Make sure to format and preprocess the new dataset as needed before feeding it into the project's code.

Remember to adjust the data loading and cleaning steps in the code to accommodate the structure and format of your new dataset.

This project offers flexibility in utilizing diverse weather datasets while leveraging the predictive power of the Facebook Prophet algorithm.

