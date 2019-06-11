# Car Prices Project - Time Series Data

### Project Goal

> Create a time series data viewer for the data accessible at the endpoint below. You should access the data using HTTP GET request. Use any HTML/CSS/JS frontend framework you are comfortable with. Please include the following features:
> * Filter by `year`
> * Filter by `price` range (min and max)
> * Filter by user-friendly time range (min and max)

### Data GET Endpoint

* `https://raw.githubusercontent.com/chousemath/car-prices-time-series/master/prices.json`
* The unit of `price` is `만원`
* `13년` and `13년(14년형)` should be seen as two different years
* `unix_timestamp` is in seconds