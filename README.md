## [J^2 Ridr: Sounds like Tinder, but nothing like Tinder](Final_markdown.html)

---

**MUSA507: Public Policy Analysis**

**Authors:** Johnathan Clementi & Jonathon Sun

[Presentation Link](https://www.youtube.com/watch?v=fKvH-xgyHvM)

---

### Introduction

What if we could tell you that your train was going to be 6 minutes late for your Tuesday morning commute, ten days before it was time to leave rather than ten minutes? Would that knowledge be valuable to you? 

Although train delays may seem like minor annoyances in the daily life of a commuter, there are real economic costs to train tardiness. The city of New York Office of the Controller found that major delays (5-minute delays) annually cost the city \$170.2 million dollars (Stringer, 2017). While some systems are truer to their timetables, systems like Amtrak are notoriously late (Lazo, 2019). In the case of Amtrak, a primary driver of lateness is congestion as it does not own most of the right of way it operates on. In a 2019 report detailing its on-time-performance (OTP) woes, Amtrak estimated approximately \$171 million in losses during 2018 due to 27% of their trains being late (Amtrak, 2019).

OTP issues are not exclusive to Amtrak in the Northeast. Regional operators such as the NJ Transit have a history of delays (McGeehan, 2018). For the 90,000 daily riders of NJ transit, these delays mean lost time, revenue, and sanity. In this study, we build and test a linear regression to predict delay length for trains based on a variety of predictors. The hope is that this model can be utilized by agencies, researchers, and the average commuter.

For agencies and researchers, the visualizations and algorithm can serve to identify bottlenecks in the system. Whether that be the stations that are coming from or arriving to or if there is a particular day of the week that is most late. This analysis will lead to the identification of lateness so that it can be addressed. For the average commuter, this analysis can provide a way to determine average lateness and given a set of variables; how late will the train be?

### Data

[Kaggle Data on NJTransit & Amtrak](https://www.kaggle.com/pranavbadami/nj-transit-amtrak-nec-performance?select=2018_11.csv)

[NJtransit Lines](https://njogis-newjersey.opendata.arcgis.com/datasets/NJTRANSIT::rail-lines-of-nj-transit/explore?location=40.432892%2C-74.532212%2C8.95) 

[NJtransit Stations](https://njogis-newjersey.opendata.arcgis.com/datasets/NJTRANSIT::rail-stations-of-nj-transit/explore)

[Weather Data](https://cran.r-project.org/web/packages/riem/vignettes/riem_package.html)



![alt text](LINE_NAME.gif)

---

### Notes
Because of the constraint on time and lack of computing resources, our final project was unable to include all the data in the dataset and uses the first half of 2020 to predcit the second half of 2020


