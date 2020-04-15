# COVID-19 Data Analysis

Basic data analysis of the COVID-19 data provided by [Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19). 

### Technical:

* Code is written in Python 3 using a Jupyter Notebook.
* Graphics are generated with [Altair](https://github.com/altair-viz/altair).

## Instructions

1. Ensure Python 3 and pip3 are installed in your environment.
2. Clone the Repository.
3. Install the requirements.
4. Clone the [Johns Hopkins data](https://github.com/CSSEGISandData/COVID-19) into a subfolder of this repository. The subfolder should be called "COVID-19" by default.
5. Run the Jupyter notebook (COVID-19 Data Analysis.ipynb) and update cells as desired.

Steps 2-5 should go roughly like this:

```
git clone https://github.com/yeutterg/COVID-19-Data-Analysis
cd COVID-19-Data-Analysis
pip3 install requirements.txt
git clone https://github.com/CSSEGISandData/COVID-19
jupyter notebook
```

# Updating the Johns Hopkins Data

The Johns Hopkins repository appears to be updated about once per day with new daily statistics for each region. To get the latest data:

1. cd into the COVID-19 directory
2. From your terminal, do a git pull 
3. Open the Jupyter notebook and select Kernel > Restart and Run All

For example:

```
cd COVID-19
git pull origin master
cd ..
jupyter notebook
```