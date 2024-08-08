# Suicide Rate Prediction in India: ARIMA Model

## Project Overview

This project involves forecasting suicide rates in India using an ARIMA model. Over the past 60 years, the data (real world) has been meticulously analyzed to identify trends and patterns, making it a valuable resource for understanding the impact of socio-economic and health factors on suicide rates. The model is part of a research initiative and uses real-life, confidential data to provide insights that could inform future policy decisions and mental health strategies.

## Repository Structure

- **arima-project-suicide-prediction.ipynb**: The Jupyter Notebook containing the complete implementation of the ARIMA model for forecasting suicide rates.

## Motivation

Suicide is a significant public health issue in India, influenced by various socio-economic and health-related factors. This project aims to forecast future suicide rates based on historical data, providing insights that could help in the formulation of preventive measures. By understanding trends and potential future scenarios, policymakers and health professionals can be better equipped to address this critical issue.

## Dataset

The dataset used in this project is a confidential, real-life collection of suicide rates in India over the past 60 years. This data includes variables that capture the impact of factors such as infertility, illness, and drug addiction on suicide rates. The dataset is not publicly available due to its sensitive nature.

## Preprocessing Techniques

1. **Log Transformation**: Applied to stabilize variance and make the data more stationarity-friendly for ARIMA modeling.
2. **Differencing**: Used to remove trends and achieve stationarity, essential for accurate time series forecasting.
3. Reverting the applied transformations from the final results to get the original units.

## Model Architecture

The ARIMA model was chosen for its robustness in handling time series data. Various combinations of ARIMA parameters (p, d, q) were tested to identify the best model, which was then used to forecast future suicide rates. The model was evaluated using metrics like AIC, BIC, and the Ljung-Box test to ensure its adequacy and reliability.

## Results

The final ARIMA model demonstrated a strong ability to forecast suicide rates, with minimal residual autocorrelation as indicated by the Ljung-Box test. The model's predictions provide a valuable tool for understanding future trends in suicide rates, potentially informing preventative measures and public health strategies.

## Future Work

- **Regression Analysis**: Perform regression analysis to understand the impact of various socio-economic factors like infertility, illness, and drug addiction on suicide rates.
- **Model Expansion**: Explore other time series models like SARIMA or machine learning approaches to compare and potentially improve forecasting accuracy.
- **Policy Implications**: Collaborate with mental health professionals and policymakers to translate these insights into actionable strategies.

## Conclusion

This project showcases the application of ARIMA modeling in forecasting critical public health data. By analyzing and predicting suicide rates, it provides a foundation for informed decision-making and the development of targeted interventions to reduce suicide rates in India.

## Author

**Siddharth Upadhyay**  
- [[LinkedIn](https://www.linkedin.com/in/siddharth-upadhyay-330ab9229/)](https://www.linkedin.com/in/siddharth-upadhyay-330ab9229/)
- [[GitHub](https://github.com/SID-9?tab=repositories)](https://github.com/SID-9?tab=repositories)
