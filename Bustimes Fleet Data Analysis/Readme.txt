

======= ==========
General Info/Usage
======= ==========

These sheets show a breakdown and basic analysis of the Fleet data held on bustimes.org. Specifically:

 > Total vehicles in the fleet;
 > Conflicting registration numbers and fleet numbers (was mainly for me to make sure I was only counting each vehicle once);
 > Proportion of the fleet with a route history available, as a percent out of the total fleet;
 > Info on vehicle types:
   >> A list of all the unique vehicle types in the fleet;
   >> How many vehicles of each type are in the fleet;
   >> A mini graphic depicting the proportion of the fleet which is made up of each vehicle type.
 > Info on vehicle liveries:
   >> A list of all the unique liveries in the fleet;
   >> How many vehicles with each livery are in the fleet;
   >> A mini graphic depicting the proportion of the fleet which is made up of each livery.
 > Info on routes:
   >> A list of all the routes which have tracking history;
   >> How many vehicles have tracking history for each route;
   >> A mini graphic depicting the proportion of vehicles which have tracking history for each route, out of all vehicles with tracking history.
 > Info on vehicle types by route:
   >> A list of the most common vehicle type used on each route.

** As always with bustimes.org, take the data with a pinch of salt and don't take it as gospel. The data in the spreadsheet is taken directly from bustimes.org with minimal pre- and post-processing. Any errors in the data on bustimes.org will also be present in my spreadsheet. **




===== ======
Known issues
===== ======

** As always with bustimes.org, take the data with a pinch of salt and don't take it as gospel. The data in the spreadsheet is taken directly from bustimes.org with minimal pre- and post-processing. Any errors in the data on bustimes.org will also be present in my spreadsheet. **

A timer has been included to show how old the displayed data is. The box containing the counter ("x days ago ...") updates only when you first open the sheet and is reset only when you refresh the data. The data can be refreshed easily by pressing the button "Refresh Data" located in cell A1 (top left).

The data should be very quick to process with the exception of the final list (Vehicle Types by Route), this column may take slightly longer to load.

There is a bug in the formula to load all the unique routes, which sometimes causes the sheet to omit routes. I think it is something to do with the order that each route is loaded and added to the list but I'm not sure what is causing it.


The column headers in the raw data are appearing in each list. This should just be a case of me removing that row from the raw data but I'm lazy and haven't done it yet I didn't want to mess with the data and risk breaking the whole sheet.


Bustimes.org sometimes retains route data for vehicles after they leave service, until they start a different route; this means that some vehicles might be recorded as being on a route when in reality they are not. This may be fixable in the future.


I would like to have a "confidence" column next to the Routes by Vehicles list to show the quality of the data shown (at the moment a vehicle type will appear as a "top vehicle" if anything greater than 50% of the vehicles on that route are the given type, but there's nothing to distinguish between a route where 51% of the vehicles are the shown type and a route where 99% of the vehicles are the given type).


