# Global-Covid-19-Cases Report (2020 - 2022)

## Introduction

Coronavirus disease 2019 (COVID - 19) is a contagious disease caused by a virus, the severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2). The first known cases was identified in Wuhan, China, in Decenber 2019. The disesase quickly spread worldwide, resulting in the COVID-19 pandemic. The symptoms are variable but often include fever, cough, headache, fatigue, breathing difficulties , loss of smell and loss of taste.

# Data Source

The data sets for this analysis was extracted from a github repository (CSSEGISandData/COVID-19) and was analysed using Microsoft Excel tool. 

# File naming convention

Date: MM-DD-YYY.csv in UTC
Province_State: Province, State or dependency name
Country_Region: country, region or soverignty name
Lat and Long: keys that shows the location of country or region on the map
Confirmed: Counts include confirmed and probable (where reported)
Deaths: Count include deaths where reported
Recovered: counts include recovered patients

# Data Transformation

I connected to an already opened github repository from the "get data from web" on the Data ribbon of Microsoft Excel. Thereafter, i a copied URL from the github repository was pasted into the space provided for the URL after which the dataset was imported into the power query of microsoft excel for cleaning. Some transformation process carried out include: making first row as header, unpivoting some columns that were not aligned for appriopriate analysis, changing of data types, transforming a data column to get the years, the months and days into a respective columns for better visualization. Data was loaded into excel workbook after cleaning and was made ready to be visualised.  

# Data Visualisation

1. As at 13th July, 2022, the confirmed and deaths figure recorded was 164b and 2.8b cases respectively.
2. Death rate (death cases divided by confirmed cases expressed in percentage) was 1.70%
3. United States of America recorded the highest prevalence cases of 30b cases while North Korea have the least prevalent occurence of 59 cases
4. Year 2022 has the highest cummulative covid_19 prevalence since the year 2020 the pandemic started 
5. The month of June recorded the highest cumulative covid-19 prevalence in the years under reviewed.
