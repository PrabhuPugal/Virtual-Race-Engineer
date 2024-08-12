# Virtual Race Engineer

## Description
**Virtual Race Engineer** is a Python-based application designed to assist drivers and racing teams by providing real-time analytics, strategy recommendations, and telemetry data during a Formula 1 race. The project emulates the role of a race engineer, offering insights and strategic advice based on real-time race conditions, vehicle status, and competitor positions to enhance performance and decision-making.

## Features
- **Real-Time Telemetry Monitoring**: Collects and displays live data from the car, including speed, tire wear, fuel levels, and engine performance.
- **Strategy Optimization**: Provides recommendations on pit stops, tire changes, and fuel management based on real-time data and predictive algorithms.
- **Competitor Analysis**: Tracks the performance of competitors and suggests adjustments in strategy to gain a competitive edge.
- **Alert System**: Generates alerts for critical situations such as low fuel, high tire wear, or mechanical issues.
- **Data Logging**: Logs race data for post-race analysis and performance review.

## API Integration
The **Virtual Race Engineer** leverages the **FastF1 API** to retrieve real-time and historical Formula 1 telemetry data. This API provides detailed information about various aspects of a race, including lap times, sector performance, tire usage, and more. By integrating this data, the application can perform in-depth analyses and deliver accurate, real-time recommendations.
## Data Used for Analysis
The project utilizes several types of data for its analysis:

- **Telemetry Data**: Includes speed, throttle, brake pressure, gear shifts, and steering angles collected at high frequency during the race.
- **Race Event Data**: Information about laps, pit stops, tire choices, and weather conditions.
- **Competitor Data**: Performance data of other cars on the track, including their lap times, tire degradation, and pit strategies.

These datasets are used to build predictive models, simulate race strategies, and provide real-time feedback during the race.

## Machine Learning Models
The project uses the following machine learning models to predict race outcomes and optimize strategies:

1. **Random Forest**: This ensemble learning method is used to handle complex, non-linear relationships in the data, making it suitable for predicting outcomes like tire wear and fuel consumption.
2. **Linear Regression**: This model is employed to predict continuous variables, such as lap times and fuel usage, where relationships between features are expected to be linear.
## Metrics Used
The following metrics are used to evaluate the performance of the models:

- **Mean Absolute Error (MAE)**: Measures the average magnitude of errors in predictions, providing insight into model accuracy.
- **Root Mean Squared Error (RMSE)**: Highlights the differences between predicted and actual values, with a focus on larger errors.
- **Precision and Recall**: Used for classification models to assess the accuracy of predictions related to race events like pit stops and overtakes.
- **R-squared (R²)**: Indicates how well the regression model fits the observed data.

## Validation and Metrics
To ensure the accuracy and reliability of the models, the following validation methods and metrics are used:

- **F1 Score**: This metric is used to assess the precision and recall of the models, particularly in classification tasks related to race events like pit stops and overtakes.
- **Hyperparameter Tuning**: Techniques like grid search and random search are used to fine-tune the models' hyperparameters, optimizing their performance on the validation dataset.

## Methods for Checking Model Correctness
To further validate the models, the following methods are employed:

1. **Cross-Validation**: The data is split into multiple folds to test the model's performance across different subsets, ensuring robustness.
2. **Residual Analysis**: The residuals of predictions are examined to identify any systematic errors and improve model accuracy.
3. **Confusion Matrix**: For classification models, a confusion matrix is used to visualize the performance and calculate metrics like precision, recall, and F1 score.

## Contributing
This project is a contribution of
```
Prabhu P
Arun Harrish A P
```
Contributions are welcome! If you would like to contribute to the development of the Virtual Race Engineer, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test thoroughly.
4. Submit a pull request with a clear description of the changes.
5. Please ensure that your code adheres to the project's coding standards and includes appropriate documentation.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact
For questions or feedback, please reach out to me at prabhupugal01@gmail.com.
