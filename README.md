# NYC Taxi Travel Time Forecasting with Weather Insights

## Overview
This project aims to enhance the prediction models for NYC taxi trip durations by integrating weather data with historical taxi trip records. The goal is to establish more reliable and efficient mobility solutions, improving planning and reducing uncertainties caused by weather impacts on travel times.

![Final Poster](https://github.com/user-attachments/assets/1855b001-fbfb-46e8-a5f4-2898ff19946c)

## Features
- **Data Integration**: Merges NYC taxi trip data with relevant meteorological data to understand the impact of weather on travel times.
- **Advanced Analytics**: Utilizes techniques like boxplot analysis and IQR method to clean and prepare data for modeling.
- **Deep Learning Models**: Employs multiple neural network configurations, including single-layer, multi-layer, and deep neural networks to optimize prediction accuracy.

## Technology Stack
- **Programming Languages**: Python
- **Libraries & Frameworks**: Pandas, NumPy, Scikit-Learn, TensorFlow
- **Tools**: Jupyter Notebook, Git

## Methodology
1. **Data Acquisition**: Collect historical NYC taxi trip data and corresponding weather data.
2. **Data Preprocessing**: Merge datasets based on pickup dates and clean data using statistical methods to remove outliers and reduce noise.
3. **Model Development**: Train various neural network models starting with simple architectures and gradually moving to complex configurations.
4. **Validation and Testing**: Evaluate models using Mean Absolute Error (MAE) and Mean Squared Error (MSE) metrics to ensure accuracy and reliability.

## Results
The advanced deep neural network model with 1024, 512, 256, and 128 neurons showed the best performance in predicting taxi travel times under varying weather conditions, achieving a low MAE and a high correlation with actual trip durations.

## Conclusion
The integration of weather data into the NYC taxi trip duration prediction models significantly enhances the accuracy of forecasts, proving crucial for operational planning and strategic management in urban mobility.

## How to Run
- Clone the repository: `git clone https://github.com/yourusername/nyc-taxi-travel-time-forecast.git`
- Navigate to the project directory: `cd nyc-taxi-travel-time-forecast`
- Install dependencies
- Run the Jupyter notebooks to train models and visualize results.
