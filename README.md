Energy Project Summary

Data Collection and Filtering

Primary source of information was open source data on energy collected by Our World in Data.  I created a column in the owid-energy-data csv to distinguish continents from countries. Importing the owid as a csv. Then taking out all values which represent groups of countries (ex: ASEAN) which have a majority of null values and not much use for this project.
Separate CSV data pulled to obtain flag images from user Zhongtron from Kaggle.com and was imported into Power BI as the second table. Both tables were joined together through the internationally recognized country codes which appear as “iso_code” in the owid-energy-data table and “Alpha-3 code” in the flags_iso table.
Changing the data type in Power Query of the column “renewables_cons_change_pct”, “renewables_energy_per_capita” and “renewables_consumption” to from text to decimal number.
Measure created to aggregate the sums of chosen renewable energy types covered in tabs “Solar” and “Wind” to summarize in the “Homepage” tab.

Visuals

The data has information from 2022 for a minority of countries, so the most recent year of full data, 2021, was chosen to show most current trends across all tabs.
