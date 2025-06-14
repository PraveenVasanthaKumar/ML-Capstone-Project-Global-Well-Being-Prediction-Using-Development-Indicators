# ML Capstone Project-Global Well Being Prediction Using Development Indicators

**Objective**

The main goal of this project is to predict the global well-being of countries based on a combination of socioeconomic, governance, and subjective well-being indicators. The project leverages data from the World Happiness Report from 2005 to 2023, integrating various factors such as economic conditions, social support, governance, health, and individual perceptions to predict overall happiness and life satisfaction across nations.

**Specific Goals**

**1. Data Exploration and Preprocessing**
Analyze and preprocess the dataset to handle missing values, normalize data, and ensure the integrity of categorical and numerical variables.
Identify the key socioeconomic and psychological factors that most influence happiness scores globally.

**2. Identify Global Trends**
* Analyze trends in happiness scores globally and regionally.
* Identify regions or countries with consistently high or low happiness levels.

**3. Predict Happiness Scores**
* Build predictive models using machine learning techniques to forecast happiness scores based on available features like GDP, social support, and other socio-economic variables.
* Compute the change in "Life Ladder Score" over years for each country and predict the direction (increase or decrease).

**4. Socioeconomic, Governance, and Well-Being Insights**
* Investigate how socioeconomic factors (e.g., GNI per capita, total population, internet penetration) and governance indicators (e.g., Voice and Accountability, Government Effectiveness) influence happiness.
* Identify the most significant drivers of well-being across countries and explore any regional patterns that could inform policymaking.

**5. Visualize Relationships**
* Create meaningful visualizations to represent the relationships between key variables.
* Highlight patterns, outliers, and correlations to provide a deeper understanding of global well-being.

**Technologies Used**

* Data Preparation: Microsoft Excel
* Programming Language: Python (Jupyter Notebook)
* Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-Learn


Data Description
This dataset provides various indicators for countries based on their happiness report data from 2005 to 2023, including economic, social, and governance factors, along with subjective measures like life satisfaction and emotional well-being.

Variable	Type	Values	Description

![image](https://github.com/user-attachments/assets/c720ba7d-d83c-4470-a2d1-f57de1294b94)


Results Summary
1. Life Ladder Score Prediction
Best Model: RandomForestRegressor

Test R²: 0.856 (excellent generalization).
MSE: 0.178 (minimal error).
MAE: 0.321 (low average error).
Overfitting: Minimal (Train R²: 0.851).
Alternatives: GradientBoostingRegressor and XGBRegressor are strong options but slightly less accurate.

2. Healthy Life Expectancy Prediction
Best Model: RandomForestRegressor

Test R²: 0.916 (outstanding generalization).
MSE: 3.63, MAE: 1.27 (low errors).
Overfitting: Balanced (Train R²: 0.852).
Alternatives: XGBRegressor performs similarly but with slightly higher errors.

Final Recommendation:
RandomForestRegressor is the best model for both tasks, delivering high accuracy, minimal errors, and excellent generalization.

