## ﻿Use Case: Inventory Management - View and Manage Items 

# Actor: Admin

# Description:

This use case describes how the Admin interacts with the Inventory Management system to view, filter, and manage items where certain item attributes (e.g., item code, quantity on hand, price) are currently undefined. The Admin can search for items, apply filters based on category, subcategory, and status, and modify or delete product information.


## **Preconditions:**
- The Admin is logged into the system with appropriate permissions to manage inventory items.

- Categories, subcategories, and item statuses are predefined in the system.

- Some items may lack complete data, such as item codes or pricing, which the Admin must correct or update.


## **Postconditions:**
- The inventory list reflects the latest information after modifications by the Admin.

- Items with undefined attributes are either updated with valid data or flagged for further review.

- The system shows up-to-date stock information, including low stock alerts and expired items.

## **Trigger Point:**
- The Admin accesses the Items section in the Inventory Management module, where they observe that certain items have undefined data (e.g., item codes, quantities, or prices).

## **Normal Flow:**
1. Admin navigates to the Inventory Management page: The Admin views a list of items (e.g., 'Biryani Curry Cut,' 'Goat Milk') with some details marked as 'undefined' (e.g., item code, quantity on hand).
1. Admin searches for specific items: The Admin uses the Search bar to find a product by name or item code.
1. Admin filters by category: The Admin clicks the Select Category button and selects from the following options: Fresh Vegetables, Fresh Fruits, Dairy, Groceries, Bengali Specials, Meat/Fish/Eggs. Depending on the selected category, the Admin is provided with relevant subcategory options.
1. Admin filters by status: The Admin clicks the Select Status button to view All, Active, or Inactive items.
1. Admin views stock alerts: The Admin checks the four information cards: All Products, Published Stock, Low Stock Alert, Expired.
1. Admin adds a new item: The Admin clicks the Add Item button in the top right corner to add a new product to the inventory.
1. Admin modifies existing items: The Admin clicks the Edit icon next to a product with undefined details (e.g., 'Goat Curry Cut').
1. Admin deletes an item: The Admin clicks the Delete icon next to an item they wish to remove.
1. Admin changes the status of an item: The Admin toggles the Status switch for items to activate or deactivate them.
1. Admin uses pagination: The Admin navigates between pages of items using the pagination controls at the bottom of the list.

## **Alternative Flow:**
1. If the Admin selects a category that has no subcategories, the subcategory filter remains inactive, and only the category filter applies.
1. If no products match the search criteria or filters, the system displays a message indicating no results were found.
1. If the Admin tries to add a new product but inputs invalid data (e.g., undefined quantities or prices), the system shows an error message.
1. If the Admin attempts to delete a product that is marked as 'Low Stock' or 'Expired,' the system displays a warning before proceeding with the deletion.
1. If the Admin leaves certain fields (e.g., quantity, price) as undefined while editing a product, the system may require that these fields be completed before allowing the changes to be saved.
