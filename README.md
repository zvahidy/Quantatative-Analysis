# Quantatative-Analysis
I am currenlty working in the role of a quantitative analyst for a FinTech investing platform. This platform aims to offer clients a one-stop online investment solution for their retirement portfolios that’s both inexpensive and high quality. To keep the costs low, the firm uses algorithms to build each client's portfolio. The algorithms choose from various investment styles and options.

I've been tasked with evaluating four new investment options for inclusion in the client portfolios. Legendary fund and hedge-fund managers run all four selections. (People sometimes refer to these managers as whales because of the large amount of money that they manage). My goal was to determine the fund with the most investment potential based on key risk-management metrics: the daily returns, standard deviations, Sharpe ratios, and betas.

---

## Technologies
###### Resource 
- Data Availabe for download:
    - Whale_navs.csv: http://localhost:8889/lab/tree/Quantatative-Analysis/Resources/whale_navs.csv
    
###### Tools
Jupyter Lab
- Jupyter Notebook
- Pythons and Pandas Libraries
- Path from Pathlib
- NumPy
- %matplotlib incline


    

---

## Installation Guide

Installation requirements for this project included Pyton and Panda Libraries and JupyterLab (See Appendix)

Activate conda dev environment:

Activate conda dev environment:
![Activate conda dev environment](https://user-images.githubusercontent.com/107367097/177222060-bbe16acc-95cd-496c-aafd-0641b85024fb.png) 

JupyterLab is built into Anaconda therefore, run the following command to launch JupyterLab:
![JupyterLab](https://user-images.githubusercontent.com/107367097/177222194-5217273e-2187-4dea-b640-e175d21fc3b3.png)

JupyterLab user interface does NOT automatically open in a browser window, manually copy the URL provided in the terminal and paste into your browser:
![Interface url](https://user-images.githubusercontent.com/107367097/177222411-4aec31c1-5536-480a-b1fc-3ffb847440b9.png)

Once copied and pasted into your broswer, you will be able to see and use Jupyter Notebook:
![Jupyter Notebook](https://user-images.githubusercontent.com/107367097/177222682-f3073b3c-4d2f-4725-99d2-b1e18ecad9d4.png)
Begin data analysis by importing Panda:
![importing Panda](https://user-images.githubusercontent.com/107367097/177222941-d3f1ff41-8da5-485b-a9af-21c90b1c7021.png)
Import NumPy,Path, and %matplot inline:
![imports](https://imgur.com/7zDldsX)

---

## Results

Analyzed the csv file:
![whale navs](https://imgur.com/kvsAxtR)

Determined Volitility
![Volitility](http://localhost:8889/lab/tree/Quantatative-Analysis/screenshots/Volitility.png)
![](https://imgur.com/x1KtynG)

Plot Dataset
![Plot Data](https://imgur.com/Pexhh5o)

Calculate Standard Deviation:
![std](https://imgur.com/BhjM5IS)


Calculated rolling beta:
![beta](https://imgur.com/Ya5x42l)


Final Analysis: 
The results indicate that the S&P 500 out performed all portfolios. However, the portfolios that should be added out of the four researched with the best porfolio with risk-return is Berkshire Hathaway Inc. Although data shows high volitility, the returns indicate that the risk is worth the reward. The Sharpe and Beta data indicate that Paul & Co. Inc. would the least effective portfolio to be added to the suite of fund offerings.