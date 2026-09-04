# Wind Energy Forecasting and Battery Storage Simulation

A deep learning project for wind power forecasting, electricity demand prediction, and battery energy storage simulation.

## Overview

This project explores the application of deep learning to renewable energy management.

The project consists of three major components:

1. Wind power generation forecasting
2. Electricity demand forecasting
3. Battery energy storage simulation

The goal is to evaluate whether AI-based forecasting can support more efficient utilization of wind energy and help estimate energy storage requirements.

## Project Workflow

The overall workflow includes:

- Data preprocessing
- Meteorological feature engineering
- Wind power forecasting
- Electricity demand forecasting
- Model evaluation
- Battery charging and discharging simulation
- Result visualization

## Models

### Wind Power Forecasting

Two deep learning architectures were evaluated:

- Long Short-Term Memory (LSTM)
- Temporal Convolutional Network (TCN)

Input features included meteorological and operational variables such as:

- Wind speed
- Wind direction
- Atmospheric pressure
- Sunshine duration
- Turbine operating hours

### Electricity Demand Forecasting

An LSTM model was used to predict monthly electricity consumption based on historical electricity demand data.

### Battery Energy Storage Simulation

A battery storage model was developed to simulate energy charging and discharging.

The simulation follows a simple strategy:

- Charge the battery when wind power generation exceeds electricity demand.
- Discharge the battery when electricity demand exceeds wind power generation.

## Data

The project uses publicly available data from:

- Taiwan Power Company
- Central Weather Administration (CODIS)

The datasets include:

- Wind power generation
- Turbine operating hours
- Meteorological measurements
- Regional electricity consumption

## Technologies

- Python
- TensorFlow / Keras
- pandas
- NumPy
- scikit-learn
- Matplotlib
- Google Colab

## Repository Structure

```text
wind-energy-forecasting-and-storage/
│
├── README.md
├── wind_energy_forecasting_and_storage.ipynb
└── requirements.txt
