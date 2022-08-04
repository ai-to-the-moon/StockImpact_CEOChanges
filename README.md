# Effects of a CEO Change  
## Summary of Purpose  

This is not a program.  
This is just an analysis of the effects a CEO change has on the stock-price of a company.

We sought to find out the effects of a CEO change on companies of different sizes and from different sectors.  
To do this, we made a list of 20 companies with CEO changes in 2019.  
Then we obtained 6 years worth of the stocks' data, centered around the stocks' CEO-change-announcment dates.  
Next, we used this data to produce graphs & performance metrics like Sharpe ratios, rolling betas, etc.  
We then used these graphs & metrics to compare the performance of the stocks before & after the CEO change.
We also analyzed other pieces of data:  
previous CEO's years of service, new CEO's years of service, the reason for the change in guard (e.g. retirement, incompetence, scandal), the new CEO's experience, etc.    
Finally, we drew conclusions & laid out the patterns we found acrost the data.

---

## Required/Compatible Technologies

**Compatible OS's:** Mac, Windows, or Linux  
**Programming language:** Python in .ipynb format  
**Required libraries:**  

os  
requests  
json  
pandas as pd  
load_dotenv from dotenv   
alpaca_trade_api as tradeapi  
matplotlib.pyplot as plt  
numpy as np  
hvplot.pandas  
Path from pathlib   

%matplotlib inline  

datefrom from datetime   
timedelta from datetime   
datetime from datetime   

seaborn as sns   
 
Using a conda environment from anaconda is preferable.  

---

## Installation Guide

To view it, download the repository & open the .ipynb file with Jupyter Lab or some program that can run .ipynb files (e.g. VS Code using some extensions/add-ons).  
The cells should already have been run. If some haven't been run, then restart the kernel and run all the cells.

To view our hypotheses, write-up/conclusions, etc., click the google slides link [here](https://www.google.com).

---

## Usage

Usuage example:  
You are a company board-member considering a CEO change, and you want to know the potential effects of such a big decision.

Pictures of parts of the notebook:

![A picture of a graph](./usage_example1.png)  
![A picture of a data table](./usage_example2.png)  

---

## Contributors

Jake Wheeler  
email:   
git hub: JakeWheelerGitHub  

Jerome Bright  
email:  
git hub: JHBright  

Noah Saleh  
email: noahgsaleh@gmail.com  
git hub: Noah-Saleh  

Paula Koziol  
email:  
git hub: ai-to-the-moon  

---