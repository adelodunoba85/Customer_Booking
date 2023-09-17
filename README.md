# Customer Booking

Below is a detailed description of the data, explaining exactly what each column means:

- `num_passengers` = number of passengers travelling
- `sales_channel` = sales channel booking was made on
- `trip_type` = trip Type (Round Trip, One Way, Circle Trip)
- `purchase_lead` = number of days between travel date and booking date
- `length_of_stay` = number of days spent at destination
- `flight_hour` = hour of flight departure
- `flight_day` = day of week of flight departure
- `route` = origin -> destination flight route
- `booking_origin` = country from where booking was made
- `wants_extra_baggage` = if the customer wanted extra baggage in the booking
- `wants_preferred_seat` = if the customer wanted a preferred seat in the booking
- `wants_in_flight_meals` = if the customer wanted in-flight meals in the booking
- `flight_duration` = total duration of flight (in hours)
- `booking_complete` = flag indicating if the customer completed the booking

## Task Description

The task involved three main objectives:

### Explore and Prepare the Dataset

I began by thoroughly exploring the dataset provided in the "Getting Started" Jupyter Notebook.
This exploratory phase helped me understand the dataset's columns, distributions, and basic statistics.
I considered feature engineering to enhance the dataset's suitability for predictive modeling.

### Train a Machine Learning Model

Once the dataset was adequately prepared, I proceeded to train a machine learning model.
For this task, I employed the RandomForest algorithm, which provides valuable insights into variable contributions to predictive power.

### Evaluate Model and Present Findings

After model training, I evaluated its performance using cross-validation and relevant evaluation metrics.
I created a visualization to interpret how each variable contributes to the model's predictive capabilities.
I summarized the key findings on a single presentation slide, adhering to the provided PowerPoint Template.

### XAi implementation

Implementing Local Interpretable Model-agnostic Explanations (LIME) and SHapley Additive exPlanations (SHAP) is a powerful way to explain predictions made by machine learning models. These techniques provide insights into why a model makes specific predictions for individual data points

## Key Achievements

Here are some highlights of the work done for British Airways:

Dataset exploration and preprocessing to enhance model readiness.
Utilized Python for the analysis portion, ensuring code transparency and reproducibility.
Trained a RandomForest machine learning model for customer booking prediction.
Conducted cross-validation and calculated relevant evaluation metrics to assess model performance.
Created a visualization to interpret variable contributions to the model.
Presented findings concisely in a single slide adhering to the PowerPoint Template provided.
