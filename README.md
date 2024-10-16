# SparkDemo
Code snippets for Spark! demos

# Getting Started
1.) Make a GitHub account (a platform built on top of git to share code and collaborate with others)

- https://github.com/

2.) Install Git (version control system which manages your code's history)

- https://git-scm.com/downloads Download the appropriate version for your operating system.

3.) Clone (or fork) this repo locally

- Using a command line (or Git Bash) run:
  - `git clone https://github.com/BuechnerGIS/SparkDemo.git`
- Change directories into the SparkDemo folder
  - `cd ./SparkDemo`

4.) Configure your environment
- Create a python virtual environment
  - `python3 -m venv ./venv`
- Activate the virtual environment
  - _Windows_
    - `./venv/bin/activate`
  - _Mac/Linux_
    - `source ./venv/bin/activate`
- Install modules
  - `python3 -m pip install -r ./requirements.txt`
- Start Jupyter Notebook Server
  - `python3 -m notebook`

5.) Open your local Jupyter Server
- Navigate to http://localhost:8888/tree in a web browser
- Use the Notebook to step through the exercise


# Exercises

## Pull OSM data you created!
Write a query to download your data from https://overpass-turbo.eu/.
Download as a GeoJSON.
- Convert to a Shapefile (QGIS)
- Add to a Leafmap map in Jupyter Notebook

## Query the data
Explore your data using `<dataframe-name>.query()` function
