# Forecasting_of__daily_climate_with_Prophet
This repository contains code and data for training a forecasting model using Facebook's Prophet library to predict daily climate variables. The model is specifically designed for Indian climate and utilizes historical data from the city of Delhi, India.
## Dataset
The dataset provided covers the period from 1st January 2013 to 24th April 2017 and includes the following parameters:

- Meantemp: Mean temperature recorded in Delhi.
- Humidity: Level of humidity in Delhi.
- Wind_speed: Speed of the wind in Delhi.
- Meanpressure: Mean atmospheric pressure recorded in Delhi.
The dataset is available in a structured format, allowing for easy ingestion and processing. It serves as the foundation for training and evaluating the forecasting model. You can find it in the [link](https://www.kaggle.com/datasets/sumanthvrao/daily-climate-time-series-data?datasetId=312121&searchQuery=prophet).

##  Dependencies
The following dependencies are required to run the project:

- Python
- Pandas
- Scikit-learn
- Itertools
- Prophet
- Plotly

## Conclusion
The trained Prophet model provides accurate predictions for the specified climate variables. The forecasts enable users to anticipate daily climate conditions in Delhi, India, based on historical patterns and trends.

The performance of the model can be evaluated using various metrics, such as root mean squared error (RMSE), mean absolute error (MAE), or mean absolute percentage error (MAPE). These metrics help assess the accuracy and reliability of the model's predictions.

## License
This project is licensed under the MIT License. Feel free to modify and use the codebase for your own purposes.

## Contact
For any questions, suggestions, or issues, feel free to contact the repository maintainer at chris13angelid@gmail.com
