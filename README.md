# Random_Forest_Thesis_model
An automation model, developed for training, testing and predicting soil moisture implementing a Random Forest model.

# Installing a python environment
Miniconda is a minimal installer for conda and the simplest way to get started with python installation. 
The installer in the following link: https://www.anaconda.com/docs/getting-started/miniconda/main

Setting up the GEE configurations
The script relies on the Google Earth Engine python API to extract geospatial information from various layers hosted on Google premises. To utilize this data the end user must first authorize their account via Google. The authentication is a one-time process that will write a credential file to your local directory with a token. This token is written by typing earthengine authenticate in the Miniconda prompt.
