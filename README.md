# Generic Real Estate Consulting Project
## Group 20:
* Rei Hsuan Cheng
* Keith Howen
* Benjamin Lo
* Kalyana Sreeram
* Andreas Battistini

## Project Aim:
* The aim of this project is to reveal the underlying relationship between rental price and various factors such as income, population, unemployment and distance to facilities. In tandem with preliminary analysis, several machine learning models were also trained to explain the most critical internal and external features for the prediction of future rental prices for the next **5 years** (2022 - 2027). In addition, suburbs were scored based on elements of liveability in order to pinpoint the most liveable and affordable locations for renters.

Broadly, We intend to answer three questions:

1. What are the most important internal and external features in predicting rental prices?
2. What are the top 10 suburbs with the highest predicted growth rate until 2027 ?
3. What are the most liveable and affordable suburbs in Victoria ?

## Repository Instruction:
* Ensure all raw data are present in folder
* Ensure that all code dependencies are fulfilled as per ```requirements.txt```
* Run each notebook **in consecutive numerical order**. E.g. 1.0 -> 1.1 -> 1.2...
* Summary notebook is the last item in the ```main``` branch, called ```summary_notebook```
  * Please ensure every notebook in the ```notebooks``` directory are ran prior to the ```summary_notebook```. This ensures that graphs used in the summary show up correctly
  
### Notebooks Summary - Workflow and Pipeline:

* 1.0_Primary_Rental_Scrape - Scrape multiple rental properties in Victoria 
* 1.1_Primary_Cleaning_Parse_Rental - Cleaning and transforming scraped data using various pandas and regex tools 
* 1.2_Primary_Suburb_Room_Extraction - Feature Engineering using regex tools to extract features from scraped rental properties 
* 1.3_Primary_Dataset_API_Proximity_Calculations - Caluclating proximity to CBD, schools, hospitals and train stations for the scraped properties  
* 1.4_Primary_Outlier_Removal - Detecting and removing outlier properites 
* 1.5_Preprocessing_Income_Population - Preprocessing external income and population datasets 
* 1.6_Preprocessing_School - Preprocessing external school dataset 
* 1.7_Preprocessing_Unemployement - Preprocessing external unemployement dataset 
* 2.0_Preliminary_Analysis_Primary - Explaratory data analysis on scraped rental properties 
* 2.1_Preliminary_Analysis_Historical_Rent - Explaratory data analysis on external historical rental data 
* 2.2_Preliminary_Analysis_Unemployment_And_Historical_Rental - Time series explaratory data analysis on how unemployement affects rental prices 
* 2.3_Preliminary_Analysis_Population_School - Explaratory data analysis on how population and access to education affect rental prices 
* 2.4_Preliminary_Analysis_Income - Explaratory data analysis on how residents income affect rental prices 
* 2.5_Preliminary_Analysis_Population_Immigration - Explaratory data analysis on how immigration patterns affect rental prices 
* 2.6_Geospatial_For_Scraped_Rental - Geospatial analysis for both internal and external attributes affecting rental prices 

## Project Aim:
* The aim of this project is to reveal the underlying relationship between rental price and various factors such as income, population, unemployment and distance to facilities. In tandem with preliminary analysis, several machine learning models were also trained to explain the most critical internal and external features for the prediction of future rental prices for the next **5 years** (2022 - 2027). In addition, suburbs were scored based on elements of liveability in order to pinpoint the most liveable and affordable locations for renters.
