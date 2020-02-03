
# Project: Analysis of Emergency 911 Calls 

### Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. 


### Run

In a terminal or command window, navigate to the top-level project directory `911 calls Analysis/` (that contains this README) and run one of the following commands:

```bash
ipython notebook 911_Calls_Data .ipynb
```  
or
```bash
jupyter notebook 911_Calls_Data .ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

This dataset consists of 99492 data points, with 9 features. This dataset is provided by provided by montcoalert.org and can be found on [Kaggle](https://www.kaggle.com/mchirico/montcoalert).

**Features**
1.  `lat`: Latitude.
2. `lng`: Longitude.
3. `desc`: Description of the Emergency Call.
4. `zip`: Zipcode.
5. `title`: Title.
6. `timeStamp`: YYYY-MM-DD HH:MM:SS.
7. `twp`: pupil-teacher ratio by town.
8. `addr`: Address.
9. `e`: Dummy variable (always 1).
