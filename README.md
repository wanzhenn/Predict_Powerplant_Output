# Predict_Powerplant_Output
*   **Problem Statement:** To predict output of Combined cycle power plants (CCPP)

*   **Method:**
    1.   Conducted Exploratory Data Analysis (EDA) to find out correlation of variables to predicted output 'PE'
    2.   Utilized Machine Learning models to predict 'PE'
    3.   Evaluated performance of models and selected best model for deployment
  
*   **Approach:** Obtain data from 1997 to 2022 (Source: UCI Machine Learning Repository)

*   **Metric:** Measure overall loss based of predicted output of (PE) and the actual output in the year 2022 (Jan-Jun)

* **Conclusion:**

   Based on the overall mean, RandomForestRegressor model which utilized more data points provided a more accurate prediction of 'PE' as compared to a    linear model, which utilized a negative relation between 'AT' and 'PE'.
