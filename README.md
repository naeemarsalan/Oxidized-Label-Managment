# Oxidized-Label-Managment

Changes made to the Oxidized Project, add 3 routes

## /Location - To Read Config and format Groups into Table
Parses the YAML oxidized config file and creates a 2D Array and pushs it to Location.erb file

## /save_location - Get AJAX Data from front end and parses into yaml format
Gets post data from live table so query can be delete/edit, updates the relative groups based on ID read from yaml file. Formates data back
into yaml format and saves file. If the data submited for the current feild is empty it uses the default value from file.
As the frontend we do not display passwords for ISO standards.

## /save_data - Gets New Ajax Data add to the end off groups
Gets AJAX data from front end slices into 4 chunk arrays, which are then processed and added to the end of config file.


