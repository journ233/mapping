# Mapping

How to geocode using Census Geocoder and map using Kepler GL.

Install Python 3.9.18 via pyenv for best results. Kepler GL does not support Jupyter Lab 4, so Jupyter Lab 3 must be installed.

```sh
% pip install -r requirements-3.9.18.txt
```


## Lecture 1205

This lecture covers the steps to geocode data using the Census Geocoder. Note that the Census Geocoder cannot always provide data for business addresses.

You will need to install a number of packages to make this work. You should already have `brew` installed on your computer from a previous lecture. Run the following lines in your Terminal:

```sh
% brew update
% brew install gdal
```

This will likely take a little bit of time.

Then you'll need to install various Python packages. If you're running a Python 3.9.4 virtual environment, you can run the following code from the root of this repo:

```sh
% pip install -r requirements-3.9.4.txt
```

If you're not running a 3.9.4 virtual environment, then in whatever Python environment you're using, enter the following command:

```sh
% pip install pandas geopandas altair jupyter jupyterlab censusgeocode rtree pygeos
```
