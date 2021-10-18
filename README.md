# Module 11 Challenge - UFOs - JavaScript

## Overview

The purpose of this project is to update and republish a previously created webpage.

Both versions of the webpage display an HTML Table containing summary information
about UFO Sightings.

Version 1.0 of the webpage included a dynamic HTML Table with a date filter entry box
and a `Filter Table` action button that filtered and refreshed the table on `<Click>`.

Version 2.0 specifications indicated that the webpage should be updated to include
additional filters for `City`, `State`, `Country`, and `Shape`.
The HTML Table should be filtered and refreshed whenever new values are entered
into any of these filter entry boxes. For a cleaner interface, the original
`Filter Table` action button was removed.

### Deliverables

1. Updated Version 2.0 of webpage which filters UFO Sightings on multiple criteria.
2. This written report (README.md)

## Results

With the new Version 2.0 of the webpage working as requested, a user now has much greater flexibility to perform their own explorations of the provided data, at will.

The filter entry boxes are designed to be flexible and intuitive. If no user-specified filters are entered, the entire table of data is shown. If additional filtering is desired,
any combination of the filter boxes can be used in concert to show only observations of interest. The HTML Table is refreshed on `<Enter>` or `<Tab>`. To re-display the original table, clear the text in all the filter boxes, or refresh the page. Figures 1 & 2 below gives an example of what this looks like in practice.

**Figure 1: Webpage with No Filters Applied**

![Figure 1](/Resources/Figure_01.png "Figure 1")

**Figure 2: Webpage with Filter Applied**

![Figure 2](/Resources/Figure_02.png "Figure 2")

## Summary

One drawback of the current version of the webpage, is there is no export functionality. If a user finds some results they find particularly interesting and would like to investigate further at a later time, they must either record it manually, or resort to copying the HTML Table directly. Some more tech-savvy users may have no problem performing this task, but it may be less obvious to someone less familiar. A nice feature of the webpage would be to export the current view to a CSV and allow the user to save it locally to their computer.

Another drawback is in the quality of the original data itself. As noted in the ***Data Quality*** Section above, the last three Fields are free text with loosely enforced standards of data consistency. In Version 2.0 of the webpage, these fields are not incorporated into the Filter Search; however, if a future version of the webpage incorporated any or all of these fields into the search capability, there would have to be much more consistent formatting of records in order to achieve consistent and accurate search results. Alternatively, the parsing of these records would have to include more sophisticated pattern-matching on filter rather than simple equivalency.
