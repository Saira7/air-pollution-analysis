# Air Pollution Analysis and Prediction

This project focuses on analyzing air pollution data and applying machine learning models to predict air quality based on various atmospheric features. The aim is to understand trends, visualize pollutant distributions, and build predictive models that can help assess environmental conditions.

## Contents

- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Correlation Analysis
- Feature Engineering
- Model Building and Evaluation:
  - Linear Regression
  - Random Forest Regressor
  - Decision Tree Regressor
- Visualization of Results
- Conclusion

## Dataset

The dataset contains information on atmospheric pollutants and meteorological parameters such as:

- PM2.5
- PM10
- NO2
- SO2
- CO
- O3
- Temperature
- Humidity
- Wind Speed

These features are used to predict air quality and analyze pollutant behavior over time.

## Requirements

To run the project, install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
## Running the Notebook

1. Clone the repository or download the `.ipynb` file.
2. Open the notebook using Jupyter:

   ```bash
   jupyter notebook AirPollution.ipynb
   ```
 3. Run all cells in sequence to process data, train models, and visualize results.

## Results

The models were evaluated using metrics such as:

   - Mean Absolute Error (MAE)

   - Mean Squared Error (MSE)

   - R-squared Score

Comparisons between models highlight the strengths and weaknesses of each approach in predicting pollutant levels.

## Conclusion

  - Feature correlation shows strong relationships among pollutants and weather conditions.

  - Random Forest Regressor provided better performance compared to other models.

  - Data visualization revealed temporal patterns in air pollution.
