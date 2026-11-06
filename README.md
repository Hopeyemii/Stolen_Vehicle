# STOLEN VEHICLE ANALYSIS REPORT – NEW ZEALAND

## Project Overview
This analysis examines reported vehicle thefts across regions in New Zealand between 7 October 2021 to 6 April 2022. The objective is to understand the distribution of stolen vehicles, identify regional patterns, examine vehicle characteristics, and highlight areas that may require further investigation.
The analysis combines three datasets: stolen vehicle records, regional population information, and vehicle make details.

## Tools and Technologies
1.	Python language
2.	Jupyter Notebook – analysis environment
3.	Pandas – data cleaning, transformation, and analysis
4.	Matplotlib and Seaborn – data visualization

## Data Cleaning and Preparation
The data cleaning and preparation process involved:
1.	Examining dataset structures, column types and missing values.
2.	Checking duplicate records and duplicate vehicle IDs.
3.	Converting the date_stolen column into a datetime format.
4.	Extracting year, month, month name, day and day of the week.
5.	Removing commas from population values and converting the population column to numeric.
6.	Combining the three datasets using their respective location and make identifiers.
7.	Validating the merges to confirm that all 4,553 vehicle records matched a location record.
8.	Replacing missing categorical values with Unknown, while retaining missing numerical values rather than assigning unsupported values.

## Key Performance Indicator(KPI)
Total Population: 5,123,200

Total Vehicle theft:	4,553

## Key Findings 
### Regional Distribution:
Auckland recorded the highest number of stolen vehicles, with (1,638) cases, followed by Canterbury (660) and Bay of Plenty (446). Southland recorded the lowest number among the regions with reported thefts, at (26).
However, when theft counts were considered relative to population, Gisborne recorded the highest rate, at approximately 338 stolen vehicles per 100,000 residents. This shows that the region with the highest number of thefts is not necessarily the region with the highest population-adjusted rate.
### Monthly Theft Trend:
Reported thefts increased across the observed period, reaching their highest monthly total in March 2022, with 1,053 cases. February recorded 763 cases, while January recorded 740.
April recorded 329 cases, but the dataset only covers the first six days of that month. Therefore, its total should not be compared directly with complete months.
### Vehicle Make and Type:
Toyota was the most frequently recorded vehicle make, with 716 records. Trailer appeared as the second-highest entry in the make-name field, with 543 records.
By vehicle type, Stationwagons recorded the highest number of thefts (945), followed by Saloons (851) and Hatchbacks (644). This identifies the vehicle types that appeared most frequently in the dataset.
### Vehicle Model Year and Colour:
Vehicles from model years 2005 and 2006 recorded the highest theft counts, with 347 and 333 cases respectively.
Silver was the most frequently recorded vehicle colour, with (1,272) cases, followed by White (934) and Black (589).
### Make Classification:
The majority of records were classified as Standard (4,348), while (190) were classified as Luxury. Fifteen records had an Unknown classification.

## Recommendations
1.	Prioritise regional monitoring using both total theft counts and population-adjusted rates.
2.	Investigate the factors contributing to the high reported theft rate in Gisborne.
3.	Monitor monthly theft patterns to identify changes and support timely decision-making.
4.	Improve data collection and classification to reduce unmatched records and ambiguous categories.

## Data Limitations
1.	April contains only six days of records, making its monthly total incomplete.
2.	Three regions had no theft records in the dataset. This does not confirm that no thefts occurred in those regions.
3.	Fifteen vehicle records did not match the make-details dataset.



