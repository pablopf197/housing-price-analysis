# **Factors Influencing Housing Prices**

## **Objective**
This project analyzes a comprehensive housing dataset containing over 2.2 million property records from across the U.S. to identify the key factors influencing property prices. By examining features such as house size, number of rooms, lot size, property status, and location, we aim to uncover trends and relationships that drive housing prices.

The analysis includes Exploratory Data Analysis (EDA) and regression modeling to evaluate the impact of various features and locations on property values.

---

## **Dataset**
The dataset used in this analysis includes:
- **Total records**: Over 2.2 million properties.
- **Key features**:
  - Property location: Street, City, State, and zip code.
  - Property characteristics: House size, lot size, bedrooms, bathrooms.
  - Status: "Ready for sale" or "Ready to build."
  - Historical data: Previous sale dates (where available).

---

## **Steps in the Analysis**
1. **Exploratory Data Analysis (EDA)**
   - Visualized relationships:
     - Price vs. number of bedrooms, bathrooms, house size, and lot size.
     - Average housing prices by city and state.
   - Trend analysis:
     - Distribution of prices for properties "ready for sale" vs. "ready to build."
   - Correlation analysis:
     - Relationships between numeric features like house size, lot size, and price.

2. **Key Analysis Questions**
   - **Location Impact**: How do housing prices vary across cities, states, and zip codes?
   - **Property Features**: What is the effect of house size, lot size, and number of bedrooms and bathrooms on price?
   - **Housing Status**: Are "ready for sale" properties priced higher than "ready to build" properties?
   - **Historical Trends**: How have property prices changed based on previous sale dates?
   - **Brokers and Streets**: Are there brokers or streets associated with high-value properties?

3. **Data Preparation**
   - Addressed missing values (e.g., imputed missing prices and property sizes).
   - Transformed dates into useful features (e.g., years since last sold).

4. **Predictive Modeling**
   - Built regression models:
     - **Linear Regression**: Evaluated the relationship between price and features such as house size and number of bedrooms.
     - **Multiple Regression**: Incorporated additional factors to refine predictions.
   - Evaluated performance using:
     - Mean Absolute Error (MAE).
     - Root Mean Squared Error (RMSE).