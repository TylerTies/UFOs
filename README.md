# UFOs

## Overview
This project's goal was to create a webpage that would allow users to interact with filters and view desired UFO sighting data. The project html to build a website and javascript to build a table that is able to dynamically change with webpage input from the user.

## Results
The webpage's usefulness centers around the filter functionality to sift through the UFO sightings data. The following steps will walk through this functionality.

1. The filters are located in the lower left corner of the webpage. The fields are prefilled with data in the correct format but not actively filtering. This data assists users in showing them how to format the queries.
![Filters](/images/filters.png)

2. The next step is to start entering your filter criteria.  The filters recognize when a change is made and automatically apply the filter.  Simply clicking out of the field or hitting enter will update the table. The screenshot below shows an example of a query using the date and country criteria. The text is darker in these fields than the example data in the other filters.
![Search](/images/search.png)

3. The filtering can be removed by deleting each individual filter entry as desired.  Another option is to click the words "UFO Sightings" at the very top left of the page to reset to a clean page. A screenshot of this location is below.
![Reset](/images/reset.png)

## Summary

### Drawback
This webpage is useful for the dataset it contains.  The webpage is limited in that the data source is a static source.  As time progresses, this data will become more out of data and less desirable.


### Recommendations
A few small upgrades could make strides in ease of use.
1. The first upgrade would be to implement a change that works around the case requirement on the fields.  The fields are currently case sensitive and users could easily miss data.  Fields such as state are typically presented in uppercase and would cause issues if users don't realize this requirement.  Even a note on the page explaining this requirement would be helpful.

2. Another potential upgrade to help make it easier on users would be a button near the filters to reset all filters.  This functionality is currently at the top of the page far away from the filters and it's not apparent that the functionality exists.  A button that is clearly seen and titled would be a helpful addition.