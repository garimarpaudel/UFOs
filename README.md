# UFOs

## 1. Overview of Project
#### The purpose of this project is to allow users to filter for UFO sightings with multiple criteria at the same time.The request from a client was to display a table organizing UFO data stored as a JavaScript array. The client wanted the ability to filter by multiple criteria creating a dynamic website.  The table was created using JavaScript, while HTML/CSS and Bootstrap were used to modify the aesthetics of the website. 


## 2. Summary
### Drawback:
The user must know specific dates, cities, or shapes to search.  The filters require correct lower-case spellings and cannot include spaces at the end.  The city that was used, for example, could not be typed as "elcajon", “el cajon_”, or "El Cajon".  The only acceptable input would be "el cajon".

### Recommendations: 
1. The next addition to the filters should be to add a trim function to catch spaces at the end of words as well as allow for upper and lower cases.

2. A filter on a date range might be preferable than a singular date.  Typing 1/2010 did not bring up all the dates from January as hoped.  Perhaps, the UFO Sightings occur more frequently in a specific month instead of a specific day within the month.  It is recommended to add in a filter function to include a date range as the filter to aid in the investigation of UFO Sightings. 
