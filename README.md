### **Air quality vs Temperature**

---------

**Author:**
Sonia Cobo Pacios
02/06/2021
The Bridge - The Bridge Digital Talent

---------



---------

**Project description:**

---------

This project studies the relationship between air quality and temperature. It is well-known that the increase in average temperatures due to climate change has a negative impact to air quality. 

This project studies the relationship between air quality and temperature. It is well-known that the increase in average temperature due to climate change has a negative impact to air quality.

In the past few years it has been discovered that these two concepts are highly related, more than previously assumed. However,their relationship is not due to greenhouses gases, they are mainly linked through temperature changes.

The project's aim is to prove this relationship, particularly when comparing temperature to ozone concentration, as the hypothesis is that ozone is the main pollutant affecting air quality due to climate change.

To prove this hypothesis the project considers the behaviour of several harmful pollutant, such as ozone (O3), sulphur dioxide (SO2), nitrogen dioxide (NO2), carbon monoxide (CO) and Particles Matter 10 (PM10) over the past six years in relation to temperature changes


---------

**Project structure:**

---------

First data about the differerent pollutants were imported as csv, cleaned, organised an initial observations were drawn.

Then temperature data was downloaded using Selenium (**Warning** there is a cell in the code that if executed it will download this data from internet again. This is also noted in the code).

Once both data was cleaned they were compared into a single dataframe. To help understanding their relationship different graphs were used. 

---------

**Project conclusion:**

---------

The studied data, and in particularly the correlation graph cannot show any relationship between temperature values and air quality.

As there are scientific proofs confirming the increase in temperature impacts air quality negatively this EDA project concludes that the second answer is indeed the correct. The data sample wasn't large enough to obtain a reliable result, particularly when consdiering temperature changes.

While it was determined that the dataset isn't adequate to draw any conclusions we cannot either confirm which pollutant is affected the most by temperature increases.

From the study data we can conclude that some pollutant such as SO2 and NO2 have been decreased over the years, but it is not possible to confirm if they will keep this trend and if it is enough to provide any release to climate change. On the other side, CO and PM10 keep increasing due to human activities over the years regardless temperature values.

Though this project couldn't confirm the initial hypothesis (the increase of temperature affects negatively air quality) it was interesting to understand that some harmful pollutants are indeed being decreased, and pollution levels are kept prery average along the whole country. A further study can be done to understand the benefits of this reduction and what measures can be implemented to improve this trend.

Regardless temperature, more data is required to obtain a trend. Once this additional data is obtain it can also be possible to create a predictive model to foresee future temperatures and its consequences for air quality and climate change.