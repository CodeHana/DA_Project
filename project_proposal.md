### Project Proposal for 

#### Question/need:

The WomenTechWomenYes (WTWY) International are placing their street teams at entrances to subway stations to collect the sign up from the crowd. 
WTWY wants to 
* Collect the sign up (signatures, email and addresses) as many as possible 
* find the people who may be interested in attending the gala, passionate about the participation of women in technology

The purpose of the analysis is plan to bulid a system that helps the team to know that
1) What are the top N stations that has the high flow of crowd? 
2) When is the peak of the flow? 
3) Which area/statios may have people more intrested in attending the WTWY events?  

The WTWY International can benefit from the system by
- Knowing where is more efficient in collecting the signatures and  may have people more likely to attend the gala event, so that the WTWY can dispatch teams to these high flow stations
- Knowing when to locate more resouces for collecting the sign-up


#### Data Description:
* [MTA turnstile data](http://web.mta.info/developers/turnstile.html): provides information of the patterns of transit traffic in New York City. The data helps to know when and at which stations and when has high flow of crowd
* [Citywide Payroll Data](https://data.cityofnewyork.us/widgets/k397-673e?mobile_redirect=true) and [Household Median Incomes](https://data.cccnewyork.org/data/map/66/median-incomes#66/50/6/107/62/a/a): to know which area has more high salary or high income family. 
* [zipatlas](http://zipatlas.com/us/ny/new-york.htm): to know which area has more female population
* [NYC PUBLIC SCHOOLS GRADUATION RATE DATA](https://data.nysed.gov/gradrate.php?year=2020&instid=7889678368): to know which area has high quality/ high graduation rate of schools with more female students 



#### Tools:
* Using python, sqlalchemy to analyis and matplotlib to visualize the analysis results
* Maybe incorporate with google map to visualize the map results in New your city 

#### MVP Goal:

The goal of the Analysis tell the WTWY street team when and where to locate their team and collect the sign-up effectively. Therefore, the results of the project will show
* Which stations and when (not including the weekend) has more commuting people 
* Which areas have more female population with high income
* Which area have more female students in good quality school (using high graduation rate as indicator)

