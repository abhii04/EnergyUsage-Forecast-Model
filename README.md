# PJME Energy Consumption Forecasting
![image](https://github.com/user-attachments/assets/efcb50c0-695a-4d5a-9e6c-f5d904595d35)


## Overview

This project focuses on forecasting PJME (PJM Eastern Hub) energy consumption using time series analysis techniques. The objective is to develop a robust forecasting model that predicts future energy usage based on historical data. This enables better decision-making and resource management in the energy sector.

## Project Structure

1. **Data Preparation**: This phase involves cleaning and visualizing historical energy consumption data. It includes identifying trends, outliers, and anomalies to understand the data better.

2. **Feature Engineering**: In this step, additional time-based features are created from the time series data. These features include hour, day of the week, month, and year, which help capture temporal patterns and improve model performance.

3. **Model Validation**: The data is split using `TimeSeriesSplit` to perform cross-validation. This ensures that the model's performance is robust and generalizes well across different time periods.

4. **Future Forecasting**: Future data points are generated, and predictions are made for energy consumption. These predictions are then visualized to assess the forecast's accuracy and utility for strategic planning.

## Key Features

- **Data Visualization**: Visualizations of historical energy consumption, outliers, and future predictions to gain insights into patterns and trends.
  
- **Feature Engineering**: Enrichment of the dataset with time-based features to enhance forecasting accuracy.

- **Time Series Splitting**: Use of `TimeSeriesSplit` for rigorous model validation and performance evaluation.

- **Forecasting**: Generation and visualization of future energy usage predictions to support planning and decision-making.

## Installation

To run this project locally, ensure you have Python and the necessary packages installed. You can install the required packages using pip.

## Usage

1. **Data Preparation**: Load and clean the data, followed by visualizing it to understand historical trends and anomalies.

2. **Feature Engineering**: Enhance the dataset with additional time-based features to capture temporal patterns.

3. **Model Validation**: Use `TimeSeriesSplit` to validate the model across different time periods, ensuring robust performance.

4. **Future Forecasting**: Extend the dataset into the future and generate predictions. Visualize these predictions to evaluate forecast accuracy.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your proposed changes. Ensure that your contributions adhere to the existing coding standards and include relevant tests.


## Contact

For any questions or further information, please contact [Abhilash Shinde](abhilashshinde4@gmail.com).

---

Thank you for exploring this project. I look forward to your feedback and contributions!

