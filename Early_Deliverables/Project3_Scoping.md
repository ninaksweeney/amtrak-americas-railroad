## Problem Statement
Amtrak needs a strategy to improve its historically low ridership and revenue, which have been made worse by the onset of COVID-19.


## Nontechnical Scoping

Opportunity :  
   
Amtrak is a low-carbon alternative to air travel, which may appeal to younger audiences - a key demographic that Amtrak is trying to target.   

Impacted Parties :   
* Amtrak marketing team 
* Amtrak staff on chosen routes 
* Politicians writing policy related to Amtrak
* Amtrak finance team, Station staff and surrounding tourism-related business
* Airline staff in affected areas  

Main Constraints :   
* Amtrak is currently sustained with subsidies, so marketing budget must not exceed its annual allowance
* Amtrak staff will need to adjust to changes in ridership, so advertising should ramp up slowly

Other Considerations :  
  
Amtrak faces a number of major obstacles at the moment. This project addresses a combination of ridership & revenue, but not challenges like crumbling infrastructure, COVID-19 dangers, or Congressional hurdles. All of those other challenges will affect our solution in known & unknown ways. 

## Technical Scoping

Potential Solution Paths :  
* EDA to drill down to (assumed) potential target audience
* Prediction model to identify who is most likely to replace other forms of travel with rail (collect data on this at the ticket purchase time)
* Model which routes, days, times, etc. produce the highest ROI for Amtrak 
* Model which routes, days, times, etc. are the best environmental options compared to airlines

Data Sources :  
* [Air travel data, last three years](https://www.transtats.bts.gov/DL_SelectFields.asp?gnoyr_VQ=FHK&QO_fu146_anzr=b4vtv0%20n0q%20Qr56v0n6v10%20f748rB)
* [US Climate Opinion Survey Data](https://climatecommunication.yale.edu/visualizations-data/ycom-us/ )
* [Census data on age](https://data.census.gov/cedsci/table?q=United%20States&t=Age%20and%20Sex&g=0100000US%243100000&tid=ACSST1Y2019.S0101&hidePreview=true)
* [University information nationally](https://educationdata.urban.org/data-explorer/colleges/)
* [University Geography data](https://nces.ed.gov/programs/edge/Geographic/SchoolLocations#)
* [Amtrak Route data](https://data-usdot.opendata.arcgis.com/datasets/amtrak-routes/explore?location=33.813562%2C-96.584950%2C4.00&showTable=true)
* Needed from amtrak : Data on new ticket purchasers - demographics, geography, and other potentially predictive factors
* Other data, such as route durations and prices, can be manually collected from the website

## Impact Hypothesis  
  
Climate-focused advertising targeted at young people who travel often will increase ridership and revenue for Amtrak. 

Assumptions:  
* Popular air travel routes are an opportunity to gain ridership - people are willing to switch over
* A focus on climate change in Amtrak's messaging will resonate with some Americans
* Young people are more likely to connect to climate-focused messaging
* Individuals with more concern about climate change are more willing to **act** on those concerns by changing travel habits

## Current State
  
Defining Success :  
Increase ridership of 18-35 age bracket by 5% on chosen routes.   

Status Quo :   
* Recovering from COVID losses
* Hoping to target young people
* Not heavily advertising sustainable aspects of Amtrak  
  
Unknowns :  
* Why do people choose air? For time? Comfort? Cost? Habit?
* What messaging will resonate best on this topic?
* Which aspects of rail travel make it difficult for people to switch?

## Future State

Action :  
Marketing will target advertising at the chosen locations, with a new focus on environmental sustainability and making responsible choices for climate. 

Technical Process : 
Model will predict what makes a person likely to turn to rail travel, and extensive EDA will help us drill down to a portion of this audience as a trial run. 

Timeline :
Advertising must be ready for holiday travel, so target audience should be chosen by late October. 

## Trade-Offs  
  
Costs of Failure : 
* Choosing the wrong target audience will waste money and resources
* If prediction model is off, we could lose out on a different, valuable audience that isn't identified or represented in the data
  
Benefits of Success : 
* Gaining & retaining the business of college students will provide ridership for at least their 4-year schooling
* Normalizing rail travel among young people can help them change their travel habits permanently

## Evaluation
* Advertising to target audience should produce a 5% increase in young riders from the given routes.
* Expect to gain ~$200 for every trip home, at least twice a year, from college students. 
* Validate using very small target audience at first, and then expand with successes. 
