## Motivation for Analysis

The Peace Corps is a U.S. Government program that sends American volunteers all over the world to work on community-driven projects in education, health, agriculture, youth development, and more. The mission of the Peace Corps is to promote world peace and friendship by helping countries develop and build understanding between cultures. Volunteers typically commit two years of service, and stay in their country or region of assignment until their service is complete.

Until recently, the Peace Corps kept their early resignation data confidential to avoid potential backlash from reports of negative experiences. Thanks to the Data Liberation Project, this information is now publicly available and free to analyze. The Data Liberation Project is dedicated to acquiring, preserving, and sharing valuable public data that might otherwise remain inaccessible. By promoting transparency, the project empowers researchers, journalists, and the public to draw meaningful insights from newly available datasets. 

My motivation for analyzing this data comes from the unique opportunity to learn more about the experiences of past volunteers and to provide insight to future volunteers. With this information now publicly available, we can analyze patterns and trends of early volunteer departures and the primary reasons for leaving each country. These insights can help future volunteers make informed decisions when planning their service trips to curate a more positive and successful experience.

Informative links:

[About the Peace Corps](https://www.peacecorps.gov/what-we-do/our-mission/)

[About the Data Liberation Project](https://www.peacecorps.gov/)


## Data Overview
This dataset provides an overview of Peace Corps volunteers who resigned before the end of their natural service contract. Data is organized by service locations and the reasons for resignation, allowing volunteers to select up to two reasons for their early resignation. Each row represents an aggregate of the number of volunteers for each combination of reasons by country. For example, if 5 Zimbabwe volunteers cited "mental health" and "amount of work," the count of that unique row would be 5. 

Data is available through July 31, 2023, but the start of the covered period is unclear. However, even with this limitation, the data reveals interesting trends for volunteer resignations and the potential conflicts that volunteers experience in various countries. In addition, I supplemented this analysis with a Peace Corps dataset (2007–2020) providing detailed insights into volunteer numbers and early resignations by country and year.

Links to Data Sources:

[Data Liberation Project](https://www.data-liberation-project.org/datasets/peace-corps-resignations/)

[Early Resignation Data 2007-2020](https://www.peacecorps.gov/about-the-agency/policies-and-publications/reports-and-documents/?search_text=Early%20Termination%20Data%20by%20Country%20-%20Annual%20Method%20-%20FY%202007-2020%20%5BCSV%5D)


## Summary of Findings

My analysis of Peace Corps resignation data shows an average of 186 resignations per country, with 2019 standing out as the peak year, totaling 4,128 early departures. The most common reason cited for leaving was "no reason listed" followed by family-related reasons, while Morocco recorded the highest number of resignations due to the "amount of work." Of all participating countries, only 14 had zero early terminations, highlighting the widespread nature of early departures. Africa led all regions in both the total number of volunteers and the highest number of resignations, demonstrating the unique challenges and demands of service in that continent. 

<img src="Total Volunteers by Region 2007 to 2020.png" alt=" Total Volunteers by Region 2007 to 2020" width="50%">
<img src="Primary Reasons for Resignation by Country - Ecuador.png" alt=" Primary Reasons for Resignation by Country - Ecuador" width="50%">
<img src="Average Resignations by Country.png" alt=" Average Resignations by Country" width="50%">



## Directions on How to Use GitHub Web Editor

Are you logged into github? Just press the period key right now. This will load the web editor. Then install the malloy extension. See images below for reference:
| **Step**   | **Image Preview** |
|--------|-----------|
| `Step 1 - Press allow` | <img src="step1.png" width="50%"> |
| `Step 2 - Click the Blocks, search for Malloy, install` | <img src="step2.png" width="50%"> |
| `Step 3 - Click Trust` | <img src="step3.png" width="50%"> |
| `Step 4 - Click a .malloynb file` | <img src="step4.png" width="50%"> |
| `Step 5 - Press Run` | <img src="step5.png" width="50%"> |
