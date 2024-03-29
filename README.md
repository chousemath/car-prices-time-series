# Car Prices Project - Time Series Data

### Project Goal

> Create a time series data viewer for the data accessible at the endpoint below. You should access the data using HTTP GET request. Use any HTML/CSS/JS frontend framework you are comfortable with. Please include the following features:
> * Filter by `year`
> * Filter by `price` range (min and max)
> * Filter by user-friendly time range (min and max)
> * Average price of displayed data (after the filter) should always be shown
> * Total number of displayed data points (after the filter) should always be shown
> * You should be able to add data points (need to designate the `year`, `price`, and `id` of the car, and corresponding date/timestamp)
> * You should be able to remove data points
> * You should be able to update data points (note that each data point has an `id` attribute)
> * Don't worry too much about performance
> * Please upload your code to github and share

### Data GET Endpoint

* `https://raw.githubusercontent.com/chousemath/car-prices-time-series/master/prices.json`
* The unit of `price` is `만원`
* `13년` and `13년(14년형)` should be seen as two different years
* `unix_timestamp` is in seconds

### Things We Would Like to See

* Knowledge of REST
* Proficiency in frontend technologies
* Proficiency in functional javascript (map, filter, reduce)