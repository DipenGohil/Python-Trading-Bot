# Python-Trading-Bot
Web-Scraped data from websites such as Wikipedia to get custom data that can be used for the QuantConnect trading algorithm.

I ran a backtest from Sept 2015 to October 2021, with starting amount being $50000, and the bot earned $64000.

<img width="538" alt="image" src="https://github.com/user-attachments/assets/c30eda97-7ec3-4404-bc0f-bade237f1a98">



Step 1:
    Use the fetchDataForTradingAlgorithm.ipynb python program to fetch custom data from the wikipedia page.

Step 2:
    Upload the csv file containing the data to your dropbox.

Step 3:
    Open QuantConnect, create your account and click 'Create New Algorithm'. Copy contents of main.py to your algorithm.
    
Step 4:
    Modify the dropbox link in the program by adding your dropbox link. Also change the tickers as per requirement in the trading algorithm.

Step 5:
    Click the run button.
