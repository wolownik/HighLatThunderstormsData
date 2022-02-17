# HighLatThunderstormsData
The Repository contains filtered high latitudes thunderstorm data and an interactive map presenting mean number of annual thunderstorm days at high latitudes in years 2000-2019

To see interactive thunderstorm map (instead raw html text file) use this address: https://rawcdn.githack.com/wolownik/HighLatThunderstormsData/5f4c921217b40567308899a0cba206bc5c9a1a4b/HighLatThunderstormMap.html

(Click on an individual WMO station on the map to see more details)

Dataset has been prepared on the basis of SYNOP reports downloaded from Ogimet resources (https://www.ogimet.com) and NOAA Integrated Surface Database at https://www.ncdc.noaa.gov/isd/data-access and has been used in manuscript: "Thunderstorm activity at high latitudes observed at manned WMO weather stations" (submitted in consideration for publication in the International Journal of Climatology)

Data folder contains:
- ThunderstormSYNOPsAfterVerification.csv - all SYNOP reports containing information about high latitude thunderstorms from 2000-2019 (which have passed the verification process)
- DataCompletenessPreVerification.csv - data completeness of available WMO reports from high latitude stations
- MapData.rds - RData file with SYNOP data processed in a way it can be easily presented on a map. Allow reproduction of thunderstorm map (script in Rmarkdown format: InteractiveMapRmd.Rmd) 
- TableThunderstormDaysOnStation.csv - file with number of thunderstorm days on each station 
- SelectedStations.csv - file containing number of thunderstorm days recorded in every year at selected high latitude WMO stations characterized by high data continuity (wide 'mts' format)
