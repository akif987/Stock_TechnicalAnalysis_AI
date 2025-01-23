# Stock_TechnicalAnalysis_AI
Project: AI-Powered Technical Analysis Stock Dashboard

This project demonstrates how to build a stock dashboard that leverages AI and machine learning to perform technical analysis on stocks.

Tech Stack:

Python,
Streamlit,
yfinance,
Pandas,
Plotly,
Ollama,
Meta's Llama 3.2-Vision,

Features:

Visualize stock charts ,
Apply technical analysis indicators ,
Generate insights from a large language model ,

Disclaimer

Important Note: This  is not financial or investing advice. It is for Exprimental purpose only. How to use AI/LLM vision models in Python. Also, don't blindly trust the results of LLM model results without critical thinking or subject matter expertise . LLM's are still experimental technology that have high error rates.   

Getting Started

Clone this repository
Set up a virtual environment
Install the required libraries (pip install -r requirements.txt)
Run the application (streamlit run main.py)
Here's a step-by-step guide on how to use the code provided in the video:

1. Set up your environment:

Install Ollama:
Download and install Ollama from their official website.
Open your terminal or command prompt and run: oama run llama3.2-dvision to install the Llama 3.2 Vision model.
Create a Python environment:
Create a new virtual environment using virtualenv or conda.
Activate the environment.
Install required libraries:
Install the necessary libraries using pip:
Bash

pip install streamlit yfinance pandas plotly requests opencv-python

2. Obtain the code:

Copy the code from the video description or download the code file.

3. Run the app:

Save the code as a Python file (e.g., ai_technical_analysis.py).
Open your terminal or command prompt and navigate to the directory where you saved the file.
Run the following command:
Bash

streamlit run ai_technical_analysis.py
This will open the app in your web browser at http://localhost:8501/.

4. Use the app:

Input stock ticker: Enter the stock ticker symbol (e.g., AAPL) in the sidebar.

Select date range: Choose the start and end dates for the analysis.

Click "Fetch Data": Retrieve the stock data for the specified ticker and date range.

Select technical indicators: Choose the technical indicators you want to overlay on the chart (e.g., 20-day SMA, 20-day EMA, Bollinger Bands, VWAP).

Click "Run AI Analysis": Trigger the AI-powered analysis. The app will send the chart to the Llama 3.2 Vision model for analysis.

View results: The app will display the AI's analysis results, including a buy, hold, or sell recommendation and the reasoning behind it.
