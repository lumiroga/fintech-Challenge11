# Challenge XI | Fintech <img src="https://instructure-uploads-pdx.s3.us-west-2.amazonaws.com/account_150420000000000001/attachments/590996/columbia.png" height="48" width="48">
---
This project is the tenth challenge for the Columbia Fintech Bootcamp.

This challenges is about Time Series Analysis and Time Series Forecasting

The data used is a set of Different Data from Mercado Libre, the largest online shop in Latin America

The source data includes: 
* [Google Search Trends](./Resources/google_hourly_search_trends.csv)
* [Mercado Libre Daily Revenue](./Resources/mercado_daily_revenue.csv)
* [Mercado Stock Price](./Resources/mercado_stock_price.csv)

--

## Technologies

The main language is Python, with the following auxiliary modules/libraries.
Python version is 3.7, developed in an independent conda virtual environment

### pandas
This module handles DataFrames (dynamic tables), to maniupulate, store data, do automatic calculations and adding dynamic data.

### Prophet
Facebook library used to create forecast based on Time Series, it facilitates the generation of forecasts and produces very detailed results and graphs for analysis

### pathlib
This module helps abstracting the OS discrepancies between folder structures and files.

### numpy
Library for generic Math calculations (in this case average)

### Holoviews
Library to interface Hvplot with Colab (And in this case VSCode), without the  hv.extension('bokeh') command, Hvplot graphs are not displayed

---


### Clone repository`
`git clone https://github.com/lumiroga/Fintech_Challenge11.git`
---

## Usage

Open the terminal

Go to solution folder in your local computer

`cd ./Fintech_Challenge11`

`jupyter forecasting_net_prophet.ipynb`


---

## Contributors

[lumiroga](https://github.com/lumiroga)

---

## License

* mpl-2.0 | Mozilla Public License 2.0