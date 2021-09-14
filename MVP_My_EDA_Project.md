## MVP for EDA Project
#### MYC Turnstiles data analysis for WomenTechWomenYes (WTWY) International 

- The goal of this project is to help WomenTechWomenYes(WTWY) to know where to locate their team and collect the sign-up effectively. 

- The analysis uses the NYC - MTA turnstile data from 05/01/2021 to 08/31/2021.
- Which stations are the businest stations - with the Top 10 highest traffic flows during the weekday and on the weekend
![](https://github.com/CodeHana/DA_Project/blob/main/DA_Project/Busiest_NYC_Subway.png)

To get the top stations with busiest traffic flow. 
I used the sum of daily entries differences and daily exits differences to get the total riders per day in each station. 
Because some stations have larger number in daily entries, some has larger in exits (as shown in the graphs below), therefore I consider both exits and entries is to reduce the bias

![](https://github.com/CodeHana/DA_Project/blob/main/DA_Project/NYC_weekdayRiders.png)
![](https://github.com/CodeHana/DA_Project/blob/main/DA_Project/NYC_weekendRiders.png)

The top 10 stations (weekday and weekend) from 05/01/2021 to 08/31/2021 (xtick shows Monday total riders)


#### To follow up
1. Shows the traffic flows trend of top 10 stations from Monday to Sunday - tells the team when's better to get collect the sign-up
2. Shows the analysis result through map visulization 
3. Mapping the results with the top income data from  [Household Median Incomes](https://data.cccnewyork.org/data/map/66/median-incomes#66/50/6/107/62/a/a): to know which area has more high salary or high income family. 
