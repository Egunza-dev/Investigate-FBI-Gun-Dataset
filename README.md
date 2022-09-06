# Project: Investigate a Dataset (FBI Gun Data)

## Introduction

> The data comes from the FBI's National Instant Criminal Background Check System. The NICS is used by ammunition merchants to determine whether a prospective buyer is eligible to buy firearms or explosives. Guns shops call into this system to ensure that each customer does not have a criminal record or isn't otherrwise ineligible to make a purchase. The data has been supplemented by state level data from census.gov.
>
> The NICS data is found in one sheet of an .xlsx file. It contains the number of firearm checks by month, state, and type.
>
> The U.S. census data is found in a .csv file. It contains several variables at the state level. Most variables just have one data point per state (2016), but a few have data for more than one year.


>#### Questions to Answer:
>1. Does Population estimates in States correlate with total gun registration and purchases?
>1. Is there relation between total gun registration and purchases and the percentage of various races in the given states?
>1. Which States had the highest growth in gun registration and purchases?
>1. What is the overall trend of gun purchases?

## Conclusions

> **Results**: The data suggests that
> 1. There exists correlation between gun totals and population estimates variables although this doesn't hold true in several states, a key outlier being the state of Kentucky with relatively low population estimates but with the highest gun totals.
> 1. There is no correlation between total gun registration and purchases and the percentage of various races in the given states.
> 1. The state of Kentucky has had the highest consistent gun purchases and registrations followed by the state of Carlifonia. The state of North Carolina experienced a momentary peak in march 2014 which overally was the highest but then plummated in the consequent periods.
> 1. The overall trend in gun purchases is an upward/increasing trend as indicated by higher highs and higher lows when the totals gun_data figures are plotted against month time data in a time plot.

> **Limitations**: 
> 1. The gun_data available had misssing data on various types of gun registrations and purchases.
> 1. The U.S. Census Data has most variables with just one data point per state for 2016, but only a few have data for more than one year.
