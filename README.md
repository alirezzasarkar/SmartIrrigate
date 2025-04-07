# SmartIrrigate

**SmartIrrigate** is an AI-based irrigation prediction system that uses environmental data to predict the on/off status of an irrigation system. The project leverages machine learning algorithms to analyze factors such as soil moisture, temperature, air humidity, and other environmental variables to provide accurate predictions for optimizing water usage in agriculture.

## Project Overview

The goal of **SmartIrrigate** is to predict the irrigation system status based on various environmental data. By using data such as soil moisture, air temperature, wind speed, and other environmental factors, the system helps optimize water usage in agricultural irrigation systems.

## Features

- Predicting the irrigation system status (ON/OFF) based on environmental data.
- Utilizing machine learning models like **Decision Tree**, **Logistic Regression**, and **Random Forest** for classification.
- Using data preprocessing techniques such as scaling, encoding, and handling missing values.
- Providing plots and visualizations for data exploration and model evaluation.

## Technologies Used

- **Python**: Main programming language.
- **Scikit-learn**: For machine learning models and preprocessing.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib / Seaborn**: For data visualization.
- **Joblib**: For saving and loading trained models.
- **Jupyter Notebook**: For interactive data exploration.

## Model Evaluation

The best-performing model in this project is the **Decision Tree**, which has performed exceptionally well on the test data:

- **Accuracy**: 99.97%
- **F1-Score**: 99.97%

## Future Work

- Implement additional machine learning models like **XGBoost** and **Neural Networks**.
- Integrate real-time data from IoT sensors for dynamic and optimized irrigation management.
- Enhance feature engineering for better model performance.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
