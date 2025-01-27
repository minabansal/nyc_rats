# NYC Rat Population Analysis
 Project1_Group13: 
 Mina Bansal, Roger Lefort, Hansen Xu, Chi-Kuang Chen

![rats](https://github.com/tiroger/nyc_rats/blob/master/rats.png)

Rats in New York City are prevalent, as in many densely populated areas. For a long time, 
the exact number of rats in New York City was unknown, and a common urban legend was that 
there were up to four times as many rats as people. In 2014, however, scientists more 
accurately measured the entire city's rat population to be approximately only 25% of the 
number of humans; i.e., there were approximately 2 million rats to New York's 8.4 million 
people at the time of the study.[1](https://rss.onlinelibrary.wiley.com/doi/pdf/10.1111/j.1740-9713.2014.00764.x)

## Content:
New York City rodent complaints can be made online, or by dialing 3-1-1, and the New York City guide Preventing Rats on Your Property discusses how the New York City Health Department inspects private and public properties for rats. Property owners that fail inspections receive a Commissioner's Order and have five days to correct the problem. If after five days the property fails a second inspection, the owner receives a Notice of Violation and can be fined. The property owner is billed for any clean-up or extermination carried out by the Health Department.

Data is from 2010-Sept 16th, 2017 and includes date, location (lat/lon), type of structure, borough, and community board.

Acknowledgements:
Data was produced by the City of New York via their 311 portal.

---

### Research Question/Hypothesis

Hypothesis - Climate change will impact rat population

Questions
* Is there a correlation between climate and rat sightings (temperature, humidity, pressure, etc.)?
* Are there seasonal differences in rat sightings?
* Where are sightings more likely to occur? In residential areas or public areas?

### Materials/Methods

Data Sources
* Rat sightings: NYC Open Data
* NYC weather: NOAA
* Shape files: NYC Open Data

Packages Used
* Pandas
* Modin
* Numpy 
* Matplotlib
* Seaborn
* Geopandas
* Datetime


### Conclusion

* There is an increase in the NYC rat population over time
* Rat sightings are more likely to occur in residential areas like Brooklyn (specifically Bushwick and Bed-Stuy)
* There is no correlation between population and rat sightings
* As temperatures increase, so do rat sightings



