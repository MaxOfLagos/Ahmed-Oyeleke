---
author: "Ahmed Oyeleke and 4 others"
title: "Historical Global Causes of Death [1990-2019]"
date: "2023-11-06"
description: "A dashboard created to visualise data on causes of death from around the world from 1990 to 2019"
tags: ["Data", "Dashboard"]
categories: 
ShowRelated: false
showToc: false
ShowBreadCrumbs: false
---

**ETL**  
Data was sourced from [Kaggle](https://www.kaggle.com/datasets/iamsouravbanerjee/cause-of-deaths-around-the-world) and imported into PowerBI.

Some key steps
- Power Query: Unpivot the cause columns
- Power Query: Create Dimension Table for categories (Cause Categories on the dashboard)
- Power Query: Create Dimension Table for Regions and Income Group
- Assign Foreign Key of Country Code in Dimension Table containing Region and Income Level data
- Assign Foreign Key of Cause in Dimension Table for Categories
- Create mesaures for total death by Categories and Income Groups

Future Plans
- Add a second page for country-specific visualisations and comparisons

**Group Members**  
My project group comprised of these invividuals:
- [Robin Simcoe](https://www.linkedin.com/in/robin-simcoe-3739b3262/)
- [Steven Zhang]()
- [Olayinka Daramola](https://www.linkedin.com/in/olayinka-daramola-1b323a92/)
- [Jason Phung](https://www.linkedin.com/in/jasonphungab/)

## Interactive Dashboard
The interactive report can be used below. If you face any issues with using it the embedded report below, it can be viewed externally at [this link](https://app.powerbi.com/view?r=eyJrIjoiYWUzNTJiMDEtMDhkYy00MjE0LTg5YTctOTU1Y2ZiZWQ5ZmViIiwidCI6ImY1MmYyMTgzLTlmNjctNGFkMi1iNjU2LTZmNzU0ZmUxOTZjYiIsImMiOjZ9).

<!-- raw html -->
{{<rawhtml>}}
<iframe title="Report Section" width="1920" height="1110" src="https://app.powerbi.com/view?r=eyJrIjoiYWUzNTJiMDEtMDhkYy00MjE0LTg5YTctOTU1Y2ZiZWQ5ZmViIiwidCI6ImY1MmYyMTgzLTlmNjctNGFkMi1iNjU2LTZmNzU0ZmUxOTZjYiIsImMiOjZ9" frameborder="0" allowFullScreen="true"></iframe>
{{</rawhtml>}}

