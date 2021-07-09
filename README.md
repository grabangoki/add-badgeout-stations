# Adding Badgeout Stations

This jupyter notebook makes it easier to add badgeout stations. It defines a ShopperData class which provides an interface for the following:
* getting the unique identifiers for the stores based on their (real) brand name
* adding/updating a badgeout_station to a store

Under the hood, it's just making HTTP requests to Shopperdata. Please feel free to modify it as you see fit.

# Requirements

You will need `python3`, `jupyterlab` and `requests`. If you have [pipenv](https://pipenv.pypa.io/en/latest/), just run `pipnev shell`.

