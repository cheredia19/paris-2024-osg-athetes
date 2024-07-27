---
title: 'Athletes in Paris 2024'
description: ''
---

*By [César Heredia](https://x.com/cahered), data journalist*

Paris 2024 has officially begun! With over 10,5 thousand athletes from 204 countries competing in [32 sports](https://olympics.com/en/sports/#:~:text=Frequently%20Asked%20Questions,are%20in%20the%20Summer%20Olympics%3F), the 30th Summer Olympic Games will take place until August 11.

The capital of France hosts the Olympics for the third time in history, after 1900 and 1924. Back then, the games were held between May 4 and July 27. The venue hosted 3,089 athletes, 2,956 men and 136 women. Now, 5,465 men and 5,281 women take part in this massive sports event, a sign of how things have changed over 100 years.

Thirty-three nations say *present* in the Olympics with 100 or more athletes (16.1% out of 204). The 593 competitors representing the United States make them the largest delegation of the games. The USA, France (572), and Australia (460) are the top three countries with the most athletes.

<PlotlyBarChart
  data={{
    url: 'by_country_over_100.csv'
  }}
  title="Countries with 100 or more athletes"
  xAxis="country"
  yAxis="number_athletes"
/>

More than eight out of 10 countries have less than 100 athletes (83.8%). Ninety-nine have fewer than ten representatives. These include Kuwait, Palestine, Panama, and Cameroon, among others.

<PlotlyBarChart
  data={{
    url: 'by_country_below_100.csv'
  }}
  title="Countries with under 100 athletes"
  xAxis="country"
  yAxis="number_athletes"
/>

Not all athletes represent the country they were born. And Australia is a perfect example of that fact. Of the 460 competitors that will wear Australian uniforms in Paris 2024, at least 323 were born there (70.2%). The rest come from the following countries:


*No data available - 81*

This situation repeats in countries such as France (at least 25 different countries apart from France), Spain (18 different countries), Germany (17), Italy (23), Canada (20), Great Britain (13), and the Netherlands (11), among others.

<PlotlyBarChart
  data={{
    url: 'birth_country.csv'
  }}
  title="Country of birth of the athletes participating in Paris 2024*"
  xAxis="birth_country"
  yAxis="number_athletes"
/>
**NOTE: No country of birth data of 2,814 athletes*

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
  title="Height in centimeters of the participating athletes*"
  xAxis="height_cm"
  yAxis="height"
/>
**NOTE: No height data of 6,738 athletes*

## Alternate athletes

<PlotlyBarChart
  data={{
    url: 'alternate_country.csv'
  }}
  title="Countries with alternative athletes"
  xAxis="country"
  yAxis="alternate_athletes"
/>

<PlotlyBarChart
  data={{
    url: 'discipline_alternates.csv'
  }}
  title="Sports in which alternative athletes are involved"
  xAxis="discipline"
  yAxis="alternate_athletes"
/>

## Individual neutral athletes

<PlotlyBarChart
  data={{
    url: 'ain_disciplines.csv'
  }}
  title="Sports in which AIN athletes are involved"
  xAxis="discipline"
  yAxis="ain_athletes"
/>

## Refugee Olympic Team

<PlotlyBarChart
  data={{
    url: 'refugees_origin.csv'
  }}
  title="Birth countries of refugee athletes"
  xAxis="country_origin"
  yAxis="refugee_athletes"
/>

<PlotlyBarChart
  data={{
    url: 'refugees_residence.csv'
  }}
  title="Residence countries of refugee athletes"
  xAxis="country_residence"
  yAxis="refugee_athletes"
/>

<PlotlyBarChart
  data={{
    url: 'refugee_disciplines.csv'
  }}
  title="Sports in which refugee athletes are involved"
  xAxis="discipline"
  yAxis="refugee_athletes"
/>

## Full list of athletes competing in Paris 2024*

### From A to K

<FlatUiTable
  data={{
    url: 'athletes_a_k.csv'
  }}
/>

### From L to Z

<FlatUiTable
  data={{
    url: 'athletes_l_z.csv'
  }}
/>
**NOTE: It includes the alternate athetes*
