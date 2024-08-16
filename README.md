---
title: Regions and continents with the most medals at the Paris 2024 Olympic Games
description: 
---

Although the United States of America and China led the Paris 2024 Olympic Games with 40 gold medals each, **their contribution wasn't enough** to make their respective continents lead the medal table. 

As a continent, Europe led the way with 122 gold medals, followed by Asia (83) and America (62). Without the mighty Russia ([banned from the Olympics due to its involvement in the Ukraine war](https://www.aljazeera.com/news/2024/7/26/which-countries-have-been-banned-from-participating-in-the-olympics)), the Eurasian countries collected 15 golds.

<PlotlyLineChart
  data={{
    url: 'continent_golds.csv'
  }}
  title="Gold medals by continent"
  xAxis="Continent"
  yAxis="Gold Medals"
/>

Let's focus on Europe for a moment. Fourteen countries from Western Europe and 10 from the Central and Eastern region won at least one gold medal. But here's the thing: of the top ten countries in the medal standings, fifty percent belong to Western Europe:

- France: 5th notch in the medal table, 16 gold medals
- Netherlands: 6th, 15 golds
- Great Britain: 7th, 14
- Italy: 9th, 12
- Germany: 10th, 12

On the other hand, Finland didn't win any single medal, [ending a 116-year medal streak in the Summer Olympics](https://www.helsinkitimes.fi/finland/finland-news/domestic/25508-paris-ends-finland-s-116-year-medal-streak-in-summer-olympics.html).

China, Japan, and South Korea gathered 95% of the 77 gold medals won by East Asian nations. Of the countries from Oceania, Australia earned 18 golds, while New Zealand won 10.

Uzbekistan was the best Eurasian performer with eight medals, followed by Georgia (two). Azerbaijan and Kazakstan won one gold each. An AIN athlete (name adopted by the International Olympic Committee to allow the participation in the Paris 2024 Olympic Games of those athletes of Russian and Belarusian nationality who fulfilled the requirements imposed after the suspension of the Russian Olympic Committee and the Belarusian Olympic Committee) won a gold medal.

Hungary was the country from Central and Eastern Europe that won the most gold medals (six), followed by Ukraine, Romania, Bulgaria, Serbia, and Czechia (three).

Brazil stood out from the Latin America and Caribbean region with three golds, followed by Cuba (two). Jamaica, Ecuador, Argentina, Chile, Saint Lucia, the Dominican Republic, Guatemala, and Dominica won one gold medal each.

<PlotlyBarChart
  data={{
    url: 'region_gold.csv'
  }}
  title=""
  xAxis="Region"
  yAxis="Gold Medals"
/>


<PlotlyBarChart
  data={{
    url: 'region_total.csv'
  }}
  title=""
  xAxis="Region"
  yAxis="Medals"
/>

<PlotlyLineChart
  data={{
    url: 'continent_total.csv'
  }}
  title=""
  xAxis="Continent"
  yAxis="Medals"
/>

## Medal table ordered by medals

<FlatUiTable
  data={{
    url: 'medal_table.csv'
  }}
 />

