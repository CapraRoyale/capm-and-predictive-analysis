# Group Project

## CAPM and predictive analysis

### A stock data exploration by [Bruno A](https://github.com/basobo), [Ihar Z](https://github.com/IharZ), [Siege L](https://github.com/CapraRoyale)

---

## Project Proposal

* Our project is focused on looking at historical patterns of stock performance, establishing their individual CAPM, and predicting the future performance of these stocks over Fiscal Year 2020 and how that compares to their ACTUAL performance during this unprecedented time. We'll use data from Googale/Yahoo finance to compare and contrast.

* How have stocks performed in 2020 when compared to their predicted return rate from historical data?

* Compare ACTUAL performance of several index stocks, hand-picked stocks and random stocks to their predicted return.

### Relevant Definitions

* **Alpha** - a measure of an investment's performance, when compared to a related stock market index (i.e. S&P 500). It is often used to describe an investment's "edge" on the market, or it's "abnormal rate of return".
* **Beta** - A measure of volatility of an asset when compared to the market as a whole. (i.e. a beta of 1 indicates the asset is as volatile as the entire market)
* **CAPM** - Capital Asset Pricing Model is a way of describing the relationship between systematic risk and an asset's expected return, generally stocks.

## Data Cleanup & Analysis

* **Exploration and Cleanup** - [Capital_project.ipynb](./Capital_project.ipynb)

  * [X] Import, clean, normalize data and calculate alpha, beta and CAPM

* **Analysis and Display** - [Dashboard.ipynb](./Dashboard.ipynb)

  * [X] Plot data and compare predicated vs actual

  * [X] Aggregation, correlation, comparison, summary statistics, and financial analysis.

## Technical Requirements

* [x] Use Pandas to clean and format our dataset(s).

* [x] Jupyter Notebook - *data exploration and cleanup* process

* [X] [Jupyter Notebook](./dashboard.ipynb) - *final data analysis*

* [X] PyViz, Panel, Plotly Express, and Hvplot

  * [X] Create six to eight visualizations of our data

  * [X] Aggregate these visualizations into a dashboard.

  * [ ] Save PNG images of our visualizations

* [X] new Python library

* [X] Optional API - **Yahoo Finance**

* [ ] OPTIONAL - Input box in panels/dashboard for entering stock ticker