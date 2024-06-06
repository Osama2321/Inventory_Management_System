Brief Report 
Approach
The inventory management system was developed using Python with the primary goal of maintaining 
and manipulating an inventory list. The system allows users to add, remove, update, search, display, 
save, and load inventory items. 

Data Structure 
Inventory: The inventory is stored as a list of dictionaries, where each dictionary represents an item with 
attributes like item_id, item_name, quantity, price, and category. 
User Interface Design 
 Console-Based Interface: The system uses a simple console-based interface to interact with the 
user. The interface presents a menu with options for adding, removing, updating, searching, 
displaying, saving, and loading inventory items. 
 Input Validation: The interface includes basic input validation to ensure that the user inputs the 
correct data types for each field. 

Implemented Features: 
 Add Item: Allows users to add a new item to the inventory. 
 Remove Item: Allows users to remove an item from the inventory by specifying the item ID. 
 Update Item: Allows users to update specific fields of an existing item. 
 Search Item: Enables users to search for items based on specific criteria (e.g., item_id, 
item_name, category). 
 Display Inventory: Displays all items currently in the inventory. 
 Save Inventory: Saves the current state of the inventory to a json file . 
 Load Inventory: Loads the inventory from a json file.
