# Price-Elasticity-of-Demand

**Project: Plastic Elasticity of Demand Analysis**

**Objective:**
The project aims to analyze the plastic elasticity of demand by exploring the relationship between quantity and price over time. The dataset includes features such as year, quarter, quantity, and price. The primary focus is on forecasting future demand based on historical data and understanding the factors influencing plastic demand elasticity.

**Data Processing:**
1. **Data Cleaning:** The dataset underwent thorough cleaning to handle missing values, and outliers, and ensure data integrity.
2. **Data Visualization (EDA):** Exploratory Data Analysis (EDA) techniques were employed to visualize trends, patterns, and correlations within the dataset.
3. **Preprocessing Techniques:**
   - **RobustScaler():** Used for scaling numerical features, ensuring robustness against outliers.
   - **OneHotEncoding:** Applied to categorical features for effective model training.

**Machine Learning Models:**
Utilized machine learning techniques to forecast plastic demand:
1. **Regression Analysis:**
   - **OLS (Ordinary Least Squares) Estimation:**
     - R-squared: 0.901, indicating a high explanatory power of the model.
     - Intercept: 30.0515, Price Coefficient: -0.0465.
     - P-values suggest that Price significantly impacts Quantity.
     - Diagnostic tests (Omnibus, Durbin-Watson, Jarque-Bera) ensure model reliability.

**Interpretation:**
- The regression model effectively explains the variability in plastic quantity based on price.
- Significant variables and a high R-squared value contribute to model robustness.
- Visualizations, including the regression line and prediction interval, enhance interpretation.

**Component-Component plus Residual (CCPR) Plots:**
- Used to assess the effect of one regressor while considering other independent variables.

**Recursive Least Square (RLS) Estimation:**
- Employed RLS to evaluate parameter stability over time.
- CUSUM statistic within the 5% significance bands indicates stable parameters.

**Conclusion:**
The project provides valuable insights into the plastic elasticity of demand, offering a predictive model for future demand forecasting. The analysis emphasizes the importance of price as a significant factor influencing plastic quantity. The robustness of the regression model and stability over time ensure its reliability for decision-making in the plastic industry.
