# Financial Inclusion Survey Analysis

## Background:
the world is facing unequality in the availability of the banking services in many regions and countries, this is because of many reasons, mainly poverty, untrust, safety, ...etc.

here i made an analysis on a dataset to investigate the financial inclusion abroad.

## Data Preparation:
first, the data was obtained from https://hub.festman.io/ which is an excel sheet.

then i started to prepare the data for the analysis process by cleaning it and calculating some new columns, in this process i used some important excel functions, like 
VLOOKUP,COUNTIF, SUBSTITUTE, TEXTJOIN, ... 

the cleaning process transformed the sheet to be a table with the needed columns and values for the analysis process, where it had columns about (countries, regions, gender, age, education level, income class) and other columns for the ownership of bank accounts and reasons for not owning them.

![financial inclusion survey - excel](https://user-images.githubusercontent.com/79236835/161986419-cfc61d3a-0f68-41df-a7b1-d145c186518e.png)

## Data Processing:
for processing, i uploaded the data on power BI, where i used power query to make some transformations to the table to be ready to use in making the dashboard, then i used DAX to make new measures that would calculate some important things to show in the results obtained, like the "average percentage of bank account owners" in each country, "average mobile owners", "percentage of credit & debit card owners", "percentage of people who saved or borrowed money in 12 months", "percentage of people who pay online", ....

some of used DAX functions are:
- CALCULATE ()
- COUNTROWS ()
- AVERAGE ()

also i made some measures from using the columns only, like the percentage measures: and other measures were applied on a whole column, like the counting of the number of reasons of not to have bank account for each country.

here is the dashboard after i have finished it:

![financial inclusion survey - page 1](https://user-images.githubusercontent.com/79236835/161991728-d9fbcee2-afb9-4c94-89a0-683f0005e100.png)

![financial inclusion survey - page 2](https://user-images.githubusercontent.com/79236835/161991963-1f8aae35-18cf-40ba-b143-f6c3471b382a.png)

![financial inclusion survey - page 3](https://user-images.githubusercontent.com/79236835/161993158-2b494512-b057-4bab-bf10-aa2b39b85c89.png)


## the main insights obtained from the analysis are:
- 63% of the persons have bank accounts, the percentage increases in the high income countries to 95% and decreases to 45% in the low income ones "mostly Latin American, sub-Saharan, and south Asian countries"
- most bank account owners are between 15 and 40 years
- most of them are in the workforce and completed their secondary education (most of the Asian countries owners actually completed their primary study)
- bank account female owners percentage decrease in MENA countries
- the main reasons for not having a bank account is "lack of money" and "lacking documentation papers" and also banking services are far in the low income countries
-71% have debit cards, but the percentage decreases in sub-Saharan Africa, south Asia and MENA region to nearly 30%
- 82% are mobile owners, most of the owners have completed their tertiary education, and most of them are between 15 and 50 years
- surprisingly, sub-Saharan Africans have the highest "mobile money account" percentage, especially countries on the east African coast (Kenya, Uganda, Rwanda, … etc.)
- in sub-Saharan Africa region, the percentage of mobile owners can vary from 90% in east African countries to 30% in a country like south Sudan.


https://user-images.githubusercontent.com/79236835/161996103-a28b15c5-a51a-48ca-b61b-f7a64981c5fa.mp4


# in conclusion, we can say that some parts in the world need to be more covered with the banking services, and also we can say sub-Saharan Africa can be an excellent new market for the banking sector globally to expand in.

And finally, the excel sheet used and the power BI file can be found here: https://drive.google.com/drive/folders/1dlzqy0U1AlZ4nnqHR3F56upsvpMgcu7Y?usp=sharing
