# PHMSA_Sraper
Pulls a specific utilities data from CSV yearly CSV file downloads. 

Dowanload the ZIP files here: https://www.phmsa.dot.gov/data-and-statistics/pipeline/gas-distribution-gas-gathering-gas-transmission-hazardous-liquids

Unzip, can read through for full company names. 

Will save a new file for all years of data for the specefied company.


SIMILARITY RANKER

The user inputs a csv file with data of two companies information. For this example, it uses the aformentioned PHMSA data for year 2020. 

Then, the user can name a company, and the code will return the comapny with the most similar information. There is also a version that does the same, 
but only considers metrics in which the target company recordsa a value other then 0. 
