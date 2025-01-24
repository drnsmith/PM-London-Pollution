### Machine Learning Predictive Analytics for PM10 Pollution: Using Random Forests, Gradient Boosting, XGBoost, Ridge and Lasso Regressions, and Neural Network Regressor

#### **Overview**
This project aims to predict air pollution levels, specifically **PM10 concentrations**, in London using various **machine learning (ML)** techniques. Accurate forecasting of pollution levels is crucial for public health and urban planning. The dataset used for this project is the **"London Atmospheric Emissions Inventory 2013"**, which includes detailed environmental and monitoring data. The main goal is to develop and optimise predictive models and evaluate their performance using **Root Mean Squared Error (RMSE)** as the primary evaluation metric. 

- **Dataset**: [London Atmospheric Emissions Inventory 2013](https://data.london.gov.uk/dataset/london-atmospheric-emissions-inventory-2013)
- **Target Variable**: PM10 (Particulate Matter ≤ 10µm)
- **Evaluation Metric**: RMSE (Root Mean Squared Error)

---

#### **Motivation**
Air pollution is a significant global challenge, affecting public health, quality of life, and urban development. Accurate prediction of pollution levels enables policymakers and environmental agencies to take preventive measures, such as issuing warnings and enforcing regulations. This project addresses the critical need for data-driven insights to tackle urban air pollution and support healthier cities.

---

#### **Project Tasks**

1. **Exploratory Data Analysis (EDA)**:
   - Explored the dataset to understand its structure, features, and distribution of the target variable (PM10).
   - Visualised trends, outliers, and potential correlations between features and PM10 concentrations.

2. **Data Pre-processing**:
   - **Feature Selection**: Selected relevant environmental and meteorological variables for predicting PM10 concentrations.
   - **Data Cleaning**: Handled missing values, treated outliers, and standardised the features to prepare them for modelling.
   - **Feature Engineering**: Transformed categorical data and engineered additional features to improve model performance.

3. **Model Implementation**:
   - **Linear Regression**: Baseline model.
   - **Random Forest**: Ensemble learning for robust predictions.
   - **Gradient Boosting**: Sequential error correction.
   - **Ridge and Lasso Regression**: Regularisation techniques to mitigate overfitting.
   - **XGBoost**: Optimised gradient boosting for structured data.
   - **Neural Network Regressor**: Captured complex relationships in the data.

4. **Model Evaluation**:
   - Evaluated models using **Root Mean Squared Error (RMSE)**.
   - Lower RMSE values indicate better predictive performance.

5. **Model Comparison**:
   - Compared RMSE values to identify the best-performing model.
---

#### **How to Run**

1. **Clone the Repository**:
```bash
   git clone https://github.com/username/PM10-Prediction.git
   cd PM10-Prediction
```
2. Install Dependencies:

```bash
pip install -r requirements.txt
```
3. Run the Data Preprocessing Script:
```bash
python preprocess.py
```

4. Train and Evaluate Models:
```bash
python train.py
```
### Prerequisites
- **Python 3.x**: Ensure Python is installed. 
- **Dependencies**: Install the required libraries listed in `requirements.txt` by running the following command:
```bash
   pip install -r requirements.txt
``` 

### Contributing
Contributions are welcome! If you have ideas or improvements to share, please follow these steps:

1. **Fork the Repository:**
Create your own copy of the repository by clicking the "Fork" button at the top right of this page.

2. **Create a Feature Branch:**
Work on your changes in a dedicated branch.

```bash
git checkout -b feature/YourFeatureName
```
3. **Commit Your Changes:**
Write clear and concise commit messages explaining what you’ve done.

```bash
git commit -m "Add YourFeatureName"
```
4. **Push Your Changes:**
Push your feature branch to your forked repository.
```bash
git push origin feature/YourFeatureName
```
5. **Open a Pull Request:**
Submit your changes to the main repository by opening a pull request (PR). Ensure your PR description explains your changes clearly.

6. **Review and Feedback:**
I will review your PR and may suggest improvements before merging it into the main branch.

Thank you for your interest in contributing!

---
## Repository History Cleaned

As part of preparing this repository for collaboration, its commit history has been cleaned. This action ensures a more streamlined project for contributors and removes outdated or redundant information in the history. 

The current state reflects the latest progress as of 24/01/2025.

For questions regarding prior work or additional details, please contact the author.

---

### Acknowledgments
Special thanks to the dataset contributors for providing detailed environmental data.

### License

Distributed under the MIT License. See `LICENSE` for more information.

