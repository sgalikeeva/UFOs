# UFOs: Javascript and Webpage
## Overview of Project
The purpose of this project was to create a webpage and dynamic table that allows users to filter the data of UFO sightings for multiple criteria at the same time. The criteria a user can filter the data on are: date, city, state, country, and shape. 
## Results
Once the webpage is created, it is simple to walk a user through how to use the filter search. The webpage has five different search criteria a user can choose to filter the data and all the data is listed in a table below the navigation bar, the jumbotron and the article.
![This is an image](.png) 
The user can choose to filter by one or more filters. If no data matches the filter or filters chosen, the table will be blank with no row of data shown. When a filter is input into the provided text boxes, the data will filter automatically once the user either clicks outside the text box or presses tab on their keyboard. The following screenshots show a user filtering the data one filter at a time. The user first chooses to filter by state, California. The user types “ca” into the text box associated with “Enter a State.”
![This is an image](.png) 
The user then chooses to filter by city, El Cajon, in addition to filtering by the state of California. The user types “el cajon” into the text box associated with “Enter a City.”
![This is an image](.png) 
The user then chooses to filter by shape of the UFO sighting, a circle, in addition to filtering by the state of California and the city of El Cajon. The user types “circle” into the text box associated with “Enter a Shape.”
![This is an image](.png) 
The user can filter even further by date if desired. If the user made a mistake with filtering, they can click the “UFO Sightings” navigation bar at the top to reset the whole page. 
## Summary
The webpage performs well as it is but there are some drawbacks and some suggestions for further development. A major drawback is that the webpage does not tell the user in detail what the data covers, i.e., unless a user scrolls through the entire webpage and looks at all the data, there is no way to know what options the user has for the search criteria.
My recommendations are:
1)	Inform the user the span of the data in detail with either a) a description of the available data above the filter search and table or b) have drop down menus in the filter search that list available filters.
2)	The filters should be coded to also ignore the case that the user types in. Using the example above, if the user typed in “CA” rather than “ca,” the table would be empty because the filters are currently coded to match the id exactly.  

Ideally the data would also be cleaned up before having this webpage go live to correct misspellings, spacing and add capitalization to the cities, states and countries. 

