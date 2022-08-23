# UFO Sightings Website

## Overview:
### Background:
Dana is a data journalist who is excited about the chance to write about her small hometown in Oregon and the topic of UFO sightings. She has a Javascript file of sightings and wants to display them and her article on a webpage.

### Purpose:
An initial website with her article and a table of UFO sightings has been created and is filterable by sighting date. However, the ability to simultaneously filter over multiple criteria needs to be added to enable a better user experience for visitors of her webpage.

## Results:
- The new website can be found at: https://bfox87.github.io/UFOs/
- On the left-hand side of the webpage, users can filter the UFO sightings with the use of five different search criteria boxes: 1.) Date 2.) City 3.) State 4.) Country 5.) Shape.
- Users just need to type in the value they wish to search by (i.e. "san diego" for city or "triangle" for UFO shape) and then hit enter or click out of the box for the table to refresh with the narrowed results.

- In the screenshot below, the user is looking for sightings in San Diego on New Years Day 2010 (1/1/2010). The lighter grey values in the unused state, country, and shape fields are just placeholder values to give the user an idea on how to enter in the data.
![Website_Filters](https://github.com/bfox87/UFOs/blob/main/Screenshots/Website_Filters.PNG)

- Users can narrow using anywhere from just one criteria/box all the way up to all five.
- Just backspace or delete all the filter criteria to bring back the original table of all sightings.

## Summary:
One clear drawback of this page is the requirement of exact text matches for the search filters. For example, a user looking for sightings in the city of "el cajon" might not know the exact spelling and want to just type "el c" and then hit enter. This unfortunately will not bring up any results as shown in the screenshot below.
![el_c](https://github.com/bfox87/UFOs/blob/main/Screenshots/el_c.PNG)

Only when they type in exactly "el cajon" do they then find the results they are looking for.
![el_cajon](https://github.com/bfox87/UFOs/blob/main/Screenshots/el_cajon.PNG)

#### Additional Recommendations for Further Development:
Make dropdown searches for the fields instead of requiring text entry. A user will select the shape filter, for example, and see the available choices and pick one instead of needing to type "triangle" or "circle."  

Additionally, it would be helpful to enable the sorting of the sightings table by clicking on the header of the column you want to sort by. The table is currently sorted by date because the JSON data file came this way. However, sorting by other fields might be more helpful and quicker for users than going over to the filters and typing something in.