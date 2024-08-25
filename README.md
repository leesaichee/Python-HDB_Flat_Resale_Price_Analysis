# Python-HDB_Flat_Resale_Price_Analysis
As part of the Career Foundry Data Analytics Program, this [project](01%20Project%20Management/A6_Data_Project_Brief.pdf) is aimed to build an interactive dashboard that will visually showcase well-curated results of an advanced exploratory analysis conducted in Python. 

![HDB flats image](https://www.patkoproperty.com/content/images/size/w1140/2022/09/The-Checks-Before-Buying-a-Old-Flat.webp)

## Background
An HDB flat is a public housing unit in Singapore developed and managed by the Housing and Development Board (HDB), offering affordable homeownership to Singaporean citizens. Compared to Build-To-Order (BTO) flats, resale flats offer immediate availability, a variety of locations with established amenities, and greater flexibility in terms of unit type. However, a significant challenge is the rising prices in the resale market, which can be considerably higher than new BTO flats and may limit affordability for some buyers. 

## Objective
To study the factors that could affect the resale price of the HDB flats based on the data available. 

## Business Questions
1) Which factors below would affect the resale price of the resale flats?
   - floor area (sqm), remaining lease, distance to nearest train station, storey range midpoint
2) For the categorical variables below, which categories have higher resale price?
   - flat type, flat model, interchange flag (whether if the nearest train station is an interchange)
3) How does the resale price differ geographically?
   - town, region
4) How does the resale price change over time? 

## Data Source: 
1) **HDB resale flat prices**: accessed on 28 January 2024 from [Data.gov.sg](https://data.gov.sg/collections/189/view) which is made available under the terms of the Singapore Open Data Licence [version 1.0](https://data.gov.sg/open-data-licence).
2) **List of train stations with opening and closure dates**: retrieved from Wikipedia - [MRT](https://en.wikipedia.org/wiki/List_of_Singapore_MRT_stations), [LRT](https://en.wikipedia.org/wiki/List_of_Singapore_LRT_stations)
3) **2019-based consumer price index (CPI)**: retrieved from [SingStat Table Builder](https://tablebuilder.singstat.gov.sg/table/TS/M212881)
4) **Master Plan 2019 Region Boundary (No Sea)**: accessed on 25 March 2024 from [Data.gov.sg](https://data.gov.sg/collections/1717/view) which is made available under the terms of the Singapore Open Data Licence [version 1.0](https://data.gov.sg/open-data-licence).
5) **Master Plan 2019 Planning Area Boundary (No Sea)**: accessed on 25 March 2024 from [Data.gov.sg](https://data.gov.sg/collections/2104/view) which is made available under the terms of the Singapore Open Data Licence [version 1.0](https://data.gov.sg/open-data-licence).

## Tools
- Python (Pandas, Numpy, Asynchronous I/O, AIOHTTP, GeoPandas, Matplotlib, Seaborn, Folium, Scikit-learn: linear regression and k-means clustering, Statsmodels: time series analysis and forecasting)
- Jupyter Notebook
- Excel
- Tabeau Public

## Project Folders Arrangement
1) [Project Management](01%20Project%20Management)
   - Contains the Project Brief. 
2) Data
   - Contains two subfolders: “Original Data”, for storing the raw data sets, and “Prepared Data”, for storing any manipulated data sets. 
   - NOTE: The Data folder is not uploaded here due to its large size. 
3) [Sripts](03%20Scripts)
   - Contains all the Python scripts involved for the entire analysis process. 
4) [Analysis](04%20Analysis)
   - Contains all the results and visualizations produced throughout the analysis. 
5) [Sent to client](05%20Sent%20to%20Client)
   - Contains the final deliverables. 

## Final Deliverables
1) [Tableau storyboard](https://public.tableau.com/views/HDBFlatResalePriceAnalysis/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
   - NOTE: The storyboard contains only those relevant to the final results. Detailed steps can refer to the Python scripts. 
2) [Excel report](05%20Sent%20to%20Client/Final%20Report.xlsx)
