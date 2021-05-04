# Impact of Covid-19 on WA Crimes 


![pic1](readmeimages/Title_Capture.PNG)






# Project Introduction 
The aim of this project is to understand the impacts of Covid-19 on WA crime rates, and what noticable trends we can conclude since 2017 until lockdown in March 2020, and the period after. 



# Structure 
```
|_datasource                                      # data resources 
    |_1800respect.csv
    |_ERP.xls
    |_Pooled data, time series (Tables 28a to 33b).xls
    |_Time series (Tables 4a to 8d).xls
    |_Violence prevalence and time series (Tables 1 to 5).xlsx
    |_WA Police Force Crime Timeseries.xlsx
    |_domestic violence google trend.csv
    |_dv help google trend.csv
    |_googlesearchdvastopic.csv
    |_sasExport.xls
    |_sasexport.xlsx
    |_wa dv help google trend.csv
    |_wadvsearch.csv

|_output                                           # saved cvs and png files 
    |_Crime.png
    |_Regionsdvinto.csv
    |_Regionsdvout.csv
    |_Regionsinto.csv
    |_Regionsout.csv
    |_WAkeycrimeheatmap.png
    |_WAkeycrimetrends.png
    |_crimemap.png
    |_crimerates.png
    |_crimeratesregions.png
    |_crimesoverperiodbar.png
    |_crimespercentchange.png
    |_crimetyperatesregions.png
    |_decreasingcrimes.png
    |_decreasingwacrimes.png
    |_dvmap.png
    |_dvratesregions.png
    |_gercrimerates.png
    |_googlesearchtrends.png
    |_headlines.csv
    |_increasingcrimes.png
    |_searchregressions.png
    |_standardisedcrimes.png
    |_timeframes.csv
    |_wbrcrimerates.png

|_gitignore                                       # gitignore for ignoring some files 
|_Police_Districts.shp
|_Police_Districts.shp.xml
|_Police_Districts.shx
|_Presentation1.pptx
|_Project Proposal - Group 3
|_README.md
|_Maps.ipynb
|_WA Crime Rates.ipynb
|_crimeratesregions.png
|_crimetypecountsregions.png
|_crimetyperatesregions.png
|_dvratesregions.png
```




# Usage
```
# create environment 
conda env create --file envname.yml

# activate environment
conda activate envname
```

# Questions 
1. What was the impact of restrictions on crime in WA?
2. Have all types of crime decreased?
3. What about reports of increased domestic violence?
4. How did Domestic Violence crime change in each region?
5. Are there other indicators of domestic violence?



# Datasets
|Source                                      |Link                                                        |
|--------------------------------------------|------------------------------------------------------------|
|Western Australia Police Force              |https://www.police.wa.gov.au/Crime/CrimeStatistics#/        |
|Estimated Resident Population for WA        |https://profile.id.com.au/wapl/population-estimate?BMID=40  |
|Google Trends                               |https://trends.google.com/trends/?geo=AU                    |
|The Guardian API			     |https://open-platform.theguardian.com/                      |
|WAPOL District Boundaries	             |https://catalogue.data.wa.gov.au/dataset/wa-police-district-boundaries|



# Analysis 
## __What was the impact of restrictions on crime in WA?__
![Impact of Restrictions on Crime in WA](output/crimetyperatesregions.PNG)

Majority of regions experienced decrease in crime during the first ever Covid-19 lockdown period in WA during March, April and May in 2020. The only region that experienced increase in crime was Wheatbelt region. It was mainly Drug Offences that were on icrease in this region, during this period. 

## __What about reports of increased domestic violence?__
![Selection from 200 Guardian headlines on DV and lockdown](DV_Guardian_reports.PNG)

Here is a snapshot of some articles on domestic violence and lockdown.

## __Are there other indicators of domestic violence?__
![Google Search Trends](Google_Search_Trends.PNG)

As victims and offenders were spending more time together with increased social isolation and decreased social movement, we wanted to look at how domestic violence was affected by the lockdown during the same period. Decreased social movement was possibly the main reason which may have restricted avenues for women to seek help. This graph shows the difference in looking up domestic violence as a topic as opposed to looking up the 1800 number in order to seek help. 

## __What is the correlation between DV, 1800 helpline and crime?__
![Correlation Between Helpline Search and Crime Rate](output/searchregressionstogether.PNG)

This graph shows almost no correlation between google searches for domestic violence as a topic and crime rates. However, there is a moderate positive correlation between searches for 1800respect as a keyword and crime. The relationship between domestic violence google search and crime is not as strong as in the previous case. 



# Contributors 
Fern Bradder: (https://github.com/FernB)  
Sri Vegunta: (https://github.com/SriVegunta)  
Petra Moyle: (https://github.com/PetraMoyle)  
