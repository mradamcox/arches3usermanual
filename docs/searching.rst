###########################
Using the SEARCH screen
###########################

Keyword Search
===============
You can start by entering a term in the search bar. Arches-HIP will then suggest terms that can help you specify what you are looking for. These include specific resources from your database, or terms from the reference data (controlled vocabularies) in your organization’s installation of Arches-HIP. You can apply several terms in combination in order to further refine your search results. To remove any keyword, simply click on the × to the right of the label. Search results will be updated in real time as you create and edit a search query in that way.

In addition to keywords, you may also apply spatial and temporal filters to your database.

Location Filter
================

Clicking the Location Filter button will load a map view of your database. The map will show all records in your database that have a precise location attached to them. Map Tools, located on the top right corner of the map, will allow you to limit your search results to a specific area of the map in several different ways:

* Limit search results to map extent: Selecting this option (toggle on/off) will limit the search results to only those records in the area visible in the map. Panning and zooming in or out will allow you to further limit or expand the search results in real time.
* Draw Polygon to Filter Map: This option will allow you to draw a polygon on the map in order to limit the search results to only those records that lie within its boundaries. Clicking once on the map will set a new vertex for your polygon. Clicking and dragging will allow you to pan on the map. You can complete your polygon by clicking on the starting point, or by double clicking anywhere on the map to define the last side of the polygon. This option can be combined with the Buffer option (see below) to set a buffer area around your polygon.
* Draw Line to Filter Map: This option will allow you to draw a line on the map in order to limit the search results to those records that lie within a certain distance from that line. You may specify the distance in the default unit of measurement in the box marked “Buffer.” The outlines of the buffer area will be indicated on the map. 
* Draw Point to Filter Map: This option will allow you to mark a point on the map in order to limit the search results to those records that lie within a certain distance from that point. You may specify the distance in the default unit of measurement in the box marked “Buffer.” The outlines of the buffer area will be indicated on the map.
* Buffer: Use this box to specify the distance required to mark a buffer area around a point, line, or polygon on the map.

As soon as you apply a location filter, a label marked “Map Filter Enabled” will appear in the search bar.

You can reverse the location filter by clicking once on this label. This will allow you to limit the search results to those lying in the area beyond the map extent or outside of a polygon or a buffer area.

To reset any location filter, click on the × to the right of the label.

Time Filter
============

Clicking the Time Filter button will load a set of controls that can be used to apply a temporal filter to your database.

A slider marked Range of Years will allow you to define upper and lower time limits. Your search results will be limited to only those records that contain a date that falls within this range.

Under Start/End Dates you can apply a more targeted time filter by specifying the relationship (before, on, or after) of a specific entry in the record(s) that you are searching for (for example, construction date) to a specific date in the calendar. To do so, select the type of date and a qualifier from the drop-down menus and enter or select a date. Click the Add button to add this time filter to your query.

In this way you can create a combination of temporal relationships. To remove a temporal filter, click on the × in the list of temporal filters that have been applied to your query.

As soon as you apply a time filter, a label marked “Time Filter Enabled” will appear in the search bar.

 

You can reverse the time filter by clicking once on this label. This will allow you to limit the search results to those outside a defined range of dates. **YA: Actually, it is unclear to me how exactly this option works when it comes to a combination of Start/End Dates, e.g. what would “built after X AND demolished before Y” turn to? “not built after X OR not demolished before Y” seems to be logical (and maybe that’s how it works and you should just apply it with caution?)**

To reset any location filter, click on the  to the right of the label.

Viewing Search Results
======================

As you apply a combination of keywords and filters, search results will be updated in real time. As you add new criteria, you will be able to see fewer and fewer records, as Arches filters out those search results that do not meet your search terms. Criteria are applied cumulatively, and can help you construct powerful search queries. Eventually, you may discover that some of the criteria that you have applied are too limiting, or are simply no longer appropriate for returning the results that you are after. Simply remove those criteria from search bar, by clicking on the × to the right of the corresponding label and the results will be instantly updated.

Click on the name of a record among the search results to view a report with more information for that resource. If you want, you can choose to open the report in a new browser tab. The content and format of the reports can be customized by your System Administrator.

Alternatively, you can view a graph of related resources, and access the records corresponding to them, by clicking on Related Resources:
INSERT IMAGE
Clicking on Map will display the selected resource on a map:
INSERT IMAGE