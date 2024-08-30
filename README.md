# Rainfall Prediction in Nairobi

## Overview
This project aims to predict rainfall in Nairobi using machine learning models based on historical weather data. The objective is to build a robust model that can forecast rainfall accurately, which is essential for sectors like agriculture.

## Business and Data Understanding
### Business Understanding
Accurate rainfall predictions are crucial for various sectors, especially agriculture. This project addresses the need for precise weather forecasts in Nairobi by leveraging a decade’s worth of historical weather data.

### Data Understanding
The dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package) and includes various weather attributes such as Temperature, Rainfall, Humidity, Wind Speed, and more. The data covers the period from 1970 to 1999.

## Modeling
The project utilized three primary models:
1. **Logistic Regression**
2. **Random Forest**
3. **XGBoost**

Feature engineering and preprocessing were applied to the dataset, followed by training the models. Each model's performance was evaluated using accuracy, precision, recall, and F1-score.

## Evaluation
XGBoost emerged as the best-performing model, with superior accuracy and balanced computation time. Random Forest also performed well but showed signs of overfitting. Logistic Regression provided a good balance between accuracy and speed.

## Conclusion
The XGBoost model is recommended for deployment in real-time applications. Regular updates and data expansion could further improve the model’s performance. Future research may explore deep learning techniques for enhanced predictions.

## Recommendations
- **Model Deployment**: Deploy the XGBoost model for real-time rainfall prediction.
- **Data Expansion**: Incorporate more recent weather data and satellite data for improved accuracy.
- **Regular Updates**: Retrain the model periodically with new data.
- **Further Research**: Explore advanced algorithms, including deep learning, to refine the predictions.
