# Air-Quality
1. INTRODUCTION In this project, we discuss the analysis of the dataset “air quality”, that represent Contains the responses of a gas multisensory device deployed on the field in an Italian city Contains the responses of a gas multisensory device deployed on the field in an Italian city. Hourly responses averages are recorded along with gas concentrations references from a certified analyzer. with the goal of studying the similarity between the time series and discovering interesting sequential patterns. Instead, for the analysis of alternative classification methods and outlier detection, we used the dataset “The dataset contains 9358 instances of hourly averaged responses from an array of 5 metal oxide chemical sensors embedded in an Air Quality Chemical Multisensor Device.


3. TIME SERIES
4.1 DATA ANALYSIS
The dataset is Data were recorded from March 2004 to February 2005 (one year)representing the longest freely available recordings of on field deployed air quality chemical sensor devices responses ,
The dataset is characterized by the following attributes:
- Date: represents the date in the format (AAAA-MM-DD) - Time : True hourly averaged concentration (HH.MM.SS) - PT08.S1: hourly averaged sensor response (nominally CO targeted) - NMHC(GT): True hourly averaged overall Non Metanic HydroCarbons concentration in microg/m^3 - C6H6(GT): True hourly averaged Benzene concentration in microg/m^3 - PT08.S2(NMHC): PT08.S2 (titania) hourly averaged sensor response (nominally NMHC targeted) - NOx(GT):True hourly averaged NOx concentration in ppb - PT08.S3(NOx): hourly averaged sensor response (nominally NOx targeted)
-NO2(GT): True hourly averaged NO2 concentration in microg/m^3(reference analyzer) -PT08.S4 : hourly averaged sensor response (nominally NO2 targeted) -PT08.S5: (indium oxide) hourly averaged sensor response (nominally O3 targeted) -Temperature in Ã‚Â°C -Relative Humidity (%) -AH Absolute Humidity

but, for simplicity we took in consideration only the “Date” and the “Open” attributes.


