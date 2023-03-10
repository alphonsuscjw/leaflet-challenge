# leaflet-challenge

The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. This challenge visualises USGS earthquake data that will allow the USGS to better educate the public and other government organisations (and hopefully secure more funding) on issues facing our planet.

First, I imported using the d3 library the json data for all earthquakes from the past 7 days. Next, I created earthquake markers, the radius of each being proportional to the magnitude and the colour darkness of each being proportional to the depth. I then created a map with layer control. Lastly, I set up a legend for the different colours of the earthquake markers. The result is a map showing all earthquakes that happened in the past 7 days with information on the magnitude, depth, place and time.
