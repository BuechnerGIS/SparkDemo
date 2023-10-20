# SparkDemo
Code snippets for Spark! demos

# Getting Started

## Install Git
https://git-scm.com/downloads
Download the appropriate version for your operating system.

## Make a GitHub account
https://github.com/

## Clone (or fork) this repo locally
### Using a command line (or Git Bash) run
git clone https://github.com/BuechnerGIS/SparkDemo.git

## Change directories into the SparkDemo folder
cd ./SparkDemo

## Create a python virtual environment
python3 -m venv ./venv

## Activate the virtual environment
### Windows
./venv/bin/activate
### Mac/Linux
source ./venv/bin/activate

## Install modules
python3 -m pip install -r ./requirements.txt

## Start Jupyter Notebook Server
python3 -m notebook

## Open Jupyter 
Navigate to http://localhost:8888/tree in a web browser

## Use the Notebook to step through the exercise


# Exercises

## Pull OSM data you created!
Write a query to download your data from https://overpass-turbo.eu/.
Download as a GeoJSON.
- Convert to a Shapefile (QGIS)
- Add to a Leafmap map in Jupyter Notebook

## Query the data
Explore your data using `<dataframe-name>.query()` function
