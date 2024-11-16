# Housing Price Prediction Project

## Overview
This project aims to develop a predictive model for housing prices using various regression techniques. The project is encapsulated in a Jupyter Notebook and demonstrates a data science workflow that includes data preprocessing, feature engineering, model training, and evaluation. The primary model used is `GradientBoostingRegressor`, achieving an R-squared score of 92.67% and a Mean Absolute Error (MAE) of 15,192.97.

## Project Structure
- **Data Loading and Preprocessing**: Handling missing values, encoding categorical variables, and feature scaling.
- **Exploratory Data Analysis (EDA)**: Visualizing the data to understand relationships and patterns.
- **Model Training**: Implementing multiple regression models (e.g., `GradientBoostingRegressor`, `RandomForestRegressor`, `XGBoost`) and tuning hyperparameters.
- **Model Evaluation**: Assessing performance using metrics like R-squared, MAE, and visualizations of actual vs. predicted values.

## Key Results
- **Chosen Model**: `GradientBoostingRegressor`
- **Performance**:
  - R-squared: 92.67%
  - MAE: 15,192.97
- **Rationale for Model Selection**:
  - Strong performance across data splits.
  - Balance of accuracy and computational efficiency.

## How to Run the Project
1. Clone this repository.
2. Ensure Python 3.8+ is installed.
3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook "Housing Prediction.ipynb"
   ```

## Future Enhancements
- Integrating additional data sources to improve model robustness.
- Implementing feature selection techniques to optimize performance.
- Exploring deep learning approaches for comparison.

## License
This project is open-source under the MIT License.

## Contact
For questions or collaboration, reach out via [LinkedIn](https://www.linkedin.com/in/adiel-maina/) or [GitHub](https://github.com/adielmaina).
