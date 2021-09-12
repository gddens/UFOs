# UFOs
## Overview
The purpose of this analyis is to allow the data on UFO sightings to be filtered based on various user inputs, such as date, location, shape, etc. 

## Results
On the side, under the "Filter Search" in the sidebar, there are 5 search boxes in which the user can utilize to filter based on date, city, state, country, and shape of the UFO in question:

![image](https://user-images.githubusercontent.com/86032451/133001695-ac435a78-3be6-4727-8cb0-a06d195ee745.png)

The user can then fill in one or more of the search boxes to filter by their desired criteria, hitting Enter when done in order to activate the filters. For example, by entering just "oh" in the state field and hitting enter, we were able to filter the data to only the three UFO sightings recorded in that state:

![image](https://user-images.githubusercontent.com/86032451/133001746-8a9772b0-0c40-4e64-886a-53a496767088.png)

## Summary
One drawback of this webpage is that it doesn't allow for incomplete or "wildcard" searches (i.e. adding a "%" at the end of a search string so that it pulls all results that begin with what was entered, instead of pulling just exact matches). This consideration should be looked into further as part of future development needs, and, if able to allow for wildcard searches, then additional filters should be added so that data can be filtered by the "Duration" (which has issues with formatting consistencies - i.e. minutes being spelled as both "mintues" mins - and therefore can only be effectively filtered using wilcards) and "Comments" column. 
