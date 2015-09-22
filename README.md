# InventoryLookupEntryTool
A slick little 1 pager that allows you to add, delete, or modify inventory entries and use google sheets &amp; forms as a database for the back end. 

1. Copy these google spreadsheets to your own google drive: 

Product Info - https://docs.google.com/spreadsheets/d/12HQygaXcNy7aC7uG6g6w5lrSIFJOEHuvNWH92qduKiU

Inventory Location - https://docs.google.com/spreadsheets/d/1zpr9EPaNJ_2FOCCV7ca0iAjjeIV9H59tI6gVNso28qE
    
(the form should be automatically generated and accessable through the Inventory Location Spreadsheet) 

2. Replace these variables values on their respective lines in the inventory.html file using the strings from your google spreadsheets URL's starting on line 21. 
    21    var productInfoSpreadsheetUrlString = "12HQygaXcNy7aC7uG6g6w5lrSIFJOEHuvNWH92qduKiU";
    22    var formUrlString = "1GESlEZ1HTFWAGIVFvZl9A6mntXTaauF63-ewCY_Z7y4";
    23    var inventoryLocationSpreadsheetUrlString = "1zpr9EPaNJ_2FOCCV7ca0iAjjeIV9H59tI6gVNso28qE";

3. Open up the form, copy the field_id's for each entry field, and paste them in to the appropriate fields in the inventory.html file. Starts on line 222. 


4. Save to your webserver and launch! Enjoy entering various items and being able to look them up using the google sheet or the app. 

