# Spatial Data Analysis Project
This repository contains a project focused on the spatial data analysis of population differences between the years 2002 and 2014 in Poland. The project involves the use of visualizations with maps and GIS data to highlight demographic changes over this period.

## Introduction
This project analyzes spatial data to showcase the differences in population in Poland between the years 2002 and 2014. The analysis is visualized using maps and Geographic Information System (GIS) data to provide a clear and insightful view of demographic changes over the years.

## Project Structure
spatial-data-analysis/\
│\
├── dane/\
│   ├── wojewodztwa/\
│   │   ├── pop_2002.csv\
│   │   ├── pop_2014.csv\
│   │   ├── smierci.csv\
│   │   ├── szpitale.xlsx\
│   │   ├── uro_2002.csv\
│   │   ├── uro_2003.csv\
│   │   ├── uro_2004.csv\
│   │   ├── uro_2005.csv\
│   │   ├── uro_2006.csv\
│   │   ├── uro_2007.csv\
│   │   ├── uro_2008.csv\
│   │   ├── uro_2009.csv\
│   │   ├── uro_2010.csv\
│   │   ├── uro_2011.csv\
│   │   ├── uro_2012.csv\
│   │   ├── uro_2013.csv\
│   │   ├── uro_2014.csv\
│   │   ├── woje_uro.csv\
│   └── ...\
├── .gitignore\
├── project.ipynb\
└── README.md\

## Data Sources
The data used in this project includes:

- Population data for the years 2002 and 2014 (pop_2002.csv, pop_2014.csv)
- Birth data from 2002 to 2014 (uro_2002.csv to uro_2014.csv)
- Death data (smierci.csv)
- Hospital data (szpitale.xlsx)
- Combined birth data (woje_uro.csv)
- wojewodztwa/ - folder containing GIS data required for visualisation

These datasets provide a comprehensive view of the demographic changes in Poland during the specified period.

## Prerequisites
Python 3.x
Jupyter Notebook
Required Python libraries: pandas, geopandas, matplotlib, folium
