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

Use the following classes to stylize the fields:

* form-group for the div around each input and it's label
* form-control for the input field

Use the following types for the input fields: text, number, date

3. When form is submitted, make sure all values are filled out before adding to the trip destinations array. Hide the form after adding.

Requirements:

* Starting City (Must have a value)
* Destination City (Must have a value)
* Cost of Round Trip Flight (Must be a positive decimal number)
* Cost of Hotel Per Day (Must be a positive decimal number)
* Cost of Meals Per Day (Must be a positive decimal number)
* Number of Days (Must be a positive integer number)
* Start Date (Date must be after today and filled in)

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

* Convert your code to have a Destinations class that accepts a Destination class instance.

* Convert your code to wrap the Table manipulation logic into a Table class that abstracts the table away.

* Convert your code to wrap the Form manipulation logic into a Form class that abstracts the form away.