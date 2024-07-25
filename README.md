---
title: 'Athletes in Paris 2024'
description: ''
---

*By [César Heredia](https://x.com/cahered), data journalist*

<PlotlyBarChart
  data={{
    url: 'by_country_over_100.csv'
  }}
  title="Countries with over 100 athletes"
  xAxis="country"
  yAxis="number_athletes"
/>

<PlotlyBarChart
  data={{
    url: 'by_country_below_100.csv'
  }}
  title="Countries with under 100 athletes"
  xAxis="country"
  yAxis="number_athletes"
/>

<PlotlyBarChart
  data={{
    url: 'year_of_birth.csv'
  }}
  title="Year of birth of athletes"
  xAxis="year"
  yAxis="number_athletes"
/>

<PlotlyBarChart
  data={{
    url: 'athletes_height.csv'
  }}
  title="Height in centimeters of the participating athletes"
  xAxis="height_cm"
  yAxis="height"
/>

## Full list of athletes competing in the 2024 Summer Olympic Games
<FlatUiTable
  data={{
    url: 'data.csv'    
  }}
/>
**NOTE: It includes the alternate athetes*
