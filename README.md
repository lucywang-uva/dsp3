# Housing Prices Forecast Analysis

## SRC

### Installing/Building Code
All source code exists in the SRC directory. Install all dependencies required by each file that are specified by the imports.
To run the files in this directory, developers used Jupiter Notebook.

### Code Usage
Users can use, copy, modify, merge, publish, distribute, and sublicense this software, granted that the original MIT License is included in new software.

## DATA

### Data Dictionary 
- Year  
- Quarter 
- Not Seasonally-Adjusted Purchase-Only Index
- Seasonally-Adjusted Purchase-Only Index
- Not Seasonally-Adjusted Purchase-Only Index % Change Over Previous Quarter
- Seasonally-Adjusted Purchase-Only Index % Change Over Previous Quarter
- Not Seasonally-Adjusted Purchase-Only Index % Change Over Previous 4 Quarters
- Seasonally-Adjusted Purchase-Only Index % Change Over Previous 4 Quarters

Link to data: https://www.fhfa.gov/DataTools/Downloads/Pages/House-Price-Index-Datasets.aspx?fbclid=IwAR1GrWS0sQwNIcVooRnQf6PqKBHW4HAzX7YXblIP2oEwoVHONfK-QgyGiZk

(Used "U.S. Summary" .xls file under "Quarterly Data") 

### Revelant Notes
- Obtained from the Federal Housing Finance Agency
- The data set regards quarterly data regarding House Price Index (HPI) values in the US from 1991 to 2022. 
- Includes 128 rows, with every four rows representing a year from 1991 to 2022. For each year, the data is split into four quarters from one to four.


## FIGURES
Graph | Summary
------------- | -------------
![alt text](https://github.com/lucywang-uva/dsp3/blob/main/FIGURES/not_seasonally_adjusted_HPI.png?raw=true) | There is a steep dip in HPI at the end of 2007 and the beginning of 2008, as explained by the 2008 financial and housing crisis. Prices began to increase again around 2012, with a steeper slope at the beginning of the COVID pandemic as people were under lockdown and there was a higher demand for housing. This steep slope only began to flatten in the second quarter of 2022.
![alt text](https://github.com/lucywang-uva/dsp3/blob/main/FIGURES/seasonally_adjusted_HPI.png?raw=true) | The seasonally-adjusted HPI trends over time follow the same general pattern as the not seasonally-adjusted trend, with the seasonally adjusted graph being slightly smoother most likely due to micro-corrections after considering market fluctuations based on seasonality. 
![alt text](https://github.com/lucywang-uva/dsp3/blob/main/FIGURES/not_seasonal_analysis.png?raw=true) | The seasonally-adjusted HPI trends over time follow the same general pattern as the not seasonally-adjusted trend, with the seasonally adjusted graph being slightly smoother most likely due to micro-corrections after considering market fluctuations based on seasonality. 
![alt text](https://github.com/lucywang-uva/dsp3/blob/main/FIGURES/seasonal_analysis.png?raw=true) | The seasonally-adjusted HPI trends over time follow the same general pattern as the not seasonally-adjusted trend, with the seasonally adjusted graph being slightly smoother most likely due to micro-corrections after considering market fluctuations based on seasonality. 






## REFERENCES
[1]   Bernstein, J., Tedeschi, E., & Robinson, S. (2021, November 30). Housing prices and inflation. The White House. Retrieved April 6, 2023, from                                                                       https://www.whitehouse.gov/cea/written-materials/2021/09/09/housing-prices-and-inflation/ 

[2]   Santarelli, M. (2023, March 30). Housing market predictions 2023: Will home		prices drop in 2023? Norada Real Estate Investments. Retrieved April 6, 2023, from https://www.noradarealestate.com/blog/housing-prices/ 

[3]   Pierre, S. (2022, October 13). A guide to time series forecasting in Python. Built		In. Retrieved April 10, 2023, from									https://builtin.com/data-science/time-series-forecasting-python 

[4]   House Price Index Datasets. House Price Index Datasets | Federal Housing Finance Agency. (n.d.). Retrieved April 10, 2023, from						https://www.fhfa.gov/DataTools/Downloads/Pages/House-Price-Index-Datasets.aspx?fbclid=IwAR1GrWS0sQwNIcVooRnQf6PqKBHW4HAzX7YXblIP2oEwoVHONfK-QgyGiZk 

[5]   Liberto, D. (2023, March 28). Understanding the House price index (HPI) and		how it is used. Investopedia. Retrieved April 10, 2023, from https://www.investopedia.com/terms/h/house-price-index-hpi.asp 

