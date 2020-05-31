# Visualizing Geographic Data 

Exploring the fundamentals of geographic coordinate systems and how to work with the basemap library to plot geographic data points on maps. 

# Dataset

We'll be working with flight data from the openflights website. Here's a breakdown of the files we'll be working with and the most pertinent columns from each dataset:

* **`airlines.csv`**: data on each air line
> * `country` - where the airline is headquartered.
> * `active` - if the airline is still active.
* **`airports.csv`**: data on each airport.
> * `name` - name of the airport.
> * `city` - city the airport is located.
> * `country` - country the airport is located.
> * `code` - unique airport code.
> * `latitude` - latitude value.
> * `longitude` - longitude value.
* **`routes.csv`**: data on each flight route.
> * `airline` - airline for the route.
> * `source` - starting city for the route.
> * `dest` - destination city for the route.

# Questions

1. For each airport, which destination airport is the most common?
2. Which cities are the most important hubs for airports and airlines?
