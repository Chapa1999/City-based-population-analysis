# City-based-population-analysis
----------------------------------------------------------------------------------------------------------------------------------------
## INTRODUCTION

•The Census of India conducted every 10 year's.
•First census Started in 1871. The word 'Census' came in the Latin word 'Censere' and the 'Censere' meaning to assess. Or other word Census meaning 'an official count or survey, especially of a population'. 
•Census is nothing but a process of collecting, analyzing, evaluating, publishing and discripting statistical data regarding the population.

### This repository consists of the following:
1. README.txt (this file)
2. Dataset : "Census.csv"
3. Notebook downloaded as an ipynb file
4. "Web-scraping_Using_2011_Census_of_India" consists of scraping websites and creating dataframes.
5. "Data_Analysis_Using_2011_Census_of_India" consists of analyzed data.

# Step 1 : IMPORTING LIBRARIES:
We are import many libraries as per our needed:-
1. import pandas as pd                 # used for data analysis.
2. import numpy as np                  # used to perform mathematical operations on arrays.
3. import re                           # to check if a string contains the specified search pattern.
4. import requests                     # allow you to send HTTP/1.1 requests using Python.
5. from bs4 import BeautifulSoup       # web scraping purposes to pull the data out of HTML and XML files.
6. import matplotlib.pyplot as plt     # used to data visualization.
7. import seaborn as sns               # making statistical graphics in Python.
8. from tabulate import tabulate       # used to print tabular data in nicely formatted tables.

# Step 2: Clear the data
### 1.We make a lot of things clear in web scraping: -
1. Remove ',','' etc.
2. Change the data type as per our requirement.
### 2. In data analysis we are only removing the "Nameless: 0" column.

# Step 4 : SUMMARIZING THE DATASET
1. Dimensions of the dataset
2. Peek at the data
3. Statistical Summary
4. Class Distribution
5. Information about data
6. Length of the data

### Let's following questions:-
1. Total number of cites as per state?
2. Population wise highest rank city in India.
4. population wise least city in India.
5. Check highest LITERACY city in India.
6. Check lowest LITERACY city in India.
7. Etc.
►"*All the question of the answer are showing using ghraph and table format in "Data_Analysis_Using_2011_Census_of_India"*"

# Conclusion
•We are using Census 2011 of India for our dataset.
•Analyzing our data, we can see that Uttar Pradesh has the highest number of cities and there are 64 cities in Uttar Pradesh.
•The highest city in India by population is Mumbai (Maharashtra) and population is 12442373. 
•The lowest city in India by population is Kupurthala (Panjab) and population is 98916. 
•The highest city in India by litaracy is Aizawl (Mizoram) and percentage is 98.36%. 
•The lowest city in India by litaracy is Sambhal (Uttar Pradesh) and percentage is 48.98%. And we see that the total population of Hyderabad is 6731790 and the literacy percentage is 83.26% and 
•Hyderabad is the 4th most populous city in India according to our data.

----------------------------------------------------------------------------------------------------------------------------------------
 #                                                                *Thank You*
