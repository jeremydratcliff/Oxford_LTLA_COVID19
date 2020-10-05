# Oxford_LTA_COVID19

In England and the United Kingdom, reporting of COVID-19 cases, deaths, and estimated recoveries is centralized by Public Health England. The data is available at [coronavirus.data.gov.uk](coronavirus.data.gov.uk). The website does not contain historical data for locations lower than the national level. This project is built on manual tracking of case data for the Oxford Lower Tier Legal Authority and generation of a visualization using R Markdown.

This repository will serve to report and visualize the growth of COVID-19 cases in the lower tier authority of Oxford ([See map for boundaries](https://www.oxford.gov.uk/downloads/file/1097/oxford_city_council_boundary_map)).

**Products**
* OxfordCases.csv - csv file containing the reported daily cumulative cases for the Oxford LTA. Column 1 is the date, Column 2 is total cases. Each row represents a single date.
* OxfordCases.pdf - visualization of the data, built using R Markdown and the ggplot2 package.
