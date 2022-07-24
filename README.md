<img src = "https://www.cam.ac.uk/sites/www.cam.ac.uk/themes/fresh/images/interface/cambridge_university2.svg" width ="250" height ="250">

# Tweet data analysis

In this project we will conduct exploratory probability distribution fitting and a time-series analysis of twitter data to identify any trend or pattern over time.

*Code repository by Calbert Graham, University of Cambridge, U.K.* 


## Contents of respository

This repository contains the following files:
- fitting-probability-distribution-to-data.ipynb: the main file for the probability distribution analysis
- time-series-analysis.ipynb: the main file for the time series analysis
- tweet-time-series.txt: the tweet dataset used for both analyses
- License
- README.md
- .gitignore

## Prerequisites

To use this code, please ensure you have an up-to-date installation of [Python 3](https://www.python.org/downloads), preferably running in a [virtual environment](https://docs.python.org/3/tutorial/venv.html). The code was prepared in [Google Colaboratory](https://colab.research.google.com) and exported to Github. There may be minor compatibility issues. Please submit a pull request if you find any.

For fitting probability distribution, you will need to install the following Python packages: [numpy](https://numpy.org/install/), [SciPy](https://www.scipy.org/install.html), [matplotlib](https://matplotlib.org/stable/users/installing/index.html), [pandas](https://pandas.pydata.org/docs/getting_started/install.html), [seaborn](https://seaborn.pydata.org/installing.html). You might do something like `pip3 install numpy scipy matplotlib pandas seaborn` once you've [upgraded pip](https://pip.pypa.io/en/stable/installing/#upgrading-pip).

For the time series analysis, you will need to install the following additonal package: [statsmodels](https://www.statsmodels.org/stable/install.html)

If you run the code in Google Colab then packages will automatically be installed when the import command is run.

## Data structure
This experiment depends on data made available to the author by Dr Ling Wang from the School of Electronic Engineering and Computer Science, Queen Mry University. You can download the dataset and others from his [website](http://www.eecs.qmul.ac.uk/~linwang/download/ecs764/).

Here is a sample of the data included in the study:

| Times (seconds) | Number of tweets | 
| -------- | ------ | 
| 60000 | 33 | 
| 60001| 37 | 
| 60002| 27 | 
| 60003 | 37 |
| 60004 | 38| 
| ... | ...| 
| 69995 | 2 | 
| 69996 | 2|
| 69997 | 1 | 
| 69998 | 1 | 
| 69999 | 2| 

## Directory structure
Experiment output files will save to your working directory (i.e. where you download the repository and/or run the experiment from) unless you update the code. One easy way to download the entire repository is to click the link to the main page and add '/zipball/master/' to the URL - works like a charm.


## Citation

None required. Use as you see fit.


_Calbert Graham_, crg29@cam.ac.uk, _July 2022_

