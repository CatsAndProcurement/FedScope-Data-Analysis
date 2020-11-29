# FedScope-Data-Analysis

Python script that analyzes U.S. government agency data on contracting employees (occupational code 1102)

Created on Mon Nov 23 18:28:00 2020

@author: CatsAndProcurement

The purpose of this Python script is to demonstrate one way of analyzing U.S. federal government employee data from the Office of Personnel Management (OPM). OPM's FedScope dataset contains individual, anonymized information on most civilian employees. Exceptions include many employees working in national security-related positions and a few other categories; see the following link for agency coverage:
https://www.fedscope.opm.gov/datadefn/aehri_sdm.asp#cpdf3

FedScope raw data is is made available quarterly in a large (~150MB) TXT file compressed in a ZIP file, published via the following web page:
https://www.opm.gov/data/index.aspx

This script uses Pandas (a Python math module) to analyze FedScope data on contracting employees (occupational code 1102). The script assumes that you have already downloaded the relevant data (see link above) and unzipped it to the same directory as the script.
