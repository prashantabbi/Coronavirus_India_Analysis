# Coronavirus_India_Analysis
A Data Analysis project on the spread of the Novel Coronavirus in India. This project uses raw data in the form of .csv files and transforms it into a Data Analysis. This project is an attempt of analysing the coronavirus (Covid – 19) spread in India using data science concepts and analytics with the help of Python in the Jupyter Notebook interface. This analysis will help us find the basis behind common notions about the virus spread purely from a data perspective.
The data used in this project is spread across 2 files:
1.	Covid_19_india.csv
2.	Indian Coordinates.xls
For the analysis we have used the common Python libraries, such as NumPy, Pandas, Seaborn, matplotlib, stdlib, folium and fbprophet.

**The important packages imported are as follows:**
1. **Import pandas as pd:** 
Pandas is a python software package. It is a must to learn for data-science and dedicatedly written for Python language. It is a fast, demonstrative, and adjustable platform that offers intuitive data-structures. You can easily manipulate any type of data such as – structured or time-series data with this amazing package.
2. **Import NumPy as np**
NumPy is a popular array – processing package of Python. It provides good support for different dimensional array objects as well as for matrices. Numpy is not only confined to providing arrays only, but it also provides a variety of tools to manage these arrays. It is fast, efficient, and really good for managing matrices and arrays.
3. **Import matplotlib.pyplot as plt**
Matplotlib is a Python library that uses Python Script to write 2-dimensional graphs and plots. Often mathematical or scientific applications require more than single axes in a representation. This library helps us to build multiple plots at a time. You can, however, use Matplotlib to manipulate different characteristics of figures as well.
4. **Import seaborn as sns**
It is a library built on prime of matplotlib. it allows one to make their visualisations pretty and provide us with some of the common visualisation needs (like mapping a colour to a variable or using faceting). Seaborn is more integrated for working with pandas DataFrames
5. **Import plotly**
The plotly Python library is an interactive, open-source plotting library that supports over 40 unique chart types covering a wide range of statistical, financial, geographic, scientific, and 3-dimensional use-cases. Built on top of the Plotly JavaScript library (plotly.js), plotly enables Python users to create beautiful interactive web-based visualizations that can be displayed in Jupyter notebooks, saved to standalone HTML files, or served as part of pure Python-built web applications using Dash.
6. **Import folium**
Folium is a Python library used for visualizing geospatial data. It is easy to use and yet a powerful library. Folium is a Python wrapper for Leaflet. js which is a leading open-source JavaScript library for plotting interactive maps.

# Prediction and Forecasting
In python prediction and forecasting can be carried out with a help of “fbprophet” package.
Prophet is a facebook’s open source time series prediction. Prophet decomposes time series into trend, seasonality and holiday. It has intuitive hyper parameters which are easy to tune.<br /><br />
•	Trend models non periodic changes in the value of the time series.<br />
•	Seasonality is the periodic changes like daily, weekly, or yearly seasonality.<br />
•	Holiday effect which occur on irregular schedules over a day or a period of days.<br />
There are few advantages of using Prophet<br />
•	Accommodates seasonality with multiple periods<br />
•	Prophet is resilient to missing values<br />
•	Best way to handle outliers in Prophet is to remove them<br />
•	Fitting of the model is fast<br />
•	Intuitive hyper parameters which are easy to tune

# Results of Project Functions
1.	In this project two files are imported.<br />
Covid_19_india.csv<br />
Indian Coordinates.xls<br />
2.	Data is prepared for analysis with the help of data cleaning by removing, modifying that is incorrect, incomplete, irrelevant, duplicated or improperly formatted.
3.	Merging operation is done by joining two data frames. In this way information about a particular entity common to both the two datasets.
4.	Pie charts are plotted for each state separately and for overall country data.<br />
•	States like Maharashtra, Gujarat, MP, West Bengal have a death rate of nearly 5 percent<br />
•	States like Tamil Nadu, MP, UP, Rajasthan, Andhra Pradesh, Telangana, Haryana, Kerala have more than 50% recovered cases<br />
•	Punjab has almost 90% recovered cases<br />
•	No deaths have been recorded in Tripura, Goa, Ladakh, Puducherry and Manipur<br />
•	Andaman and Nicobar Islands have all the cases recovered<br />
•	Dadar and Nagar Haveli, Sikkim, Nagaland has all active cases<br />
•	Maharashtra has highest number of cases recorded<br />
•	Overall in India, 53% are active, 3% have died and 44% have recovered<br />

5.	Merging of two datasets based on the state column was performed. Data repetition, Extra spacing, slight changes in name of the state was corrected and removing the not common data for both the data sets.
6.	Visualization was carried out using folium package. Maps were plotted indicating the Covid hotspots.
7.	Prediction was carried out using timeseries fbprophet model and graphs were plotted indicating actual values and predicted values.

