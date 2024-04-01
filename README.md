# Used Car Price Prediction Project

![Used Car Price Prediction](img/standvirtual.png)

Welcome to the Used Car Price Prediction project! This repository contains the code and resources for scraping used car prices from the web, training a predictive model, and making accurate price predictions.

## Overview

This project is aimed at predicting used car prices using data scraped from various online sources. The workflow includes:

1. **Data Scraping**: Python scripts are used to scrape the web for used car listings, extracting essential features such as make, model, year, mileage, and price.

2. **Data Preprocessing**: The scraped data undergoes thorough cleaning and preprocessing to handle missing values, outliers, and ensure consistency.

3. **Exploratory Data Analysis (EDA)**: Visualization techniques are applied to gain insights into the distribution and relationships between variables.

4. **Model Training**: A Random Forest Regression model is trained using Scikit-learn, achieving an impressive accuracy rate of 88%.

5. **Model Deployment**: The trained model is saved for future use, allowing for real-world price predictions.

## Results

The predictive model demonstrates its efficacy by accurately predicting the price of a personally purchased car, highlighting its practical utility in the used car market.

## Future Work

In future iterations, we plan to:

- Experiment with different machine learning models
- Conduct hyperparameter tuning for improved performance
- Compare model performance with an Artificial Neural Network approach

## Getting Started

To get started with the project:

1. Clone this repository:

   ```bash
   git clone https://github.com/your_username/used-car-price-prediction.git
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook `used_car_price_prediction.ipynb` to explore the project in detail.

## Additional Resources

For more information, refer to the Jupyter notebook `used_car_price_prediction.ipynb` in this repository.

---

Include the image file `car_prediction_image.png` in the repository and replace `your_username` in the clone URL with your GitHub username.

This README file provides a comprehensive overview of the project, its objectives, workflow, and future directions, facilitating collaboration and contributions from the community.


I developed a Python project aimed at scraping the web for used car prices, storing all the acquired data locally. Following this, I engaged in data cleaning and visualization to prepare the dataset for model training using Scikit-learn. Utilizing a Random Forest pipeline, I fitted the data and achieved an impressive accuracy of 88%. Subsequently, the trained model was saved and deployed to predict the price of a car I personally purchased, yielding results that closely matched expectations.

This endeavor provided invaluable insights into the intricate market trends governing used car prices, which are influenced by a multitude of numerical and categorical variables. Moving forward, I aspire to explore different models, delve into hyperparameter tuning, and compare performance, potentially including an Artificial Neural Network model for enhanced predictive capabilities.

For further details, please refer to the Jupyter notebook saved within this repository.
