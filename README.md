# UFOs
#UFO_Analysis
Week 11: Working with Java Script &HTML ##
## Overview of UFO_Analysis: 
We are working with Dana who is a Data journalist who wants to investigate UFO sightings in her hometown of McMinnville, Oregon. This location is famous for its UFO sightings and holds a yearly gathering where UFO believers discuss findings and topics related to these sightings. Dana is excited about this project since she has been interested in this topic since she was a child. She has provided us with a java script file filled with data on the sightings from across the world with the location, type of sighting and descriptions. After creating a table with the UFO information, we added filters and display the data in a html format for her to present on a webpage.  While we originally only filtered by date, she was so impressed, she wants us to add additional filters for city, state, country and shape.  

#### The below pseudocode provided us an outline for the analysis ####
•	Deliverable 1: Filter UFO sightings on multiple criteria
•	Deliverable 2: A written report on the UFO analysis (README.md)

•	### Overview of SurfsUP_Analysis: ###
1.	Deliverable 1: Filter UFO sightings on multiple criteria

•	#### The list element that creates the button is removed, and there are five list elements for filtering in the index.html file ####

![alttext]( https://github.com/mbehr11/UFOs/blob/main/Resources/Filtered_list-html.PNG) 

•	#### The event listener is modified to detect changes to each filter in the app.js file ####

![alttext]( https://github.com/mbehr11/UFOs/blob/main/Resources/Filter_function.PNG)

•	#### The updateFilters() function saves the element, value, and the id of the filter that was changed ####

![alttext]( https://github.com/mbehr11/UFOs/blob/main/Resources/filtered_changes.PNG)

•	#### The filterTable() function loops through all of the filters and keeps any data that matches the filter values ####
•	![alttext](https://github.com/mbehr11/UFOs/blob/main/Resources/filtered_data_table.PNG)

•	#### The webpage filters the table correctly based on user input ####

•	![alttext](https://github.com/mbehr11/UFOs/blob/main/Resources/updated_filters_table_to_tabledata.PNG)


2.	Deliverable 2: A written report on the UFO analysis:

•	To begin with when someone goes to the website they will land on the homepage. It will contain all the information provided to us from the data.js file. It will include our header with the title “The Truth Is Out There”. Along with a sub-title “UFO Sighting: Fact or Fancy? Ufologists weigh In”. We also included an overview paragraph to the right describing the purpose of this analysis. The filtered searches are also prefilled to guide the users if they wish to filter the data. We can also go to the home screen after filtering the data by clicking in the top left corner of the webpage on “UFO Sightings” to reset the data and preform another filtered search. The home page of our website will look something like this:

![alttext](https://github.com/mbehr11/UFOs/blob/main/Resources/UFO-homepage.PNG) 

		#### Date ####
•	Now originally, we were asked to make a filter so people that visited the website could specify UFO sightings by date. As you can see by the below image, when we specified the date of 1/13/2010, three results were printed in the table. Here is our example below: 

![alttext]( https://github.com/mbehr11/UFOs/blob/main/Resources/filter_date.PNG) 

•	The filters can then be reset to the home page, by clicking in the top left-hand corner on UFO Sightings. Once we do so, we can specify if the fields under “Filter Search” to filter another date or as we did for the second part of our analysis filter by other criteria. We can now have people who visit the site filter by city, state, country, and shape. 
		

#### City ####

For the second white box, we can search by City. This is already prefilled with “rosewell”.  To filter by city, we would type in the city’s name and hit enter. For example, if the viewer wanted to look up la mesa’s reported sightings, they would type “la mesa” into the search box and hit enter. Here is an example of a search by City:

![alttext]( https://github.com/mbehr11/UFOs/blob/main/Resources/filter_city.PNG) 

#### State ####
•	With the third box a user can go more general with their table results and specify state. This box as the ones above is prefilled with “ca”.  To filter by state, we would type in the state’s initials and hit enter. For example, if the viewer wanted to look up Oregon’s reported sightings, they would type “or” into the search box and hit enter. Here is an example of a search by State:

![alttext](https://github.com/mbehr11/UFOs/blob/main/Resources/filter_state.PNG)

#### Country ####

•	For the fourth filter box, this allows a user to specify the table results by Country. This box as well is prefilled with “us”. To filter by Country someone would specify “us” and hit enter. This is a very general search as the only information provided was all from the United States. Here is an example of a search by Country:

![alttext](https://github.com/mbehr11/UFOs/blob/main/Resources/filter_country.PNG)

#### Shape ####
•	Finally, a user can also search in the fifth filter box by shape. As you can see from the data table, all the sightings included a mention of the shape of the encounter. Looking at the table there are several ways you can filter the data including by light, unknown, triangle, fireball, and circle, as well as many others. In the search bar you would type the shape you are looking for and hit enter. Here is the example of a search by Shape:  

![alttext](https://github.com/mbehr11/UFOs/blob/main/Resources/filter_shape.PNG)

## Summary ##
•	After my analysis, the one drawback of this design is that a user can only search by one set of criteria at a time. My recommendations would be to add the Search button below the filtered search and allow the criteria to filter by multiple search results. I would also continue to add to the data by removing the County Filter and add a separate table below which compares other countries to the United States. I would suggest adding additional data from other sources. I would also like to highlight McMinnville, Oregon in my search as this was the original interest for the analysis. 
## Contributing 
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
