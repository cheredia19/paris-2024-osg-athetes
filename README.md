---
title: 'A glimpse on the athletes competing in Paris 2024'
description: 'Almost 11K athletes from 204 countries, AIN, and the Refugee Olympic Team, will pursue the glory of the victory until mid-August'
---

*By [César Heredia](https://x.com/cahered), data journalist*

Paris 2024 has officially begun! With **over 10,5 thousand athletes from 204 countries** competing in [32 sports](https://olympics.com/en/sports/#:~:text=Frequently%20Asked%20Questions,are%20in%20the%20Summer%20Olympics%3F), the 30th Summer Olympic Games will take place until August 11.

The capital of France hosts the Olympics for the third time in history, after 1900 and 1924. Back then, the games were held between May 4 and July 27. The venue hosted 3,089 athletes, 2,956 men and 136 women. Now, **5,465 men and 5,281 women take part in this massive sports event**, a sign of [how things have changed](https://www.nbcolympics.com/news/paris-2024-sets-milestone-first-olympics-achieve-full-gender-parity) over 100 years.

Thirty-three nations say *present* in the Olympics with 100 or more athletes (16.1% out of 204). The 593 competitors representing the United States make them **the largest delegation of the games**. The USA, France (572), and Australia (460) are the top three countries with the most athletes.

<PlotlyBarChart
  data={{
    url: 'by_country_over_100.csv'
  }}
  title="Countries with 100 or more athletes"
  xAxis="country"
  yAxis="number_athletes"
/>

Meanwhile, more than eight out of 10 countries have less than 100 athletes (83.8%). **Ninety-nine have fewer than ten representatives**. These include Kuwait, Palestine, Panama, and Cameroon, among others.

<PlotlyBarChart
  data={{
    url: 'by_country_below_100.csv'
  }}
  title="Countries with under 100 athletes"
  xAxis="country"
  yAxis="number_athletes"
/>

Not all athletes represent the country they were born. And **Australia is a perfect example** of that fact. Of the 460 competitors that will wear Australian uniforms in Paris 2024, at least 323 were born there (70.2%). The rest come from the following countries:

<FlatUiTable
  data={{
    url: 'non_australia_born.csv'
  }}
/>
*No data available: 81*

This situation repeats in countries such as France (a minimum of 25 different countries apart from France), Spain (18 different countries), Germany (17), Italy (23), Canada (20), Great Britain (13), and the Netherlands (11), among others.

The following bar chart shows the country of birth of 73.8% of the athletes participating in the Olympic Games.

<PlotlyBarChart
  data={{
    url: 'birth_country.csv'
  }}
  title="Country of birth of the athletes participating in Paris 2024*"
  xAxis="birth_country"
  yAxis="number_athletes"
/>
**NOTE: No country of birth data of 2,814 athletes*

According to the data available, **at least 824 athletes live in the United States**. 438 competitors have France as their country of residence, while 377 reside in Germany, 330 in Spain, and 312 in Great Britain.

## A look at athletes' year of birth and height

The oldest active athlete who participates in the current Summer Olympic Games is 65 years old. **Juan Antonio Jiménez Cobo**, a Spaniard equestrian athlete, was born on May 11, 1959. Some media outlets claim the eldest is [Mary Hanna](https://olympics.com/en/athletes/mary-hanna) from Australia, who is 69  and competing in her seventh Olympiads. However, she is an *alternate athlete*.

At the other end, the youngest competitor in Paris 2024 is the Chinese skateboarder [Haohao Zheng](https://olympics.com/en/athletes/haohao-zheng), who will be 12 years old by August 11, the day that the Games end.

By decade, 114 athletes (active or alternate) were born between 1954 and 1980, while 1075 did it in the 80s. **From 1991 to 2000, 7159 competitors were born (62.7%)**, and 3071 came to life in the current century.

46.7% of the athletes (5339) in the current Olympics **were born between 1996 and 2001**. The years with more births were 1999 (876) and 2000 (874). The graphic below shows all the births by year, from 1954 (Hanna) to 2012 (Zheng).

<PlotlyBarChart
  data={{
    url: 'year_of_birth.csv'
  }}
  title="Year of birth of athletes"
  xAxis="year"
  yAxis="number_athletes"
/>

The tallest athlete of the 2024 Summer Olympic Games is the French sensation Victor Wembayama (224 centimeters), while the shortest is, according to our records, Zambian female footballer [Avell Chitundu](https://olympics.com/en/paris-2024/athlete/1925995), with a height of 140 centimeters.

The country that has the highest average height is South Sudan, thanks to the fact that of the 14 athletes who represent the African nation, 12 belong to the men's basketball team, while the shortest on average is Myanmar.

Of the available data, the most repeated height is 170 centimeters (5.57 ft). The graphic below shows all the heights of the competing athletes:

<PlotlyBarChart
  data={{
    url: 'athlete_height.csv'
  }}
  title="Height in centimeters of the participating athletes*"
  xAxis="height_cm"
  yAxis="height"
/>
**NOTE: No height data of 6,738 athletes*

## The *alternate athletes*: not official athletes until...

The alternates are athletes ready to compete at a moment's notice, prepared to step in if needed but [face certain challenges](https://www.triathlete.com/events/olympics/what-is-it-like-to-be-an-olympic-alternate/). These include **some restrictions until they are officially called to compete**. 

The fact that they are not credentialed athletes **limits their access to the Paris 2024 course and other official venues**. Consequently, alternate athletes do not receive the same support or access to the Olympic Village until they replace an official team member.

There are **673 alternate athletes** from 69 countries. The USA is the nation with more alternates athletes with 60, followed by France (50), Germany (41), and Japan (37).

<PlotlyBarChart
  data={{
    url: 'alternate_country.csv'
  }}
  title="Countries with alternate athletes"
  xAxis="country"
  yAxis="alternate_athletes"
/>

The *alternates* will be ready to step in if anything happens in 12 sports. Athletics and Football are the disciplines with more alternate athletes (154 and 111, respectively).

<PlotlyBarChart
  data={{
    url: 'discipline_alternates.csv'
  }}
  title="Sports in which alternative athletes are involved"
  xAxis="discipline"
  yAxis="alternate_athletes"
/>

## Individual Neutral Athletes

As explained in [olympics.com](https://olympics.com/ioc/paris-2024-individual-neutral-athletes), Individual Neutral Athletes (AIN, or *Athlètes Individuels Neutres* in French) are athletes "**with Belarusian or Russian passports** confirmed as eligible and invited to compete at the Summer Olympic Games Paris 2024." 

Quotas for AIN were determined on the field of play through the existing qualification competitions and the specific eligibility requirements of the International Federations, said olympics.com on their website.

The chart below specifies the sports in which the 31 AINs will participate in Paris 2024:

<PlotlyBarChart
  data={{
    url: 'ain_disciplines.csv'
  }}
  title="Sports in which the AINs are involved"
  xAxis="discipline"
  yAxis="ain_athletes"
/>

## The Refugee Olympic Team 

At the Paris 2024 Olympic Games, **37 refugee athletes will participate** in the competition. The figure represents the largest since the inception of International Olympic Committee refugee teams at the Rio De Janeiro Games 2016.

Fifteen athletes of the Refugee Olympic Team *(l’Équipe Olympique des Réfugiés, EOR)* were born in **Iran**. Syria and Afghanistan follow the Islamic Republic with five and four representatives, respectively. For the second Games in a row, a Venezuelan-born athlete is a member of the refugee Olympic team. Shooter **Edilio Centeno**, from Barquisimeto town, is one of the two Latin Americans (along with Cuban weightlifter **Ramiro Mora**) that are part of this group.

<PlotlyBarChart
  data={{
    url: 'refugees_origin.csv'
  }}
  title="Birth countries of refugee athletes"
  xAxis="country_origin"
  yAxis="refugee_athletes"
/>

Ten refugees live in Germany, five in Great Britain, and four in France. The Netherlands and Switzerland host three refugee athletes each, while Israel and Italy have given two competitors each a home.

<PlotlyBarChart
  data={{
    url: 'refugees_residence.csv'
  }}
  title="Residence countries of refugee athletes"
  xAxis="country_residence"
  yAxis="refugee_athletes"
/>

The refugee athletes will be involved in 12 sports: athletics, badminton, boxing, breaking, canoeing (slalom, and sprint), cycling, judo, shooting, swimming, taekwondo, weightlifting, and wrestling. You can see this as a bar chart below:

<PlotlyBarChart
  data={{
    url: 'refugee_disciplines.csv'
  }}
  title="Sports in which refugee athletes are involved"
  xAxis="discipline"
  yAxis="refugee_athletes"
/>

## Full list of athletes competing in Paris 2024*

Between athletes and alternate athletes, Paris 2024 will have 11,419 competitors. In the two tables below, you can read the basic information of each one, ordered by name.

Remember that you can filter by name, gender, whether the athlete is alternate or not, country, height in centimeters, sport (discipline), event, birth date, year of birth, place of birth, country of birth, place of residence, country of residence, nickname, hobbies, occupation, education, family, spoken languages, coach, reason (of practicing the sport), hero, influence, philosophy, sporting relatives, ritual, and other sports (subject to the availability of data).

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
