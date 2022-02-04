# Project Overivew
The purpose of this project was to create a user-friendly webpage that allows users to easily filter through UFO sighting data. 
Due to the large volume of data available for UFO sightings, it can be difficult to view in aggreggate. The webpage was designed with a filter that allows users to fitler based on the following criteria:
- Date
- City
- State
- Country
- Shape

The goal was to assist users in finding the UFO sighting data they are looking for!

# Results
## Main Page
When a user first opens the site, they will be taken to the main page that will display all of the UFO sighting data. 
<br>
![Main Page](/static/images/mainpager.png)
## Filtering
<br>
On the left-hand side of the page are for filters that a user can use to filter the data. The user can filter by: Date, City, State, Country, Shape

![Filters](/static/images/filters.png)

The user can enter data into any of the filters then hit "Enter". If there are results found for the criteria entered, the data table will filter based on the matching results. 

![Filtered Data](/static/images/filtereddata.png)

The user's selection is captured on the Console.

![Console](/static/images/console.png)

The user can filter based on multiple criteria at the same time to further limit results.

![Console](/static/images/multiple.png)

This filtering process is the same for each of the five filtering parameter options. 

To view all of the table data again, the user simply has to clear out the filter box(es) then hit "Enter".


# Summary

## Drawback(s)
One drawback to the current design is that filtering requires users to have a general idea of the values they can filter on. Users may not be aware of all options. 
For example, the "Shape" column includes a "Cigar" value. A general user may not be aware that this is a UFO shape that can be filtered on.

## Recommendation(s)
Below are two recommendations to enhance the webpage:

 1. Add a dropdown option to the fitler feature where users can either (1) type in their own text or (2) use the dropdown to select based on values present in the data. 
 2. Allow for date filtering by month and year. The current date filter requires a specific date. User may want to search based on month, year or month/year.