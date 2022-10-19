# FBI-Gun-Data-Analysis
The [FBI Gun Data](https://www.google.com/url?q=https%3A%2F%2Fd17h27t6h515a5.cloudfront.net%2Ftopher%2F2017%2FNovember%2F5a0a5623_ncis-and-census-data%2Fncis-and-census-data.zip&sa=D&source=docs) used in this project comes from the FBI's National Instant Criminal Background Check Sysytem. This dataset has been supplemented with state level data from [census.gov](https://www.census.gov/). 
This Dataset includes two (2) sets of data : **NICS** data and the **U.S. census data**.
 
The National Instant Criminal Background Check System (NCIS) data stored in an .xlsx file is used to determine whether a prospective buyer is eligible to buy firearms or explosives. Before ringing up the sale, cashiers call in a check to the FBI or to other designated agencies to ensure that each customer does not have a criminal record or isn’t otherwise ineligible to make a purchase. More than 100 million such checks have been made in the last decade, leading to more than 700,000 denials.

Each column represent a type of transaction submitted to the NCIS. In addition each type of transaction is broken down by the type of firearm -- handgun, long gun and others.
These set of transactions are used to **estimate sales** accross states:
- Handgun : any firearm having short stock and designed to be held fired by use of a single hand.
- Long gun : a weapon designed to be fired from the shoulder.
- Other : refers to frames, receivers and other firearms neither handgun nor longun(rifles or short gun).

Other sets of transaction are majorly just **background checks** initiated by an officially-licensed Federal Firearms Licensee (FFL) or ciminal justice law enforcement agency. They include:

- multiple : background check for more than one fire arm.
- admin : administrative checks that are for other uses of NCIS.
- other background checks include pre-pawned, redemption, rentals, returned, private sale, return to seller-private sale.



The [U.S census data](https://www.census.gov/) found in a .csv file contains several variables at the state level. Most variables just have one data point per state (2016), but a few have data for more than one year.

## Research Questions

The following questions arrive from the FBI Gun Data

1. What is the overall trend of gun purhases?
2. Which states have had the highest growth in gun registrations?
3. What observation can be made from the overall yealry background check?
4. What observation is seen between background check and gun purchase in each state?
