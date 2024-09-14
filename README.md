# London Air Pollution Prediction (PM10 Levels)

## Project Overview

This project aims to predict air pollution levels, specifically **PM10 concentrations**, in London using various **machine learning (ML)** techniques. Accurate forecasting of pollution levels is crucial for public health and urban planning. The dataset used for this project is the **"London Atmospheric Emissions Inventory 2013"**, which includes detailed environmental and monitoring data. The main goal is to develop and optimise predictive models and evaluate their performance using **Root Mean Squared Error (RMSE)** as the primary evaluation metric. ![Pollution](pollution_london.jpg)

- **Dataset**: [London Atmospheric Emissions Inventory 2013](https://data.london.gov.uk/dataset/london-atmospheric-emissions-inventory-2013)
- **Target Variable**: PM10 (Particulate Matter ≤ 10µm)
- **Evaluation Metric**: RMSE (Root Mean Squared Error)

## Project Tasks
The following tasks were completed to build and optimise the predictive models:

1. **Exploratory Data Analysis (EDA)**:
   - Explored the dataset to understand its structure, features, and distribution of the target variable (PM10).
   - Visualised trends, outliers, and potential correlations between features and PM10 concentrations.

2. **Data Pre-processing**:
   - **Feature Selection**: Selected relevant environmental and meteorological variables for predicting PM10 concentrations.
   - **Data Cleaning**: Handled missing values, treated outliers, and standardised the features to prepare them for modelling.
   - **Feature Engineering**: Transformed categorical data and engineered additional features to improve model performance.

3. **Model Implementation**:
   - **Linear Regression**: Implemented a simple linear regression model to serve as a baseline.
   - **Random Forest**: Built an ensemble learning model for more robust predictions.
   - **Gradient Boosting**: Used gradient boosting for sequential error correction.
   - **Ridge and Lasso Regression**: Applied regularisation techniques to mitigate overfitting.
   - **XGBoost**: Leveraged the optimised version of gradient boosting, ideal for structured data.
   - **Neural Network Regressor**: Deployed a deep learning model to capture complex relationships in the data.

4. **Model Evaluation**:
   - Evaluated the models using **Root Mean Squared Error (RMSE)** to assess prediction accuracy.
   - Lower RMSE values indicate better predictive performance.

5. **Model Comparison**:
   - Compared RMSE values of all models to determine the most accurate predictor of PM10 levels.
   - Visualised the performance of each model for clearer comparison.

## Results

- The **XGBoost** model outperformed the other models with the lowest RMSE, making it the most accurate predictor of PM10 concentrations.
- There is potential for further improvement through additional hyperparameter tuning and more sophisticated feature engineering.

## Getting Started

To get a local copy up and running, follow these steps:

### Prerequisites
- **Python 3.x**: Ensure Python is installed. 
- **Dependencies**: Install the required libraries listed in `requirements.txt` by running the following command:
   ```bash
   pip install -r requirements.txt
   

## Contributing

This project was developed in collaboration with [Collaborator's Name]. Their expertise in [specific contributions] was invaluable to the success of this project.

Contributions are welcome! If you have ideas or improvements:
1. Fork the project.
2. Create a feature branch:
    ```bash
    git checkout -b feature/AmazingFeature
    ```
3. Commit your changes:
    ```bash
    git commit -m 'Add some AmazingFeature'
    ```
4. Push to the branch:
    ```bash
    git push origin feature/AmazingFeature
    ```
5. Open a pull request.


## License

Distributed under the MIT License. See `LICENSE` for more information.

