# Japan Economy Data Scrapers from a database of wikipedia and excel files shared with me by Shizuka Inoue
# Python-project

# What does your project do?
Our Project relies on Japanese government data regarding Japan's Economy.
It takes Inflation rate of all items, and inflation rate of all items excluding food and energy.
It takes the expected inflation rate from 1983 - 2003
Nominal GDP and Real GDP
Suicide Rate
Consumption Index
Total Expected Inflation rate
we then scrape all these data from excel files provided from the Japanese Government's websites and also Wikipedia for (suicide rates)
we then change these information in respective graphs and pie charts

# What modules did you use, if any?

all the modules imported are listed below:

- import collections

- from pylab import *
- import matplotlib
- import urllib.request
- import collections
- import re
- import bs4
- import time
- import lxml

- import os

- from collections import defaultdict
- import zipfile                                                                                                                                                                                          
- import pandas as pd
- from pandas import DataFrame, read_csv
- import matplotlib.pyplot as plt
- import xlrd
- from bs4 import BeautifulSoup
- import requests

# Explain how we can run your project
- Make sure you include all python and data files
- If your project has graphics, include some snapshots
- Any documentation should be written in a notebook
    - do NOT submit ASCII/plain text, PDFs, Word files, etc.
- If for some reason it is not feasible for us to run your project, make an appointment with Larry to demo it

Explanation:

We will be sending you a zip file named efg2123-si2303.zip.
Inside this file there are 4 files
- a data file (where all our excel files are stored)
- a snapshot file where you can find snapshots of all our graphs
- EconData.py our program file that you can run on terminal with the command "python EconData.py"
- scrape.ipynb our program file that you can run in Jupyter Notebook (as the bulk of our testing was done there)

How to run on terminal:
1. Unzip the file "efg2123-si2303.zip" to get "efg2123-si2303"
2. Open "efg2123-si2303"
3. Unzip "Japan Econ.zip" to get "Japan Econ" our database file (PLEASE KEEP BOTH FILES)
4. Ensure "Japan Econ.zip", "Japan Econ", and EconData.py are all in the same directory before running
5. Run "python EconData.py"

How to run on Jupyter Notebook:
1. Unzip the file "efg2123-si2303.zip" to get "efg2123-si2303"
2. Open "efg2123-si2303"
3. Unzip "Japan Econ.zip" to get "Japan Econ" our database file (PLEASE KEEP BOTH FILES)
4. Ensure "Japan Econ.zip", "Japan Econ", and EconData.py are all in the same directory before running
5. Open up Jupyter Notebook scrape.ipynb and shift enter to run.

What our program does upon running our program (Terminal is pretty quick), (Jupyter takes awhile to load):
1. You will have 8 options 1-8, where we will ask you to enter in a digit 1-7 for the data graph you would like to see concerning the economic subjects of Japan
2. Each graph shows a specific trend of each variable
3. Options 4 and 6, produces two graphs each respectively, however, on terminal they overlap each other, as such, please move the windows in order to see the comparisons of Nominal GDP and Real GDP, as well as, Consumption index. (on jupyter notebook this problem does not exist)
4. if you are satisfied with the graphs and wish to exit please key in 8 and the program will exit

For Your viewing pleasure:
You can compare your results to ours in the snapshots of the graphs we provide for correctness and general consensus that it works


