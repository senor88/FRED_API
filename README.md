## Description

The **S&P 500 and CPI Analysis with FRED API** project demonstrates how to access, process, and visualize economic data from the FRED API. The project focuses on the S&P 500 index and CPI, two critical indicators for financial and economic analysis. Key steps in the project include:

- Retrieving **S&P 500** and **CPI** data from the FRED API.
- Cleaning and preparing the data for analysis.
- Visualizing the historical trends of both indicators.
- Using **Prophet** to forecast future values of the S&P 500 index and CPI.

This project is ideal for anyone interested in financial market analysis, inflation prediction, and the application of time-series forecasting techniques. It offers a foundation for building more advanced tools for economic prediction and financial decision-making.


# Key Features

- **Data Retrieval**: Fetches both S&P 500 and CPI data directly from the FRED API.
- **Data Preprocessing**: Cleans and prepares the data by handling missing values and resampling the data into monthly intervals.
- **Time-Series Visualization**: Visualizes the historical trends of the S&P 500 and CPI indices using `matplotlib`.
- **Forecasting**: Implements the **Prophet model** to forecast future values of the S&P 500 index and CPI.
- **Modular Code**: The code structure is flexible and easy to extend for additional economic indicators or forecasting models.


## Technologies Used

- **Python**: The primary programming language used for data analysis and forecasting.
- **FRED API**: Provides access to economic data, including the S&P 500 index and CPI.
- **pandas**: For data manipulation, cleaning, and preprocessing.
- **Prophet**: A forecasting tool for time-series predictions.
- **matplotlib**: A visualization library for plotting the historical and forecasted data.
- **requests**: Used for making HTTP requests to fetch data from the FRED API.
