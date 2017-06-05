Analyzing-Type-1-Diabetes-and-AURIN-Data-on-Jupyter
-----------------------------------------------------------------------
##Function description:
This program is based on JupyterLab with Python3.5 kernel. It tries 
to obtain data sets from AURIN OpenAPI and link the data with Type 1 Diabetes
patients distribution.
It use Python library Bokeh to visualize data and presents a interactive map.
＃#Preparations
This project is written by Python version: 3.5. 
A AURIN OpenAPI account is required to apply. Username and password should be saved in the openapi.cfg.

To run the .ipnb file, the Jupyter Notebook is required. The download link is: <http://jupyter.org/install.html>

## Required Libraries:
Except some common packages like numpy, math, csv, etc, some special packages are required as well. A brief introduction and installing command is shown below:

_urllib: Provides a high-level interface for fetching data across the World Wide Web. Install by command:

		pip3 install urllib3

_dbfread: Reads DBF files and returns the data as native Python data types for further processing. Install by command:

		pip3 install dbfread

_geojson: This library implements all the GeoJSON Objects described in The GeoJSON Format Specification like Point, Polygon,etc.Install by command:

		pip3 install geojson

_pyshp: The Python Shapefile Library (pyshp) provides read and write support for the Esri Shapefile format. Install by command:

		pip3 install pyshp

_bokeh: A Python interactive visualization library that targets modern web browsers for presentation. Install by command:

		pip3 install bokeh

_minepy: This library provides an ANSI C library for the Maximal Information-based Nonparametric Exploration (MIC and MINE family). Install by command:

		pip3 install minepy

_sklearn: A free software machine learning library for the Python program. Install by command:

		pip3 install minepy

----------------------------------------------------
###Author: Zhanyi Qi
###Email: <zhanyiq@gmail.com>
###Major: Master of Information Technology 
###Organization:The University of Melbourne
