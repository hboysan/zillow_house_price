# zillow_house_price
Intro:

The purpose of this project was to predictable calculate the price fluxuation of the housing market of North Carolina,based off of the last 5 years worth of data. The data for this project was accumulated through the zillow API and was called via Python 3 (run on top of Jupyter notebook) this data dump was interpreted through a linear resgressive model. And the algorhythm created allowed users to plug in an x (price) and y (date) to achieve a priece rate increase or decreace percentage. Flask app was used to wrap this script along with a engine launch for Postgre SQL, where the data was stored in specified tables. Visualizations of future projections for the areas which may contain the greatest (+/-) rate change were created in Tableau Workbook.

Practical Uses:

This developed program is a very basic level machine learning example. Because there were only 1 x-train and 1-y train varible used, it would be somewhat impractical to consider this completely reliable for an accurate estimate of the housing market. To further strenthen this model, one should consider obtaining data about number of jobs posted in the zip code, schools being built, or crime rates in the area. There are many contriubting factors that influence the housing market, but for the sake of this project our goal was to over simplify machine learning on a large dataset, to show the possibilties of a predictive model. 

Dependencies:
Jupyter Notebook v4.1.1
Posgre SQL v11.3 
Tableau 10.4
Python 3.7 
About 3.2gb of device storage space
