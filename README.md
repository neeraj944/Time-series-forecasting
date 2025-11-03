# Time-series-forecasting
This project predicts future trends based on past time-series data and allows users to interactively view current and future trends through a simple web interface.

Objectives:
Build a forecasting model using Prophet to predict future values.

Deploy the model using FastAPI to create a RESTful API endpoint.

Use Gradio to build an interactive UI where users can:

View current and future trend graphs

Select a particular month or interval for forecasting

View predicted data for the selected duration

Technologies Used:

Python

FastAPI – for building and deploying the API

Prophet – for time series forecasting

Gradio – for building an interactive web interface

Ngrok – for generating a temporary public URL to test the API

Matplotlib / Plotly – for data visualization

 Features:

 Interactive Gradio UI with buttons to:

Display current trend graph (past months)

Display forecast graph (upcoming months)

 How It Works?

The dataset containing historical time-series data is loaded.

The Prophet model is trained on this data to learn seasonal patterns and trends.

A FastAPI endpoint (/forecast) is created to take user input (e.g., number of months or date interval) and return predicted results in JSON format.

A Gradio interface allows users to visually interact with the API, showing both current and future trend graphs.

 Output:

Graphs showing past and future trends

Forecast results with confidence intervals (yhat_lower, yhat, yhat_upper)

Visual indication of forecasted data for user-selected months

 Use Case:

This project can be used in domains like:

Sales Forecasting

Weather Prediction

Travel Planning (Best Time Analysis)

Stock Market Trend Analysis

Energy Demand Prediction
