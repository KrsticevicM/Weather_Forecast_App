# Weather Forecast Prediction App

## Description
This project was developed as part of a university course. It is a **group project** consisting of **6 members**, and the goal was to create a **mobile application** for predicting and visualizing meteorological conditions. The app allows users to analyze historical weather data, generate descriptive statistics, and predict future weather values using a simple machine learning algorithm—linear regression.

The project was completed on **22/1/2024**.

## Features
- **User Interface**: A clean and intuitive interface for selecting weather data parameters.
- **Historical Data Analysis**: Users can choose a time range, data type (e.g., temperature, precipitation, pressure), and granularity (daily, weekly, monthly, yearly) to analyze historical weather data.
- **Data Visualization**: Line charts are generated to display weather data for the selected period and granularity.
- **Descriptive Statistics**: The app calculates and displays averages, standard deviations, and identifies outliers in the data.
- **Data Export**: Users can download the analyzed data in a text file for further use.
- **Weather Prediction**: A linear regression model is used to predict future weather values based on historical data.

## Technologies Used
- **Programming Language**: Python
- **Frameworks and Libraries**:
  - **Kivy**: A Python framework for developing mobile applications.
  - **NumPy**: For numerical data processing.
  - **Matplotlib**: For data visualization.
- **Data Source**: Meteorological data is fetched from [Meteostat](https://meteostat.net/), a reliable source for open weather and climate data.
- **Development Environment**: PyCharm Professional.

## System Structure
The system is logically divided into four main components:
1. **Main**: Initializes the KivyMD application and manages navigation between screens.
2. **Home Screen**: Allows users to select parameters for weather data analysis.
3. **Second Screen**: Displays historical weather data, predictions, and descriptive statistics.
4. **Linear Regression Model**: Predicts future weather values based on historical data.

## Documentation
For a detailed explanation of the project, including its architecture, design decisions, and implementation details, please refer to the **full documentation PDF**: [projectDocs.pdf]
