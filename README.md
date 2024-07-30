Inventory Management System
This is a simple Windows Forms application written in C#. The purpose of the application is to manage an inventory of items. It allows users to add, update, and delete items in the inventory. Each item in the inventory has an ID, name, quantity, and price.

![Screenshot 2024-07-30 093150](https://github.com/user-attachments/assets/f8b4e203-dbee-49fd-892b-fb732cf7fcf4)

Key Features:
Add Items: Users can add new items to the inventory by entering the item name, quantity, and price.
Update Items: Users can select an existing item in the DataGridView, modify its details, and update the inventory.
Delete Items: Users can remove an item from the inventory by selecting it and clicking the delete button.
Item List Display: The application displays a list of all items in a DataGridView, making it easy to see all inventory items at a glance.
Data Binding: The DataGridView is bound to a list of items, and the display updates automatically when items are added, updated, or deleted.
Selection Handling: When an item is selected in the DataGridView, its details are displayed in text boxes for easy viewing and editing.

User Interface:
DataGridView: Displays the list of items.
TextBoxes: Allow the user to enter or modify the name, quantity, and price of an item.

Buttons:
Add: Adds a new item to the inventory.
Update: Updates the selected item's details.
Delete: Deletes the selected item.
Labels: Provide descriptions for the text boxes.

Program Flow:
Initialization: The main form initializes the component, sets up event handlers, and loads the initial items into the DataGridView.
Event Handling:
Add Button: Validates input and adds a new item.
Update Button: Validates input, checks if an item is selected, and updates the selected item.
Delete Button: Checks if an item is selected and deletes the selected item.
Selection Changed: Updates the text boxes with the details of the selected item.
Error Handling: The program includes basic error handling to ensure valid input for item details.
