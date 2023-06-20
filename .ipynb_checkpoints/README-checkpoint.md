# 11_time_series_prophet_forecast

With over 200 million users, MercadoLibre is the most popular e-commerce site in Latin America. This project analyzes the company's financial and user data in an effort to find clever ways to make the company grow. The goal is determine if the ability to predict search traffic can translate into the ability to successfully trade the stock.

This Jupyter notebook contains data preparation, analysis, and visualizations for all the time series data that the company needs to understand in order to try to drive revenue. Specifically, this file contains the following:

- Visual depictions of seasonality (as measured by Google Search traffic) that are of interest to the company.
- An evaluation of how the company’s stock price correlates to its Google Search traffic
- A Prophet forecast model that can predict hourly user search traffic
- A plot of a forecast for the company’s future revenue

## Technologies

Programming Languages: Python 3.7.13

Interactive Development Environment: JupyterLab & Google Colab


Libraries: 
- Pandas - A Python library that is used for data manipulation, analysis, and visualization. 
- Sqlalchemy - An open-source SQL library for Python designed to ease the communication between Python-based programs and databases. 
- Voilà - A Python library which allows you to convert a Jupyter notebook into a live webpage. 
- Numpy - A popular open-source numerical computing library for Python which provides a powerful array object and a collection of mathematical functions. 
- HvPlot - A Python library that provides a high-level interface for quickly creating interactive plots and visualizations using popular plotting libraries such as Matplotlib, Bokeh, and Plotly.
- Warnings - A Python library that provides a way to handle warning messages that may occur during the execution of a program.

Operating System(s):  Any operating system that supports Python, including Windows & macOS.

## Installation Guide

To run this analysis, make sure you install the necessary dependencies:

1. Install Python: https://www.python.org/downloads/
2. Install and run Jupyter Lab:  https://jupyter.org/install
3. Install Anaconda: https://docs.anaconda.com/free/anaconda/install/
4. Install the necessary libraries using pip, the package installer for Python:
```
pip install pandas numpy hvplot SQLAlchemy
```
To check if sqlalchemy is already installed, run the following command:
```
 conda list sqlalchemy
```
If it is installed, the following should be displayed:
![sqlalchemy_install](sqlalchemy_install.png)

To install Voilà, run the following command:
```
conda install -c conda-forge voila
```
After installation for voila is complete, the following should be displayed:
![voila_install](voila_install.png)

5. Clone the repository: `git clone "https://github.com/mikenguyenx/7_passive_investing_sql"` using git or download the ZIP file and extract it to a local directory.


## Usage

To run the script for the Fund Portfolio Risk Return Analysis:

1. Open a terminal or command prompt and navigate to the directory with the analysis.
2. Launch Jupyter Lab: jupyter lab.  Alternatively, you can use Google Colab: https://colab.research.google.com/
3. Open `etf_analyzer.ipynb` in Jupyter Lab / Google Colab.
4. Run the code cells by clicking on the run button or by pressing the `Shift + Enter` key combination to load and preprocess the data, and generate visualizations
5. This project involves building a financial database and web application by using SQL, Python, and the Voilà library to analyze the performance of a hypothetical fintech ETF.

## Cumulative Returns Interactive Plot

![cumulative_returns](cumulative_returns.png)

## Web Application Deployment (Voilà) 

[voila_clip.webm](https://github.com/mikenguyenx/7_passive_investing_sql/assets/127016510/6e6791be-6e7a-4e0b-85b2-afb56c43171f)


## Contributors

Mike Nguyen


## License

MIT