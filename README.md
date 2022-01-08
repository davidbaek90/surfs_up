# Surfs Up Analysis

## Overview of Surfs Up Analysis
### Purpose

#### The purpose of the Surfs Up Analysis is to study the Oahu temperature data for the months of June and December. This data will help identify whether not if the upcoming surf and ice cream shop business will be able to reach operational feasibility year-around.

## Results
#### Three Key Differences In Weather Between June and December
1. Looking at the summary statistics for both months, the average temperature in June is 74.9°F and 71.0°F in December. Refer to the first two images below.
2. The lowest temperature was recorded 64°F in June, where as 56°F for December.
3. Both in June and December, temperature showed a relatively consistant 1st, 2nd and 3rd quartiles, showing a steady and gradual increase and decrase in temperature through the month. Please refer to the next two images below.

<p align="center">
<b>Smmary Statistics - June Temperature</b>
</p>  
<p align="center">
  <img src="https://raw.githubusercontent.com/davidbaek90/surfs_up/main/Resources/junedata.png">
</p>

<p align="center">
<b>Summary Statistics - December Temperatuere</b>
</p>
<p align="center">
<img src="https://raw.githubusercontent.com/davidbaek90/surfs_up/main/Resources/decdata.png">
</p>

<p align="center">
<b>Frequency of June Temperatures</b>
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/davidbaek90/surfs_up/main/Resources/junetemp.png">
</p>

<p align="center">
<b>Frequency of December Temperatures</b>
</p>
<p align="center">  
  <img src="https://raw.githubusercontent.com/davidbaek90/surfs_up/main/Resources/dectemp.png">
</p>

## Summary
#### High Level Summary of the Results
- Looking at the weather data of the June and December in Oahu, the two months show a relatively similar weather patterns. The temperature data show gradual increase and decrease through the months without skewed data, and relatively symmetrical around the mean temerature. From this data we can conclude that it is feasible to operate the surf and ice cream shop all year around in Oahu.

#### Two Additional Querries For June and December
- Two additional querries can be conducted to get more weather information of June and December in Oahu.
- The first querry that I have done is to correlate the temperature data with the amount of precipiation for each months. Below two images show the scatter plot of temperature vs precipitation for the months of June and December.
- This information is helpful to understand at which temperature you would expect most precipiatation, which would help you to make smarter choices in surf/ice cream business operation.

<p align="center">
<b>June Temperature vs Precipitation</b>
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/davidbaek90/surfs_up/main/Resources/dectempvsprcp.png">
</p>

<p align="center">
<b>December Temperatures vs Precipitation</b>
</p>
<p align="center">  
  <img src="https://raw.githubusercontent.com/davidbaek90/surfs_up/main/Resources/junetempvsprcp.png">
</p>

- Second querry that would be helpful to perform is to filter the precipiation data based on each day/week of the month. If a pattern show that certain days/weeks of the months are known to have higher precipitation, it would affect the surf and ice cream business differently.
- The second querry would require manipulation of dat as date information consist of YYYY-MM-DD. You would need splite and elimianate YYYY from the date date, and do a similar querry the temperautre/precipitation measurements based on day of the week for each month.
