
# Project Title: Forecasting Net Prophet

We will use Python programming skills to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock.

We will:
Find unusual patterns in hourly Google search traffic
Mine the search traffic data for seasonality
Relate the search traffic to stock price patterns
Create a time series model with Prophet

---

## Technologies:

The project uses python 3.7 with the following packages:

* [pystan](https://pystan.readthedocs.io/en/latest/) - It's a platform for statistical modeling and high-performance statistical computation

* [hvplot](https://hvplot.holoviz.org/) - Provides an alternative for the static plotting API provided by Pandas and other libraries

* [fbprophet](https://facebook.github.io/prophet/) -  It's a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects

* [holoviews](https://holoviews.org/) - It's esigned to make data analysis and visualization seamless and simple


---

## Installation Guide


Before running the application first install the following dependencies:

```python
import pandas as pd
import holoviews as hv
from fbprophet import Prophet
import hvplot.pandas
import datetime as dt
%matplotlib inline
```

---

## Usage

To run the financial tool program, simply clone the repository, and go through the written steps in the *.ipynb file.

---

## Contributors

Jung Kim


---

## License

MIT License
