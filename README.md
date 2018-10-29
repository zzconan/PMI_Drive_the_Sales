# PMI_Drive_the_Sales

## Overview
Every company wants to succeed and gain an edge on the competition. Achieving the revenue goals translates into maximizing sales. Many companies distribute their goods at physical Point Of Sales (POSs). For all of them the challenge is to devise a strategy that will drive the sales at POSs. Possible solution could be to place the product in the most convenient location for consumers. In this assignment, we will ask you to figure out what surroundings and respective amenities lead to top POS performance. 

## Data source

For performing this analysis, please use following data sources:
•	‘sales_granular.csv’ - contains information about the sales volumes of a product at particular POS; each POS is uniquely identified by 'store_code'.
•	‘Surroundings.json’ - contains information about 90 different amenities (restaurants, shops, beauty salons etc.) that are in the surroundings of each POS.


## Dependencies

This project has been developed on python 3.6.5, although it should be run on any python 3.x distribution

Used packages (conda):
```
- jupyter==1.0.0
- ipython==6.4.0
- numpy==1.12.1
- pandas==0.20.1
- scikit-learn==0.19.1
- matplotlib==2.0.2
- seaborn==0.7.1
- scipy==1.0.1
```
Recommend install packages or code
```
Feature selection tool 1 rfpimp
-pip install rfpimp; 
ref: http://explained.ai/rf-importance/index.html or https://github.com/parrt/random-forest-importances/blob/master/notebooks/pimp_plots.ipynb

Feature selection tool 2 feature_selector
-This needs the use code from https://github.com/WillKoehrsen/feature-selector/tree/master/feature_selector
```
