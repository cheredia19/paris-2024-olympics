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

On the other hand, **Finland didn't win any medal**, [ending a 116-year medal streak in the Summer Olympics](https://www.helsinkitimes.fi/finland/finland-news/domestic/25508-paris-ends-finland-s-116-year-medal-streak-in-summer-olympics.html).

China, Japan, and South Korea gathered **95% of the 77 gold medals** won by East Asian nations. Of the countries from Oceania, Australia earned 18 golds, while New Zealand won 10.

Uzbekistan was the **best Eurasian performer** with eight medals, followed by Georgia (two). Azerbaijan and Kazakstan won one gold each. An AIN athlete (name adopted by the International Olympic Committee to allow the participation in the Paris 2024 Olympic Games of those athletes of Russian and Belarusian nationality who fulfilled the requirements imposed after the suspension of the Russian Olympic Committee and the Belarusian Olympic Committee) won a gold medal.

Hungary was the country from Central and Eastern Europe that won the most gold medals (six), followed by Ukraine, Romania, Bulgaria, Serbia, and Czechia (three).

Brazil stood out from the Latin America and Caribbean region with three golds, followed by Cuba (two). Jamaica, Ecuador, Argentina, Chile, Saint Lucia, the Dominican Republic, Guatemala, and Dominica won one gold medal each.

The Islamic Republic of Iran, despite the [14 Iranian athletes who fled the country and represented the Refugee Olympic Team](https://www.newarab.com/analysis/why-there-are-so-many-iranians-refugee-olympic-team), got three gold medals in Paris. Bahrain and Algeria (two each) followed Iran as the MENA countries with the most gold medals. Israel, Egypt, Tunisia, and Morocco won one each.

Of the Sub-Saharan Africa region, Kenya excelled with four gold medals. South Africa, Ethiopia, Botswana, and Uganda also reached the pinnacle of the podium.

The Philippines and Indonesia were the Southeast Asian countries that did best, with two golds each.

The bar chart below shows the total number of gold medals each region accumulated at the Paris 2024 Summer Olympics.

<PlotlyBarChart
  data={{
    url: 'region_gold.csv'
  }}
  title="Gold medals by region"
  xAxis="Region"
  yAxis="Gold Medals"
/>

## A similar trend

Considering the total number of medals (gold, silver, and bronze), **Europe gathered the most medals at the last Olympic Games**, followed by the American and Asian continents. The graph below shows the total number of medals won by each continent.

<PlotlyLineChart
  data={{
    url: 'continent_total.csv'
  }}
  title="Total medals by continent"
  xAxis="Continent"
  yAxis="Medals"
/>

Spread out regionally, Western European countries again showed their muscle in Olympic sports. The 14 nations from this region **claimed 316 medals**. East Asia (186) and North America (153) accumulated at least 150 medals. **No other region won over 100 medals** in the past Olympic games.

The graphic below shows the medals won by region in Paris 2024. The medal labeled as *No region* was a bronze earned by an athlete from the Refugee Olympic Team.

<PlotlyBarChart
  data={{
    url: 'region_total.csv'
  }}
  title="Total medals by region"
  xAxis="Region"
  yAxis="Medals"
/>

## Medal table ordered by Gold, Silver, and Bronze medals

The following table displays the final standings from the Paris 2024 Summer Olympic Games, ordered by the number of gold, silver, and bronze medals by each National Olympic committee. It can be filtered by NOC, continent, or region. Ranks can also be set based on the number of medals per type and total. Data is available to download in CSV and JSON formats.

<FlatUiTable
  data={{
    url: 'medal_table.csv'
  }}
 />
