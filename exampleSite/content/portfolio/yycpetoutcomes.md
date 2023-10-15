---
author: "Ahmed Oyeleke and Robin Simcoe"
title: "[Ongoing] Pet Impound Outcomes City of Calgary"
date: "2023-10-10"
description: "An analysis of trends with impounded pets in the City of Calgary before, during and after the COVID-19 pandemic"
tags: ["Data", "Dashboard"]
categories: 
ShowRelated: false
showToc: false
ShowBreadCrumbs: false
---

_This project is ongoing, keep an eye out for the results._  

A colleague and I decided to take a look at data on pet impound outcomes available on [City of Calgary Open Data Platform](https://data.calgary.ca/Services-and-Amenities/Pets-Impound-Outcomes/jmrf-j94e) to identify any trends around pets surrenders. Many people got pets during the pandemic as a result of lockdowns and extensive time being spent indoors. We suspect that a number of these owners began to surrender their pets after lockdowns were lifted and many returned to working onsite.

**ETL**  
The source data is relatively clean, containing 5 columns, details of each column can be found below:
- Date: These are grouped by Month. January 2019, February 2019, etc
- Outcome: Five different outcomes are defined in the data, details are below where the decriptios is not clear:
  * Return to Owner
  * Adoption
  * Euthanasia
  * Transfer: Animal was sent to another pound or facility
  * Other: Includes Disposal (when a deceased animal comes to Animal Services Centre, typically hit by a car, and teh body is sent for cremation). DOA (the term used for “dead on arrival” and typically gets used when an animal is taken to a vet clinic deceased, and there is no indication as to why). In Kennel (Still being kenneled at animal service at the time of this data being collected).
- Animal: This column contains two unique values, dogs and cats
- Volume: Number of pets 

**Analysis**  
Data is available from 2012 April to 2023 March. To normalise, we will only be considering data in the 10 year periond starting from January 2013 to December 2022 inclusive. There is no data for November and December 2016.


**Visualisation**  
Created using Power BI, the interactive report can be viewed at [this link]().

**Collaborator(s)**  
I worked with Robin Simcoe on this report. She can be reached at [this link]().

![This where you put the alt information](/uploads/yycpetoutcomesquery.png "Data import into Power BI")


<!-- ![This where you put the alt information](/uploads/self.webp "Data Import into Power BI") -->

