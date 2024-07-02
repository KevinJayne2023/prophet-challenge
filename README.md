# prophet-challenge
Prophet Challenge - Mercado Libre Growth Analysis
Overview
This project aims to analyze the financial and user data of Mercado Libre, the most popular e-commerce site in Latin America, to identify patterns and trends that can help the company grow. The project is divided into four main steps:

Finding Unusual Patterns in Hourly Google Search Traffic
Mining the Search Traffic Data for Seasonality
Relating Search Traffic to Stock Price Patterns
Creating a Time Series Model with Prophet
Project Structure

Steps
Step 1: Find Unusual Patterns in Hourly Google Search Traffic
The goal of this step is to identify any unusual patterns in the Google search traffic data for Mercado Libre, particularly around the time when the company releases its quarterly financial results.

Tasks:

Load the Google search traffic data into a DataFrame.
Slice the data to just the month of May 2020.
Visualize the results to identify any unusual patterns.
Calculate the total search traffic for May 2020 and compare it to the monthly median across all months.
Determine if the Google search traffic increased during the month of the financial results release.
Step 2: Mine the Search Traffic Data for Seasonality
This step aims to mine the hourly search traffic data for predictable seasonal patterns, which can help focus marketing efforts around the times with the most traffic.

Tasks:

Group the hourly search data to plot the average traffic by the hour of the day.
Group the hourly search data to plot the average traffic by the day of the week.
Group the hourly search data to plot the average traffic by the week of the year.
Identify any time-based trends in the data.
Step 3: Relate the Search Traffic to Stock Price Patterns
In this step, the goal is to investigate whether there is a relationship between the Google search traffic data and the company's stock price.

Tasks:

Load the stock price data and concatenate it with the search data in a single DataFrame.
Slice the data to just the first half of 2020 (January to June) and plot the data.
Create new columns for "Lagged Search Trends", "Stock Volatility", and "Hourly Stock Return".
Analyze the relationship between the lagged search traffic and the stock volatility, as well as between the lagged search traffic and the stock price returns.
Step 4: Create a Time Series Model with Prophet
The objective of this step is to produce a time series model that analyzes and forecasts patterns in the hourly search data using the Prophet forecasting model.

Tasks:

Set up the Google search data for a Prophet forecasting model.
Estimate the model and plot the forecast to evaluate the near-term popularity of Mercado Libre.
Plot the individual time series components to determine the time of day with the greatest popularity, the day of the week with the most search traffic, and the lowest point for search traffic in the calendar year.

This project provides insights into the Google search traffic patterns for Mercado Libre and their relationship with the company's stock price. By analyzing these patterns and using time series forecasting, we can make informed decisions to optimize marketing strategies and potentially predict stock market behavior based on search trends.

Feel free to explore the notebook and adjust the analysis as needed for your specific use case.
