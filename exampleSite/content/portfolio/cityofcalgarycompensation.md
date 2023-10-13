---
author: "Ahmed Oyeleke"
title: "City of Calgary Compensation"
date: "2023-10-01"
description: "A dashboard created to visualise some trends in the compensation structure for City of Calgary positions from 2019 to 2023"
tags: 
categories: ["themes", "syntax"]
ShowRelated: false
showToc: false
ShowBreadCrumbs: false
---

 
 For this mini-project, I decided to take a look at the City of the Calgary compensation data which is publicly available on the [City of Calgary Open Data Platform](https://data.calgary.ca/Government/Compensation-Disclosure-List/9bze-mzx6)

**ETL**
The source data is relatively clean, containing just 4 columns - Year, Position Title, Minimum Annual Base Rate, and Maximum Annual Base Rate. With just under 15000 rows, it was a <1MB csv file. I decided to make things more interesting by importing the csv into SQL to use SSMS for some prelimniary analysis.

Afterwards I made the following changes:
- Removed Max Base Rate as I deemed it inapplicable to most new hires
- Introduced new columns: Career Level, Salary Group, Department (_Note, I used AI to help with categorising the position titles into departments_)
- Filtered for 2019 to 2023 data

**Visualisation**
The data was then imported into Power BI where the dashboard was built highlight some potentially interesting trends and comparisons.

The interactive report can be viewed at [this link](https://app.powerbi.com/view?r=eyJrIjoiY2QxYjE3OGYtOTM1NS00ZjNmLWI1MmUtZGZjZjQxYzM5ZTMwIiwidCI6ImY1MmYyMTgzLTlmNjctNGFkMi1iNjU2LTZmNzU0ZmUxOTZjYiIsImMiOjZ9).



![This where you put the alt information](/uploads/citycalcompshot.png "Screenshot from the dashboard")

