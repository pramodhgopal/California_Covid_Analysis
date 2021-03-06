# Data Analysis of Covid 19 in the State of California
A look into the number of cases and deaths in the state of California caused by Covid-19

The rmd document contains a brief analysis of the data from the COVID-19 data set from the Johns Hopkins github site. The intention is to provide an exploratory data analysis in a reproducible manner to ensure the validity of said analysis. In this document we shall import the data and try to analyse the number of cases and deaths in the state of California. Finally we will try to model the deaths by cases and see if they are linearly related.

Please use RStudio to knit the rmd document to reproduce the report.

## Data Source

CSV files - https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/



## Methods

I used RStudio to read in the data from the CSV, cleaned it and plotted the graphs using Tideyverse's ggplot. Tried establishing a relationship between 2 new columns: cases_per_thou and deaths_per_thou and tried to build a model to predict a linear relationship between them. Detailed analysis of the graphs and model can be found in the RMD document.



## Findings


Initial graph of cases and deaths in the state of California through the last year.

![image](https://user-images.githubusercontent.com/20074613/129068911-a0d14f95-d9c5-47fe-8c96-e436ca84c475.png)



Graph of cases and deaths in the state of California through the last year now accounted for lag. This graph accounts for lag (drop in cases/deaths followed by spikes in both).

![image](https://user-images.githubusercontent.com/20074613/129069156-19c327de-6609-4c33-ae3b-0abfdc2eaddb.png)






Model prediction for deaths per thousand by cases by thousand for all the counties in California

![image](https://user-images.githubusercontent.com/20074613/129069612-6a4907c9-dc4e-4797-94ca-cded5e1f53dd.png)



Please view the Rmd for conclusion analysis.  




