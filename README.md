# Oxford_LTLA_COVID19

In England and the United Kingdom, reporting of COVID-19 cases, deaths, and estimated recoveries is centralized by Public Health England. The data is available at [coronavirus.data.gov.uk](coronavirus.data.gov.uk). The website does not contain historical data for locations lower than the national level. This project is built on manual tracking of case data for the Oxford Lower Tier Legal Authority and visualization using R Markdown and LaTeX.

This repository will serve to report and visualize the growth of COVID-19 cases in the lower tier authority of Oxford ([See map for boundaries](https://www.oxford.gov.uk/downloads/file/1097/oxford_city_council_boundary_map)).

**Products**
* OxfordCases.csv - csv file containing the reported daily cumulative cases for the Oxford LTA. Column 1 is date, Column 2 is total cases, Column 3 is deaths. Each row represents a single date.
* OxfordCases.pdf - visualization of the data, built using R Markdown and the ggplot2 package.

**Data notes**  
Case totals are missing for the following dates. In these instances, the case number from the previous day was carried forward. The seven day rolling average will smooth these jumps.
* July 31, August 7, August 8, August 9, August 12, August 14, August 15, August 20, September 19
Deaths only began to be tracked October 5.
