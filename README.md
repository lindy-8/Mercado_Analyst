# Mercado Traffic Analyst
This application was created using a jupyter notebook within Google Collab. It utilizes time series and Facebook prophet predictions to observe trending Google searches and Mercado searches to provide helpful data that will improve marketing efforts and stock predictions. 
---

## Technologies & Libraries

This project utilizes python 3.7 with the following packages:

* [Pandas](https://github.com/pandas-dev/pandas) - For the command line interface, help page, and entrypoint.

* [Hvplot](https://github.com/holoviz/hvplot) - A high-level plotting API for pandas, dask, xarray, and networkx built on HoloViews.

* [Metaplot](https://github.com/matplotlib/matplotlib) - For entrypoint and help page.

* [Prophet](https://github.com/facebook/prophet) - Tool for producing high quality forecasts for time series data that has multiple seasonality with linear or non-linear growth.

---

## Pre installation Guide

*Note if you are running it on the cloud, versus locally, you will have to run all line of codes to properly use the application. 
Prior to running the application and code, please install the following dependencies:

```
from IPython.display import clear_output
try:
  !pip install pystan
  !pip install prophet
  !pip install hvplot
  !pip install holoviews
except:
  print("Error installing libraries")
finally:
  clear_output()
  print('Libraries successfully installed')
``` 

```
import pandas as pd
import holoviews as hv
from prophet import Prophet
import hvplot.pandas
import datetime as dt
%matplotlib inline
```


---

## Contributors

DU Starter Code

Ben Lindauer

---

## License

MIT
