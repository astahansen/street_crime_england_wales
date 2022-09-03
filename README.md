# Street crime in England and Wales

### Data
Every Police force in the UK record the reported crimes. General information on street crime for the past 3 years is publicly available from the [police](https://data.police.uk/data/), where it can be downloaded split into files for each constabulary by month.
An already merged version of this data covering October 2018 till September 2021 was compiled by Chris and made available on [Kaggle](https://www.kaggle.com/datasets/tantable/all-uk-police-street-crime102018-to-092021?resource=download&select=UK_Police_Street_Crime_2018-10-01_to_2021_09_31.csv) also including data on Police officer staffing levels from 2021, which was appended with officer numbers from previous years, accessed [here](https://www.gov.uk/government/collections/police-workforce-england-and-wales) to match the crime data timeline.

### Objective
Given that this data covers the pandemic years and the three lockdowns in England and Wales in 2020 and 2021 this analysis will look at changes in reported crimes during these periods to determine if they had a significant impact and if so how this manifested. It will further explore which variable from the available data could best be used to determine crime levels in an area.

### Results
Population size can be used as a proxy for absolute crime levels, due to the high correlation of these two variables. However, when looking at relative crime numbers this no longer applies. Cleveland for example has a low population level but the highest rate of crime reported per 1000 residents in the country, compared to London with nearly 9m residents shows a comparatively lower level of relative crime.

Crime levels were impacted during the nation-wide lockdowns in England and Wales, however, not to the degree one might expect. Although nearly all types of crime saw a significant drop in April 2020 anti-social behaviour soared, due to lockdown restrictions being breached during that time, mostly exceeding the drop in all other crime types combined. This meant that in most areas there was an increase in absolute crimes recorded for this period.
The short lockdown in Novemeber 2020 did not seem to have an effect on crime rates, but for the other tow lockdowns lasting more than three months there is a clear upward trend towrads the end of the period.

The storyboard for this analysis, limited to England, can be found on [Tableau](https://public.tableau.com/app/profile/asta.hansen/viz/StreetCrimeEngland/Story1).
