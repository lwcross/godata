---
layout: page
parent: Analytics & Dashboards
title: Google DataStudio
nav_order: 5
permalink: /google-datastudio/
---

# Google DataStudio

## _Setting up a Google DataStudio Dashboard for COVID-19 Tracking in Kosovo_
Country use case
{: .label .label-purple }

For monitoring of COVID-19 cases and contact tracing in Kosovo, Google DataStudio was used (outputs below)
![](../assets/googledatastudio-kosovo-1.png)

### Purpose/ objectives: 
1.	To contribute to informing the general public on the current COVID-19 epidemiological situation.
2.	Contribute to information sharing with the general public and other stakeholders to support decision making for the COVID-19 response activities

### The pipeline involved:
1. Query Go.Data API with Python script
2. Recode, clean, filter, aggregrate, in Python
3. Store aggregated output in private Google Spreadsheet
4. Add necessary information manually, not collected in Go.Data
5. Push to Google DataStudio

![](../assets/kosovo-data-flow.png)

To view full resources and scripts, please view the repo [here](https://github.com/WorldHealthOrganization/godata/tree/master/analytics/country_use_cases/godata-Kosovo)

