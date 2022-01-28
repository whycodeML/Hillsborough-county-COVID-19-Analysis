# Hillsborough-county-COVID-19-Analysis
Using the John Hopkins Covid19 dataset (https://github.com/CSSEGISandData/COVID-19get) data for the last 30 days for Hillsborough County programmatically and save it as a dataset.

Data in this task is pulled from the mentioned location which has .csv file for everyday for all the countries including United States. 
For US data also had information on county and we want information on Hillsborough. 
Further, next step here was to pull data only for Hillsborough so that we don’t end up pulling data unnecessarily for other Countries. 
This is handled in python while reading .csv file and filtering data for Hillsborough only. 
Since the requirement wants us to have data for the last 30 days, I have created file keys which could be mapped 
directly with the available files name to pull filtered data, this will save space and execution time. 
After reading data file is written in excel with an additional column of FileDate which will help us to know the source of data for each row. 
PS: After downloading the data I found that during the last 30 days a lot of data is missing for Active Cases and No data present for recovered.

Tableau Visualization: https://public.tableau.com/app/profile/rishabh.srivastava8504/viz/HillsboroughCovidCases/Dashboard1
