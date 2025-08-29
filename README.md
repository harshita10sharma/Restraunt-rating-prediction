# Restaurant Rating Prediction Model

## Overview
This project presents a predictive model for restaurant ratings developed using a real-world dataset. The main aim is to build a machine learning model that accurately predicts the aggregate rating of restaurants based on various features such as cuisine, location, pricing, and service options.

## Dataset Description
The dataset used in this project (`Dataset.csv`) contains diverse information about restaurants, including but not limited to:

- Restaurant Name and Location details
- Cuisine types served
- Price range and currency
- Availability of services like online delivery and table booking
- Various rating-related attributes, including aggregate rating, rating texts, and colors
- Other operational features and metadata

The dataset was thoroughly cleaned and preprocessed for handling missing data and encoding categorical variables to prepare it for model training.

## Data Exploration and Visualization
As part of the analysis, a range of visualizations were created to understand the data better:

- Distribution of aggregate ratings showing overall rating trends
- Top 10 cuisines to identify popular food types
- Pie charts for service availability like online delivery and table bookings
- Relationship between price range and average ratings through barplots and boxplots
- Correlation heatmaps revealing how various features influence one another and the final rating

These insights informed feature selection and model building decisions.

## Model Development
A Random Forest regression model was trained to predict the aggregate restaurant ratings. The key steps involved:

- Splitting the data into training and testing sets
- Encoding categorical variables using label encoding
- Training the Random Forest algorithm with 200 trees on the training data
- Evaluating model performance using metrics such as R², Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE)

The model demonstrated a good capacity to predict ratings accurately based on input features.

## How to Use
1. Ensure the dataset file `Dataset.csv` is available in the project directory.
2. Run the Python script to preprocess data, train the model, and visualize results.
3. Use the trained model to predict ratings for new sets of restaurant features by passing appropriate input values (e.g., cuisine type, city code, price range).

## Installation

Install the required Python packages using pip:

```bash
pip install -r requirements.txt
```

## Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-Learn for machine learning
- RandomForestRegressor algorithm for prediction

