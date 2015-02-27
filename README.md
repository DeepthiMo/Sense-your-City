Data canvas promotes public education around civic issues, using data. Data canvas created a DIY environmental sensor network, spread across 7 cities and 3 continents, where sensors are measuring air quality, dust, light, sound, temperature, and humidity. 

Data from these sensors is available for download through their website http://map.datacanvas.org/. The same link also provides a beautiful visualization tool where sensor data can be viewed interactively on the map. 

For this project *I will be using data from sensors located in San Francisco.*

##Context: Why is analyzing data from local sensors important:
Over past few decades, significant measures have been taken to diminish the effects of concentrated amounts of poisonous gases emitted by chemical factories.

However, we don’t yet completely understand how significantly we are affected by Urban air pollution both short term and long term. A lot of evidence such as [here](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC2721876/) and [here](http://www.ncbi.nlm.nih.gov/pubmed/17463411) suggest we should take a much closer look the Urban air pollution data. 

In the context of densely populated Urban residential areas, it is important to consider local data. Specifics of geography, traffic etc play an important role in the persistence and severity of the pollution. For example, in warm and sunny climates with surrounding hills, air in the upper atmosphere can become warm enough to inhibit vertical air circulation and the dispersion of air pollutants, trapping smog in the lower atmosphere. 

##Data:
Total of 12 sensors are reporting in San Francisco. Out of these 12 sensors, 3 sensors are not reliably reporting data, data from the remaining 9 sensors will be taken for this analysis. Out of the 9 sensors, data from 5 sensors will be used for training, rest for cross validation and testing.

###Predicting the effect (Dependent variables):
* Air pollution – Primary & Secondary
* Noise level

###Analyzing to understand the causes (Independent variables):
* Humidity
* Temperature
* Light
* Wind, Land sea breeze 
* Elevation
* Traffic Density
* Distance from BART

##A few questions I would like to answer by analysing data:

1. Is a city dweller better off going for a run on weekend morning than a weekday night after work?

2. Is an individual suffering from allergies better off living on higher elevation and closer to ocean ?

3. Are we more likely to live longer if we live closer to BART?

4. How does smoking two cigarattes a day compare to living in mission district? (Sensor located in Mission district is showing maximum pollution out of the sensors in SF. 

