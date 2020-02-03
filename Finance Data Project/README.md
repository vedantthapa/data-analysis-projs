
# Project: Analysis of Finance Data

In this data project we will focus on exploratory data analysis of stock prices. Keep in mind, this project is just meant to practice visualization and pandas skills, it is not meant to be a robust financial analysis or be taken as financial advice.

Let's focus on bank stocks and see how they progressed throughout the [financial crisis](https://en.wikipedia.org/wiki/Financial_crisis_of_2007%E2%80%9308) all the way to early 2016.

___
### Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)
- [Scipy](https://www.scipy.org/)
- [Plotly](https://plot.ly/)
- [cufflinks](https://plot.ly/python/v3/ipython-notebooks/cufflinks/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. 


### Run

In a terminal or command window, navigate to the top-level project directory `Finance Data Project/` (that contains this README) and run one of the following commands:

```bash
ipython notebook Finance_Data_Project.ipynb
```  
or
```bash
jupyter notebook Finance_Data_Project.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### Data
We read the data from [Yahoo Finance](https://in.finance.yahoo.com/) using pandas!  You'll need to install [pandas-datareader](https://github.com/pydata/pandas-datareader) for this to work! Pandas datareader allows you to read stock information directly from the internet. Use the given link for install guidance (*pip install pandas-datareader*)
