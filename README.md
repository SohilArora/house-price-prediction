This project focuses on predicting the median house value using socio-economic and geographic features such as income level, population, housing characteristics, and location coordinates. Multiple machine learning regression models are trained and compared to identify the best-performing model.

📊 Dataset Information
The dataset contains the following columns:
- latitude
- housing_median_age
- total_rooms
- total_bedrooms
- population
- households
- median_income
- ocean_proximity

Problem Type : Regression problem
Target variable: median_house_value

🔍 Data Analysis & Preprocessing
Exploratory data analysis revealed that median_income is highly correlated with the target variable median_house_value.
To ensure that both training and testing datasets represent the population uniformly, stratified shuffling was applied based on median_income.

The dataset was cleaned and preprocessed, including: 

- Handling categorical features using encoding.

- Feature scaling where required.

- Train-test split using stratified sampling.

🤖 Machine Learning Models Applied

The following regression models were trained and evaluated:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor

📈 Model Evaluation

Models were evaluated using the R² score as the primary performance metric.

Best Model: XGBoost Regressor

Highest R² Score Achieved: 0.82

📌 Conclusion

Among all the models tested, XGBoost outperformed other regression algorithms, making it the most suitable model for predicting median house values for this dataset.
