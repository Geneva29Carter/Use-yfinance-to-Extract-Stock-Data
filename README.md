# Use-yfinance-to-Extract-Stock-Data

#Using the Ticker function enter the ticker symbol of the stock we want to extract data on to create a ticker object. The stock is Tesla and its ticker symbol is TSLA

import yfinance as yf
import pandas as pd 

tesla=yf.Ticker('TSLA')
!wget https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/data/apple.json
import json
with open('tesla.json') as json_file:
    tesla_info=json.load(json_file)
    print(tesla_info)
