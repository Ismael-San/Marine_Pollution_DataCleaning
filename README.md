# Marine_Pollution_DataCleaning

Date
Region
Source
Ship Type
Area
Location
Pollutant
Estimated Litres

Colonnes toutes les mêmes sur tous les fichiers

Australia - Queensland
Marine Pollution 

2002-2020

Highlights evolution of marine pollution between 2002-2020



Check : 
- Missing Values
- Special characters
- Incorrect values
- Extreme values or outliers
- Duplicate records
- Incorrect data types

Add index (Event_ID) to differentiate each pollution event
Add a new 'Year' column. (current Dates column formats differ but we won't be using the exact dates in our analysis)

columnDate formats differ but exact dates won't be relevant for our analysis

Highlights marine pollution between 2002-2020 in Australia
By type of pollutants and starting from 2016, by quantities (will require computation and RegEx to normalize the data, to convert in a common measure unit)
By Region 
Displays evolution of marine pollution between 2002-2020

Pollutant :
- Determine the most recurring pollutant (needs to categorize whether they belong to Oil / Chemicals / Other)


Data : 

df_0216 : Ismael CSV (with encoding issues)
df_1617 : Jamyang CSV
df_1718 : Matthieu (XLSX)
df_1819 : Jamyang CSV
df_pol_1920 : Matthieu

Merge the data in a common df_pol

