## Analysis of Dublin House Prices Based on Crime Rates Social Housing Construction and School Distribution

The datasets used in this project are housing cost, crime dataset, social house construction and schools in Dublin. Below are the links of the data

Yihui Zhang
•	JSON file: Dublin residential property price dataset
https://data.smartdublin.ie/dataset/dublin-residential-property-price-register/resource/2d81e403-5cb7-4b1c-b296-2b21b95df5c8
•	Geojson file: Garda boundary dataset: 
https://www.geohive.ie/datasets/6d178d2c9bb3453590506690a7f319ee_0/about

Samrudhi Hawalli Ramachadra
•	JSON file: Social housing construction
 https://data.gov.ie/dataset/social-housing-construction-status-report-q3-2020
•	CSV file: school of distribution 
https://data.gov.ie/dataset/schools-in-dublin-region
•	Geojson file: Garda boundary dataset: 
https://www.geohive.ie/datasets/6d178d2c9bb3453590506690a7f319ee_0/about

Daphne Shekinah T 
•	CSV file: crime dataset: 
https://data.cso.ie/table/CJQ06


The CSV files are stored in postgres server and JSON files are loaded into mongodb cluster. Python is used for preprocessing and data cleaning. The cleaned data is stored back into the postgres server.

The resultant data is used for visualization using matplotlib and seaborn python libraries.
