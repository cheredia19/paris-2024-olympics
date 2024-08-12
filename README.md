---
title: Welcome to your template dataset page!
description: This is a template for publishing your dataset with Datahub Cloud.
---

## Medal table ordered by medals

<FlatUiTable
  data={{
    url: 'medal_table.csv'
  }}
 />

<PlotlyBarChart
  data={{
    url: 'region_gold.csv'
  }}
  title=""
  xAxis="Region"
  yAxis="Gold Medals"
/>

<PlotlyLineChart
  data={{
    url: 'continent_golds.csv'
  }}
  title=""
  xAxis="Continent"
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
