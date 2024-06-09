# Basic Cryptocurrency Portfolio Tracker
Developed a basic cryptocurrency portfolio tracker application using Python.

The application allows users to input their cryptocurrency holdings and track their portfolio's value in real-time. Implemented features include fetching live cryptocurrency prices, calculating portfolio performance and displaying graphical visualizations.

## Skills Utilized: 
- Python
- API integration
- data manipulation
- portfolio analysis
- data visualization


# Technology Stack:
- Python
- Requests library for API requests
- Matplotlib for data visualization
- JSON for data parsing

## Setup:
- Install Python and the required libraries (requests, matplotlib)
- Obtain an API key from CoinGecko and replace "YOUR_API_KEY" in the code with your actual API key

## Requirements:
- Python 3.6 or higher
- Requests library
- Matplotlib library
- CoinGecko API key

## Output:
- Prints a summary of the portfolio, including the quantity, price, and value of each cryptocurrency
- Prints the total portfolio value
- Displays a bar chart showing the value breakdown of the portfolio

## Explanation:
- The code first defines the API endpoint and headers for the CoinGecko API.
- It then prompts the user to input a comma-separated list of cryptocurrency symbols and their quantities.
- The code translates the user input to CoinGecko IDs and prepares parameters for the API request.
- It then fetches cryptocurrency data from the API and updates the portfolio with price and value information.
- Finally, it prints the portfolio summary and displays a bar chart using Matplotlib.
