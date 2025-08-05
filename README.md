# HIV Infections in New York City

## Overview & Objective

This project aims to analyze the patterns and disparities of HIV infections in New York City, focusing on how race/ethnicity, age group, gender and neighborhood influence the rate of contamination. The primary goal is to identify which groups are most affected as they will serve as good indication of where public health interventions could have a huge impact.

## Data Summary

These data were reported to the NYC DOHMH by March 31, 2021

Both datasets include data on new diagnoses of HIV and AIDS in NYC for the calendar years 2016 through 2020. Reported cases and case rates (per 100,000 population) are stratified by United Hospital Fund (UHF) neighborhood, sex, and race/ethnicity.

Note:

- Cells marked "NA" cannot be calculated because of cell suppression or 0 denominator.

## Primary Files

This project is entirely created in Python environment using Jupyter Notebook. It contains three primary files:

1. Data_analysis: This file contains all the analysis: Data gathering, cleaning and enrichment are found here.
   Three final files are exported to .csv at the end of this exploration. First two: df_Age_cleaned.csv and df_Gender_cleaned.csv are cleaned datasets
   that were used later on in a SQLite joint to obtain the Age_Gender_joined.csv file. Kindly note that all three file were used for visualization.

2. Data_vizualization: This is a visual reflection of the exploration journey.
   The final charts tell multiple stories about HIV & AIDS infection in the city of New York across different spectrums.

3. Data_dictionary: This dictionary is drawn from both cleaned datasets: Age & Gender.

## Running the Program

Here is a step by step guide to follow in order to run the project files locally:

1. Go to Github and Fork the repository repo link
2. Create a local directory on your computer and open it with Gitbash. Type in code . to open VSCode
3. Once in VSCode, you can now clone the repository
4. Install a virtual environment. In Gitbash use the following command: python -m venv venv
5. Activate the virtual environment. Use Gitbash command: source .venv/scripts/activate
6. Install the requirements.txt file to install necessary packages by running pip install requirements.txt
7. Your notebook file Data_vizualization.ipynb should be ready to run

   Note: This requirements file was created in a Windows environment and uses Windows Python 3.13.2.
   It has not been tested on a different operating system such IOS or Linux.

## Data Sources

Data used came from NYC OpenData. Provided by the Department of Health and Mental Hygiene (DOHMH)

HIV/AIDS Diagnoses by Neighborhood, Sex, and Race/Ethnicity:
https://data.cityofnewyork.us/Health/HIV-AIDS-Diagnoses-by-Neighborhood-Sex-and-Race-Et/ykvb-493p/about_data

HIV/AIDS Diagnoses by Neighborhood, Age Group, and Race/Ethnicity:
https://data.cityofnewyork.us/Health/HIV-AIDS-Diagnoses-by-Neighborhood-Age-Group-and-R/dxnu-p2qd/about_data

## Features

1. Loading data: Read two CSV datasets using Pandas
2. Data Cleaning: Fixed names, remove special characters and standardized texts in different columns
3. SQLite: Loaded the data into SQLite database and created a JOIN between tables
4. Data Visualizations: Made four distinct visualizations
5. Functions: Created two functions - One used for data cleaning and the other for calculation
6. README: Current file

## Conclusion & Recommendations
