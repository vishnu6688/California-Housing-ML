# California-Housing-ML
California housing price prediction pipeline

## Overview

​* The dataset an end-to-end machine learning pipeline focused on building predictive models to forecast housing prices using the California Housing dataset.

​## Objectives

​* Understand and analyze the California housing dataset to identify key factors influencing property values.
​* Perform data cleaning, handle missing values, and prepare data for modeling.
​* Conduct exploratory data analysis to uncover statistical insights and patterns.
​* Build, evaluate, and optimize machine learning regression models to predict median house values accurately.


## Technologies Used

​* Python
​* Pandas & NumPy
​* Matplotlib
* Seaborn
​* Scikit-Learn


## Workflow

​* Data Understanding
​* Loaded the California housing dataset to inspect its structure and dimensions.
​* Analyzed data types and initial statistical summaries of all features.


## Data Cleaning

​Checked for missing values and imputed the total bedrooms feature using median imputation.
​Identified and removed duplicate records to ensure data integrity.
​Exploratory Data Analysis
​Performed statistical analysis and data visualization to understand feature distributions.
​Examined the distribution of house prices and identified relationships between median income and property values.


​## Data Preprocessing

​Standardized numerical features to bring them to a comparable scale.
​Engineered relevant features to potentially improve model predictive power.


​## Train-Test Split

​Split the cleaned dataset into training and testing subsets to validate model performance on unseen data.


​## Machine Learning Model

​Implemented regression algorithms, such as Linear Regression and Random Forest, to model the relationship between features and target values.


​## Model Evaluation

​Evaluated model performance using metrics such as Root Mean Squared Error (RMSE) and R-squared score.


​## Model Performance

​The models were assessed based on their ability to minimize prediction error. The Random Forest regressor demonstrated superior performance compared to baseline linear models, capturing non-linear relationships effectively.


​## Key Findings

​Median income was identified as the strongest positive predictor of median house values.
​Geographical location (latitude and longitude) significantly influences pricing trends due to regional desirability.


​## Actual vs. Predicted Prices

​Actual prices aligned closely with predicted values for mid-range properties, though extreme high-value outliers presented some estimation challenges.


​## Project Limitations

​The dataset reflects 1990 census data and may not capture modern market dynamics.
​Lack of real-time economic indicators limits the model's current applicability without feature updates.


​## Conclusion

​The project successfully demonstrates an end-to-end machine learning pipeline for real estate price prediction. While effective for historical analysis, integrating updated data streams would be necessary for deployment in current market scenarios.


​## Acknowledgments

​Thanks to the creators of the California Housing dataset for providing the benchmark data for this regression analysis.
