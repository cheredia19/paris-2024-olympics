---
title: Welcome to your template dataset page!
description: This is a template for publishing your dataset with Datahub Cloud.
---

<FlatUiTable
  data={{
    url: 'medal_table.csv'
  }}
 />

 <PlotlyBarChart
  data={{
    url: 'medal_table.csv'
  }}
  title=""
  xAxis="NOC"
  yAxis="Total"
/>
