# UFOs

## Overview
Building out a dynamic webpage using HTML, Javascript, and CSS for the UFO Sighting data set. Creating this page allows for users to more easily find information on these sightings then searching a database or just a webpage in HTML format.

## Results
This page is setup to dynamically filter the UFO Sightings data set for the end user.

### How To Use the Page
To filter the results of UFO sightings on the webpage, a user will scroll to the bottom of the page under "Filter Search."

![search](/static/images/SearchInput.PNG)

Under "Filter Search" the end users will enter dates, cities, countries, etc. of a UFO sighting to filter down. Default values show users the format of the values to be input.

When these values are entered the webpage will dynamically filter the results on the right portion of the bottom of the page. 

![search_example](/static/images/citySearch.PNG)

## Summary
A drawback to the current design of this page is that, while we can dynamically search, it is not especially user-friendly to those not familiar with the page.

### Additional Recommendations
To make this site more interactive and user-friendly we could implement the following recommendations.
 - Build out a return value for if the search is empty. Currently you just receive no results, but a better design would be to return a message of some kind instead.
 - A dropdown menu for values dependent on what has already been filled in would help to guide the user to not search for something that wouldn't return results.
 - Making a more distinguishing text format between placeholder text and user defined text would make it easier on end-users as well.