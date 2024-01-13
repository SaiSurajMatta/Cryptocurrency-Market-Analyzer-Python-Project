# Cryptocurrency Market Analyzer - Python Project

## Overview
This project involves creating a Cryptocurrency Market Analyzer using Python and the CoinMarketCap API. The analyzer fetches real-time data for the top 15 cryptocurrencies in terms of market capitalization and stores it in a DataFrame. The data is then saved to a CSV file for persistence, and trends over time are visualized using Seaborn.

## Project Structure
The project consists of the following components:

1. **Cryptocurrency API Integration:**
   - Utilizes the CoinMarketCap API to retrieve the latest cryptocurrency data.
   - Handles API requests and manages data using Python's requests library and pandas.

2. **Data Persistence:**
   - Saves the fetched data to a CSV file for future analysis.
   - Ensures data persistence for historical trends and further exploration.

3. **Data Analysis:**
   - Utilizes pandas for data manipulation and analysis.
   - Calculates the mean percentage changes for different time intervals (1 hour, 24 hours, 7 days, 30 days, 60 days, 90 days) for each cryptocurrency.

4. **Visualization:**
   - Uses Seaborn and Matplotlib for visualizing percentage change trends.
   - Generates a point plot to display trends over time for each cryptocurrency.

## Instructions for GitHub Readme

### Setup Instructions
1. Clone the repository to your local machine.
2. Install the required libraries
3. Run the script to fetch and analyze cryptocurrency data.

### Understanding the Analyzer
- The script fetches data for the top 15 cryptocurrencies and stores it in a CSV file (`API.csv`).
- The data analysis section calculates the mean percentage changes for different time intervals.
- Visualizations are generated using Seaborn, showing trends over time for each cryptocurrency.

### Note
- Ensure you have a valid CoinMarketCap API key for authentication (replace `'X-CMC_PRO_API_KEY'` with your key in the script).
- Adjust the duration and frequency of API requests based on your preferences.
