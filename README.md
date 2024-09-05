# Energy Usage Prediction with Machine Learning
This project aims to predict energy usage for appliances using various machine learning techniques and IoT data. By employing models such as Multiple Linear Regression, Support Vector Machine with Radial Kernel, Random Forest, and Gradient Boosting Machines (GBM), we analyze and forecast energy consumption. The dataset used includes temperature and humidity measurements, weather data, and energy usage logs. We perform data filtering, feature ranking, and model evaluation using repeated cross-validation to determine the most effective predictive model.
## Table of Contents
-   [Summary](#summary)
-   [Overview](#overview)
-   [Description](#description)
    -   [Data Collection](#data-collection)
    -   [Data Preparation](#data-preparation)
-   [Models and Evaluation](#models-and-evaluation)
    -   [Evaluation Metrics](#evaluation-metrics)
-   [Installation](#installation)
-   [Usage](#usage)
-   [Results](#results)
-   [Credits](#credits)
-   [License](#license)
- ## Overview

In this project, we explore various predictive models to analyze and forecast energy usage for appliances using a combination of machine learning techniques and IoT data. The project focuses on evaluating multiple models, including:

-   **Multiple Linear Regression**
-   **Support Vector Machine with Radial Kernel**
-   **Random Forest**
-   **Gradient Boosting Machines (GBM)**

We employ statistical models with repeated cross-validation and evaluate their performance on a testing set.

## Description

### Data Collection

-   **Temperature and Humidity Data**: Collected every 3.3 minutes from wireless sensors and averaged for 10-minute intervals.
-   **Energy Usage Data**: Logged every 10 minutes with m-bus energy meters.
-   **Weather Data**: Downloaded from a public dataset (Reliable Prognosis, rp5.ru) and merged with the experimental data based on date and time.
-   **Additional Variables**: Two random variables included in the dataset to test regression models and filter out non-predictive attributes.

### Data Preparation

1.  **Filtering**: Remove non-predictive parameters.
2.  **Feature Ranking**: Evaluate and select important features for model training.

## Models and Evaluation

We implement and compare the following models:

-   **Multiple Linear Regression**: Assesses the linear relationship between features and energy usage.
-   **Support Vector Machine with Radial Kernel**: Applies non-linear transformations to capture complex patterns.
-   **Random Forest**: Utilizes an ensemble of decision trees for robust predictions.
-   **Gradient Boosting Machines (GBM)**: Employs boosting techniques to improve model accuracy.

### Evaluation Metrics

-   **Root Mean Squared Error (RMSE)**
-   **Mean Absolute Percentage Error (MAPE)**
-   **R² Score**
## Installation

To set up the project environment, follow these steps:

1.  **Clone the repository:**
  

    `git clone https://github.com/your-username/energy-usage-prediction.git
    cd energy-usage-prediction`

2.  **Install the required packages:**
  `pip install -r requirements.txt`
## Usage

To run the predictive models and evaluate their performance:

1.  **Run the script for model training and evaluation:**

2.    `python module.py` 
    
3.  **Review the results and performance metrics in the output files.**
    

## Results

The results include various metrics for model performance, such as RMSE, MAPE, and R² scores, providing insights into the accuracy and effectiveness of each predictive model.

## Credits

-   **Ahmed Elsheikh** - [GitHub Profile](https://github.com/Ahmedvini)  
    Lead developer and project coordinator.
    

## License

This project is licensed under the MIT License. See the LICENSE file for details.

   





