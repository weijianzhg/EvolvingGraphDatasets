# Highways Agency network journey time and traffic flow data

* DATA.GOV.UK

* Description: 

This data series provides average journey time, speed and traffic flow
information for 15-minute periods since April 2009 on all morotways
and 'A' roads managed by the Highways Agency, known as the Strategic
Road Network, in England.

Journey times and speeds are estimated using a combination of sources,
including Automatic Number Plate Recognition (ANPR) cameras,
in-vehicle Global Positioning Systems (GPS) and inductive loops built
into the road surface.

Please note that journey times are derived from real vehicle
observations and imputed using adjacent time periods or the same time
period on different days. Further information is available in 'Field
Descriptions' at the bottom of this page.

* Data fields

	- `i`: road junction name
	- `j`: road junction name
	- `Date`: date of travel
	- `LinkRef`: a unique link id representing a junction to junction 
      link on the road network.
	- `TimePeriod`: one of 96, 15 minute intervals in the day.
	- `AverageJT`: the average journey time to travel across the `LinkRef`.
	- `AverageSpeed`: the average speed (in km/h) of vehicles entering
      the junction to junction link within a given 15-minute time period.
	- `DataQuality`: Indicator showing the quality of the journey time
      data for the link and time period. 1 indicates the highest
      quality data and 5 the lowest.
	- `LinkLength`: the length of the link (km).
	- `Flow`: an average of the observed flow for the link, time period.
