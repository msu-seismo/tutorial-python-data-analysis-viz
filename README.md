# python-data-analysis-viz
## Min Chen (chenmi22@msu.edu), Tong Zhou, Ziyi Xi, and Jiaqi Li
## MSU Data Science and Computational Seismology Lab 
## Last updated on June 9, 2019


This repository contains .pdf and .ipynb files and input data files.
Our aim is to teach python beginners: 
1. how to set up Jupyter Notebook and install all the dependancies
2. how to read in csv file into python using pandas
3. how to plot data in python for further data visualization and analysis using pandas, geopandas, obspy, matplotlib, and numpy packages.

In order to import geopandas in python_data_viz_analysis.ipynb, 
you need to create a new env for it to run properly.
Please run the following command lines in your terminal to set up and activate the environment.

bash
conda config --add channels conda-forge
conda config --set channel_priority strict
conda create --name gp_env python=3.7 geopandas --yes
. activate gp_env 

After the new env (gp_env) is created, you only need to type the following lines next time you need to activate gp_env.

bash
. activate gp_env
