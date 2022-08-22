# UFOs

# Overview of Project
The purpose of this project is to take the UFO sighting data from the data.js file provided and create a website that uses user input to filter the data for multiple criteria at the same time. 

# Results
The results are evident in the functionality of the webpage, which works exactly as intended

Below, you can see the filters on the webpage in their default value, not filtering the data. Notice that there are "default" search terms that cue the user to use appropriate search terms. 

![default](/static/images/default-filters.png)

Using the date filter, I have entered 1/2/2010 and the table is filtered to only show data entries for that date

![date](/static/images/date-filters.png)

Here, we are filtering by just the city, only yielding one result.

![city](/static/images/city-filters.png)

To ensure that multiple filters work simultaneously, here I have the state and shape filters filled out, and the table is successfully returning only entries that match.

![multiple](/static/images/state-shape-filters.png)

There is no filter button to click to search results, as all user inputs are activated to the filter upon the content of the input box changing. 

# Summary
Although the deployment of our intended project was successful, there is much room for improvement in future updates.

## Poor Data Quality
One of the primary drawbacks of this project is the data source itself. It is filled with mismatching data types, formatting, and continuity.
* The timeframe of dates spans less than two weeks. 
* The city value contains superflous information, such as the entry for "ingleside (canada)".
* The countries represented are 109 for "us" and 2 for "ca"
* The data for "shape" is not very useful as it contains similar items, such as "sphere", "disk", "circle" etc... There are also many entries for "unknown" 
* The duration information is not formatted consistently. There are typos as well as examples of "mins" and "minutes" used. 
* The comments section has a lot of random strings of "&#44" throughout. There are also a lot of typos and entries in all caps.  

## Recommendations for further development
1. The most important aspect of improving this webpage is to gather more data. We need to get more data from other countries AND other timeframes. If we are only using the data given here, we should consider changing the input field for "date" to be a drop down menu for ease of use and change the Country to be a checkbox for "us" and "all". 

2. Another recommendation for further development is to visualize the data. We can plot the locations of sightings on a map and use the shape of the entry as its map marker. We can also create a heatmap of frequency of sightings or create a line chart showing the different shapes frequency over time. 
