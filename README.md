# Saturday JS Project

1. Store trip destinations in an array as a global variable.

2. Create a form that has the following fields:

* Starting City
* Destination City
* Cost of Round Trip Flight
* Cost of Hotel Per Day
* Cost of Meals Per Day
* Number of Days
* Start Date

3. When form is submitted, make sure all values are filled out before adding to the trip destinations array. Hide the form after adding.

4. Display a table with the trip destinations with the following columns:

* Starting City
* Destination City
* Total Cost (to be calculated from inputed costs)
* Start Date
* Number of Days
* Edit (with button for each row)
* Delete (with button for each row)

5. The Edit button will re-open the form with the values of that row in the form. It should work like the Add functionality for validation, but update the row in the trip destinations array.

6. The Delete button should use the window.confirm dialog box to prevent deletes when clicked in error.

Extra Functionality:

The following isn't needed, but can be done to extend the functionality.

* Call the Weather API to get the forecast for the destination city and display it in the table.

* Create an email link for each row that triggers a mailto with a message to a friend detailing the trip you are considering to take.