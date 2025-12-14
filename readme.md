# Flight Delay Prediction ✈️

This project predicts whether a flight will be delayed (15 minutes or more)
using historical flight data and machine learning.

## Problem
Flight delays cause passenger dissatisfaction and operational issues.
The goal is to classify flights as:
- **On Time**
- **Delayed (≥ 15 minutes)**

## Dataset
Sample flight data containing:
- Date information
- Scheduled departure and arrival times
- Departure delay
- Flight and route details

*(Large raw datasets are intentionally excluded from this repository.)*

## Features Used
- year
- month
- day_of_month
- day_of_week
- crs_dep_time
- crs_arr_time
- dep_delay

## Target Variable
`target_delay`
- `1` → Delayed (arrival delay ≥ 15 minutes)
- `0` → On time

## Model
- **Logistic Regression**

## Results
- **Accuracy:** 93%
- Strong performance on on-time flights
- Good recall for delayed flights

## Evaluation
- Classification report
- Confusion matrix

## Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
