---
title: "Covid Figures and Maps"
author: "Steven Rashin"
date: "June 30, 2020"
output: 
  html_document:
    keep_md: yes
---



## Data Sources

Data for this report comes from:

* The CDC Homepage <https://www.cdc.gov/covid-data-tracker/index.html#county-map> and <https://usafacts.org/visualizations/coronavirus-covid-19-spread-map/>, specifically:
    + Confirmed COVID Cases <https://usafactsstatic.blob.core.windows.net/public/data/covid-19/covid_confirmed_usafacts.csv>
    + Covid Deaths <https://usafactsstatic.blob.core.windows.net/public/data/covid-19/covid_deaths_usafacts.csv>
    + County Population <https://usafactsstatic.blob.core.windows.net/public/data/covid-19/covid_county_population_usafacts.csv>
* Covidtracker.com data (used by Johns Hopkins <https://coronavirus.jhu.edu/us-map>) <https://covidtracking.com/api/v1/states/daily.csv>
* World Health Organization <https://covid19.who.int/>
* Somerville City data <https://somerville-dashboardcovid.trial.opendatasoft.com/pages/citysdashboard/>

## Headline Numbers 
As of June 29, 2020:  

* 39,131 new cases  
* 349 new deaths  

Consequently there are now:  

* 2,572,466 total cases  
* 125,352 total deaths  

## Overall Covid Cases In The USA

Regions are defined as follows: Northeast (CT, ME, MA, NH, RI, VT, NJ, NY, PA), Midwest (IN, IL, MI, OH, WI, IA, KS, MN, MO, NE, ND, SD), South (AL, AR, DC, DE, FL, GA, KY, LA, MD, MS, NC, OK, SC, TN, TX, VA, WV) and West (AZ, CO, ID,  NM, MT, UT, NV, WY,AK,CA,HI,OR,WA).

![](Covid-Figures-and-Maps_files/figure-html/cars-1.png)<!-- -->

## US Cases Compared to World Cases
![](Covid-Figures-and-Maps_files/figure-html/US v World-1.png)<!-- -->

## Covid Cases in Somerville, MA in the Last Two Weeks
![](Covid-Figures-and-Maps_files/figure-html/Somerville-1.png)<!-- -->

## Covid Cases in MA in the Last Two Weeks 
![](Covid-Figures-and-Maps_files/figure-html/MA Cases-1.png)<!-- -->

## Latest Cases in Boston Area


Date         County Name         Cases   Deaths   New Cases   New Deaths
-----------  -----------------  ------  -------  ----------  -----------
2020-06-29   Middlesex County    23946     1862          31            7
2020-06-28   Middlesex County    23915     1855          56            6
2020-06-27   Middlesex County    23859     1849          73           10
2020-06-26   Middlesex County    23786     1839          45           14
2020-06-25   Middlesex County    23741     1825          44            5
2020-06-24   Middlesex County    23697     1820          50            8
2020-06-23   Middlesex County    23647     1812          38            3
2020-06-22   Middlesex County    23609     1809          35            2
2020-06-29   Norfolk County       9161      930          10            3
2020-06-28   Norfolk County       9151      927          26            0
2020-06-27   Norfolk County       9125      927          25            0
2020-06-26   Norfolk County       9100      927          18            3
2020-06-25   Norfolk County       9082      924          26            1
2020-06-24   Norfolk County       9056      923          14            4
2020-06-23   Norfolk County       9042      919          32            5
2020-06-22   Norfolk County       9010      914          16            2
2020-06-29   Suffolk County      19795     1007           0            3
2020-06-28   Suffolk County      19795     1004          31            0
2020-06-27   Suffolk County      19764     1004          57            7
2020-06-26   Suffolk County      19707      997          43            7
2020-06-25   Suffolk County      19664      990          36            6
2020-06-24   Suffolk County      19628      984          27            8
2020-06-23   Suffolk County      19601      976          34            0
2020-06-22   Suffolk County      19567      976          16            0

## New Covid Cases By State: Log Scale Cases

![](Covid-Figures-and-Maps_files/figure-html/unnamed-chunk-1-1.png)<!-- -->

## Latest County Case Map
![](Covid-Figures-and-Maps_files/figure-html/unnamed-chunk-2-1.png)<!-- -->

## Latest County Death Map
![](Covid-Figures-and-Maps_files/figure-html/deaths_by_county-1.png)<!-- -->


## Top 5 Counties: Today and The First of Each Month

Date         State   County Name            Cases   Deaths
-----------  ------  -------------------  -------  -------
2020-06-29   CA      Los Angeles County    100772     3326
2020-06-29   IL      Cook County            90122     4554
2020-06-29   NY      Queens County          65325     6609
2020-06-29   NY      Kings County           59576     7031
2020-06-29   NY      Bronx County           47555     4680
2020-06-01   IL      Cook County            78495     3658
2020-06-01   NY      Queens County          62094     6271
2020-06-01   NY      Kings County           56053     6742
2020-06-01   CA      Los Angeles County     55968     2362
2020-06-01   NY      Bronx County           45359     4480
2020-05-01   NY      Queens County          52274     5111
2020-05-01   NY      Kings County           45519     5320
2020-05-01   IL      Cook County            38668     1673
2020-05-01   NY      Bronx County           37785     3527
2020-05-01   NY      Nassau County          36161     1720
2020-04-01   NY      Queens County          15217      447
2020-04-01   NY      Kings County           12274      328
2020-04-01   NY      Westchester County     10683       64
2020-04-01   NY      Nassau County           9554       76
2020-04-01   NY      Bronx County            8607      360
2020-03-01   CA      Santa Clara County        13        2
2020-03-01   WA      King County                9        1
2020-03-01   IL      Cook County                3        0
2020-03-01   WA      Snohomish County           2        0
2020-03-01   CA      Sacramento County          2        0
2020-02-01   IL      Cook County                2        0
2020-02-01   CA      Santa Clara County         2        0
2020-02-01   MA      Suffolk County             1        0
2020-02-01   AZ      Maricopa County            1        0
2020-02-01   WA      King County                1        0

## Total Covid Cases By State: Free Scale Cases
![](Covid-Figures-and-Maps_files/figure-html/unnamed-chunk-3-1.png)<!-- -->

## Hospitalizations By State

![](Covid-Figures-and-Maps_files/figure-html/hospitalizations-1.png)<!-- -->

## Week to Week Changes in COVID Cases

![](Covid-Figures-and-Maps_files/figure-html/week-to-week-1.png)<!-- -->

## Cases as a Percentage of State Population
![](Covid-Figures-and-Maps_files/figure-html/unnamed-chunk-4-1.png)<!-- -->

## Northeast Cases By Month
![](Covid-Figures-and-Maps_files/figure-html/New Northeast-1.png)<!-- -->


## Cases By State Over Time

![](Covid-Figures-and-Maps_files/figure-html/unnamed-chunk-5-1.png)<!-- -->


## Deaths By State Over Time

![](Covid-Figures-and-Maps_files/figure-html/deaths by state-1.png)<!-- -->

## Positive Tests Over Negative Tests in the Last Two Weeks

![](Covid-Figures-and-Maps_files/figure-html/ratio-1.png)<!-- -->

## Currently Hospitalized Patients

![](Covid-Figures-and-Maps_files/figure-html/icu-1.png)<!-- -->

## Patients Currently on Ventilators 

![](Covid-Figures-and-Maps_files/figure-html/vent-1.png)<!-- -->

## Different Counts from Different Data

See the difference between <https://covidtracking.com/api/v1/states/daily.csv> and <https://usafacts.org/visualizations/coronavirus-covid-19-spread-map/>

![](Covid-Figures-and-Maps_files/figure-html/differences-1.png)<!-- -->



