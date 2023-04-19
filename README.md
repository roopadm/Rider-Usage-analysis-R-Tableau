<h1 align="center">
  <a href="https://www.kaggle.com/code/roopamoorthy/google-data-analytics-capstone-project-cyclistic" target="_blank">
    <img src="https://github.com/roopadm/Google-Capstone-Project-R-Tableau-Cyclistic/blob/main/images/1650821003822-removebg-preview.png" alt="Cyclistic" width="60" height="50" style="vertical-align: middle;"/>
  </a>
  <strong>Data-Driven Marketing Strategies for Rider Conversion : Rider Usage Analysis with R and Tableau</strong>
  <a href="https://public.tableau.com/app/profile/roopa.d.moorthy/viz/GoogleDataAnalyticsCapstoneProjectRiderUsageAnalysis/PopularStationsAnalysis?publish=yes" target="_blank">
    <img src="https://github.com/roopadm/Google-Capstone-Project-R-Tableau-Cyclistic/blob/main/images/tableau_logo-removebg-preview.png" alt="Tableau" width="50" height="50" style="vertical-align: middle;"/>
  </a>
</h1>

Join me on my data-driven journey through the data of Cyclistic, a bike-share company in Chicago, we will explore how annual members and casual riders use their bikes differently. Utilize R for data cleaning and manipulation, and Tableau for data visualization, to seek answers to three key questions:

- How do annual members and casual riders use Cyclistic bikes differently?
- Why would casual riders buy Cyclistic annual memberships?
- And how can Cyclistic use digital media to influence casual riders to become members?

## Goal

To uncover insights into rider usage patterns, identify the factors that drive casual riders to become members, and develop marketing strategies that will make it happen.

<b>For fully narative version of this project : <a href="https://www.kaggle.com/code/roopamoorthy/google-data-analytics-capstone-project-cyclistic">check out my Kaggle notebook.</a></b>

<p align="center"> <a href="https://www.kaggle.com/code/roopamoorthy/google-data-analytics-capstone-project-cyclistic" target="_blank"> <img src="https://github.com/roopadm/Google-Capstone-Project-R-Tableau-Cyclistic/blob/main/images/Rider%20Usage%20Analysis%20Google%20Data%20Analytics%20Capstone%20Project.png" alt="Projectimage" width="80%" height="10%"/> </a> </p>

## Dataset 

Public data of Cyclistic’s historical trip data is available on <a href="http://divvy-tripdata.s3.amazonaws.com/index.html">Motivate International Inc. </a> under the  <a href="https://ride.divvybikes.com/data-license-agreement"> license. </a>

I have used 12 months of data , April 2020 to March 2021. To get a brief look used MS Excel and noticed each month's data is recorded in separate CSV files with fields such as ride id, rideable type, start and end time, start and end station, latitude, and longitude of the start and end stations.

####

**Prerequisite:** <code>[R](https://www.w3schools.com/r/)</code> :hourglass: , <code>[Data analysis with R](https://www.coursera.org/learn/data-analysis-r)</code> 📑, <code>[Tableau](https://www.tutorialspoint.com/tableau/index.htm)</code> :hourglass: & <code>[Statistics and probability](https://www.khanacademy.org/math/statistics-probability)</code> 🗂️


## Technologies used ⚙️

* <a href="https://www.kaggle.com/code/roopamoorthy/google-data-analytics-capstone-project-cyclistic">R</a> <a href="https://www.kaggle.com/code/roopamoorthy/google-data-analytics-capstone-project-cyclistic" target="_blank"> <img src="https://github.com/roopadm/Google-Capstone-Project-R-Tableau-Cyclistic/blob/main/images/r.png" alt="R" width="30" height="30"/> </a>

* <a href="https://public.tableau.com/app/profile/roopa.d.moorthy/viz/GoogleDataAnalyticsCapstoneProjectRiderUsageAnalysis/PopularStationsAnalysis?publish=yes">Tableau</a><a href="https://public.tableau.com/app/profile/roopa.d.moorthy/viz/GoogleDataAnalyticsCapstoneProjectRiderUsageAnalysis/PopularStationsAnalysis?publish=yes" target="_blank" rel="noreferrer"> <img src="https://github.com/roopadm/Google-Capstone-Project-R-Tableau-Cyclistic/blob/main/images/tableau_logo-removebg-preview.png" alt="JupyterNotebook" width="25" height="25"/> </a>

##### R Libraries : 
* <a href="https://www.tidyverse.org/">Tidyverse</a><a href="https://www.tidyverse.org/" target="_blank" rel="noreferrer"> <img src="https://github.com/roopadm/Google-Capstone-Project-R-Tableau-Cyclistic/blob/main/images/Tidyverse.png" alt="tidyverse" width="30" height="30"/> </a> |  <a href="https://cran.r-project.org/web/packages/skimr/vignettes/skimr.html">Skimr</a><a href="https://cran.r-project.org/web/packages/skimr/vignettes/skimr.html" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/mrankitgupta/mrankitgupta/2a582d085b324cff4917325112229027309ecae3/Numpy-logo.svg" alt="skimr" width="25" height="20"/> </a> |  <a href="https://dplyr.tidyverse.org/">dplyr</a><a href="https://dplyr.tidyverse.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/mrankitgupta/mrankitgupta/1331979c3208a15be2c2a6177ffc38ced3d6b434/Matplotlib_icon.svg" alt="dpylr" width="25" height="20"/> </a> |  <a href="https://seaborn.pydata.org">Seaborn</a><a href="https://seaborn.pydata.org" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="Seaborn" width="25" height="20"/> </a> |  <a href="https://realpython.com/python-folium-web-maps-from-data/#:~:text=Python's%20Folium%20library%20gives%20you,can%20share%20as%20a%20website.">Folium</a><a href="https://realpython.com/python-folium-web-maps-from-data/#:~:text=Python's%20Folium%20library%20gives%20you,can%20share%20as%20a%20website." target="_blank" rel="noreferrer"> <img src="https://github.com/roopadm/AnalyzingDevSurvey-Data-analysis-using-Python/blob/main/Images/folium%20logo.png" alt="Folium" width="20" height="20"/> </a>

## To answer the key business questions : 🔍

Six steps of the data analysis process


1. Ask

2. prepare

3. process

4. analyze

5. share

6. act 

Also,certain roadmap is followed :

* Code, if required.
* Guiding questions and their answers
* Key tasks and deliverables as a checklist.
