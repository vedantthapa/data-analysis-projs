# Project: High Rated Games on Google Playstore

Google Play Store serves as the official app store for the Android operating system, allowing users to browse and download applications. Success of an app is largely determined by its ratings.

But is there any particular pattern among high rated apps? Does size or genre of the app play a role in determining its high rating?

Let's find out by conducting an EDA on the Google Play Store data and try to explore whether given the data, ratings of an can be predicted.


### Why solve this project?
This project provides a better understanding of certain methods of EDA and Data Preprocessing. In this project, you will apply the following concepts.

 - Removing Missing Values.
 
 - Cleaning Data.
 
 - Exploring Data through various plots.
 
___
### Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. 

### Run

In a terminal or command window, navigate to the top-level project directory `Google Playstore/` (that contains this README) and run one of the following commands:

```bash
ipython notebook Google_Playstore.ipynb
```  
or
```bash
jupyter notebook Google_Playstore.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

This dataset was found on [kaggle.](https://www.kaggle.com/lava18/google-play-store-apps#googleplaystore.csv)
The dataset has details of 10841 entries with following 13 features.

**Features**
1. `App`: Name of the app.
2. `Category`: Category the app broadly belongs to.
3. `Rating`: Customer rating of the app.
4. `Reviews`: Number of Reviews by the audience.
5. `Size`: Size of the app.
6. `Installs`: Number of Installs done for the app.
7. `Type`: Type of the app(Free/Paid).
8. `Price`: Price of the app(if any).
9. `Content Rating`: What age group is the app appropriate for.
10. `Genre`: What all genres the app belongs to.
11. `Last Updated`: Date on which the app was last updated.
12. `Current Ver`: Version of the app.
13. `Android Ver`: Android Version required by the device to the run the app.
