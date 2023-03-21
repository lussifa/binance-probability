Binance Bitcoin Trend Prediction Script

This is a Python script that predicts the trend of Bitcoin on Binance exchange using the Support Vector Machine (SVM) algorithm.
Requirements

To run this script, you'll need to have the following installed:

    Python 3.x
    ccxt library
    pandas library
    scikit-learn library

You can install the required libraries by running the following command:

sh

pip install ccxt pandas scikit-learn

Usage

    Clone this repository:

sh

git clone https://github.com/<your_username>/binance-bitcoin-trend-prediction.git

    Change directory to the cloned repository:

sh

cd binance-bitcoin-trend-prediction

    Run the script:

sh

python binance_trend_prediction.py

    The script will predict the trend of Bitcoin on Binance exchange for the next 5 minutes and output the probability of the trend being up or down. If the probability of the trend being up or down is greater than or equal to 70%, the script will record the current Bitcoin price and the highest and lowest prices over the next 5 minutes in a CSV file named result.csv.

License

This script is licensed under the MIT License.
