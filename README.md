# FireWatch-AdvanceWildfireWarningSystem
Call for Code Entry 2019

This advance warning system will use data analysis to monitor fire prone areas for indicators. Inputs will be data readings from Project Lali (2018 Second Place Call for Code winner) and National Weather Service Data. Take Southern California as the example. When conditions are prime for wildfires (need to research parameters), Watson will trigger drones (supplied by a third party) to fly grids and transmit images back to the cloud for visual processing. If Watson detects a possible smoke column (80 percent chance), Watson will drop a pin on that location in Google Maps and push an alert notification with a link to google maps. 

Here is a description of project Lali Wildfire:

Project Lali Wildfire (2nd place winner) had stationary sensors that proposed measuring temperature / soil moisture readings over LORAnet to help predict / alert wildfire warnings (drones were not part of that solution)

See application diagram in assets folder.

Here are some API links for the data analysis model.

https://earthdata.nasa.gov/earth-observation-data/near-real-time/firms/active-fire-data

https://disasters.nasa.gov/fires - information about fire detection using sattelite feeds

https://lance.modaps.eosdis.nasa.gov/ - 24 hour image feeds, could be used to monitor for smoke columns or fire indicators, also there are components for moisture

