####
## Instructions to update this web application on a yearly basis
## By: Gerardo Armendariz
####

Workflow to modify the SR Checkdams Storymap:
1. Upload new year images to the \resources\images folder on MUDFLOW server
2. Add 3 new fields (Date, Note, and Pic) for the new year to the Upstream and Downstream Perspective layers on ArcGIS Online
3. main.js file updates (under app\js)
	a. Update the new year Pic and Note field variable (lines 24 and 25). Left panel thumbnails are loaded for the last available year.
	b. Modify the JavaScript code in the main.js file to add new year pictures and notes.  Search for two instances of “SRCHECKDAMS Update - new images”, one for the regular browser view and one for mobile view.
4. Upload the modified main.js
