# Exploring how a future, countywide property reassessment would impact Allegheny County's property owners
This repository includes code that cleans and analyzes property assessment and sales transaction data for real property in Allegheny County. This work supported an [article](https://www.publicsource.org/allegheny-county-reassessment-winners-losers/) published on October, 29, 2026, by the online, nonprofit newsroom Pittsburgh's Public Source. 

## Data
This analysis used property assessment records for all properties in Allegheny County and sales transactions that had taken place in the county through May 2026. The data was retrieved through a Right-to-Know request. 

## Pre-requisites
The reassessments-env folder includes all packages needed to complete this analysis.

## Methodology
1. Clean the assessment data.
2. Filter the dataset for taxable properties sold at an arm's length.
3. Filter the dataset further to include only municipalities that tallied 15 or more of these taxable, arm's-length transactions over the last two years.
4. Find the sales ratio for all properties. The sales ratio equals the total fair market value of a property divided by the property's most recent sales price. 
5. Find the median sales ratio for each municipality.
6. Find the coefficient of dispersion for each municipality. 

## Licensing
All code in this repository is available under the MIT License. The data file in the output/ directory is available under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. All files in the data/ directory are released into the public domain.

## Feedback / Questions?
Contact Mia Hollie at mia@publicsource.org.

