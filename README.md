"# InternetsNewBillboard" 
Running order
	AllSteamAppIds
	concurrentPlayers
	SteamComunityAppIds
	ConcurrentPlayers
	CompiledPlayerData
	ItemsPerGame
	MarketHistoryPerItemRequest
	MarketHistoryDatasheetCreation
	manyToOneCsv
	SecondCsvCompiule
	MarketGrandTotals
	NormalizeGameDataToSalesData
	SalesAsAPerportionOfItemsAverageCost
	Twitch_Data_Collector
	MainData_Analysis
	
DO NOT run this in full, extremely long running times
 
Data that is withing this project is the results page for the market data and as that is the most valuable along with the player data. 

How to install selenium 
https://selenium-python.readthedocs.io/installation.html

imports used: 
	import csv
	import json
	import threading
	import pandas as pd
	from os import listdir
	from os.path import isfile, join
	from glob import glob
	import os
	import shutil
	from selenium import webdriver
	from selenium.webdriver.common.keys import Keys
	from bs4 import BeautifulSoup
	from pathlib import Path
	import matplotlib.pyplot as plt
	import seaborn as sns