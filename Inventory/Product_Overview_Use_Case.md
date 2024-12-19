Use Case: Product Overview - View and Manage Specific Product Details
# **Actor:**
Admin
# **Description:**
This use case describes how the Admin views and manages the details of a specific product within the inventory management system. The Admin can access the product's overview, order history, movement history, and item-vendor details. They can also perform actions such as reordering, transferring, cloning, or deleting the item.
# **Preconditions:**
\- The Admin is logged into the system with sufficient permissions to view and manage product details.
\- The product exists in the inventory with defined categories, stock information, and movement history.
\- Vendor and sales data are pre-populated for the product.
# **Postconditions:**
\- The Admin successfully views and manages the product details, including sales, order, and vendor information.
\- Any changes made (e.g., reordering or deleting the product) are updated in the system.
\- Stock levels and product status (active/inactive) are updated as per Admin actions.
\- The system maintains an accurate history of movements and sales for the product.
# **Trigger Point:**
The Admin selects a specific product (e.g., "Raw Banana") from the inventory to view its detailed information.
# **Normal Flow:**
1\. Admin navigates to the product overview:
`   `- The Admin clicks on a product (e.g., "Raw Banana") to open its detailed view.
`   `- The Overview tab is displayed, showing the following sections:
`     `- Item Information: Displays the product’s category, item code, unit of measurement, and the created source (Admin).
`     `- Purchase and Sales Information: Shows purchasing and minimum selling prices.
`     `- Quantity on Hand: Displays the stock quantity in the main warehouse and other stores.
`     `- Sales Order Summary: A graphical representation of monthly revenue with a filter for Site1 or Average Revenue.

2\. Admin views order history:
`   `- The Admin clicks on the Order History tab.
`   `- A table is displayed with details such as Order ID, Status, Date, Location, Quantity, and Subtotal.

3\. Admin views movement history:
`   `- The Admin clicks on the Movement History tab.
`   `- A table is displayed with details such as Movement Type, Movement Date, Location, and Quantity.

4\. Admin views item-vendor information:
`   `- The Admin clicks on the Item-Vendor tab.
`   `- A table is displayed with details such as Vendor Name, Product Name, Subtotal, and Location.

5\. Admin changes the product status:
`   `- The Admin uses the Toggle button at the top-right corner to mark the product as Active or Inactive.

6\. Admin performs actions on the product:
`   `- The Admin clicks the Action button and chooses one of the following options:
`     `- Reorder: Reorder the product for stock replenishment.
`     `- Transfer Item: Move stock from one warehouse to another.
`     `- Clone Item: Create a duplicate of the product entry.
`     `- Delete Item: Permanently remove the product from the inventory.
# **Alternative Flow:**
5A:
` `- If the Admin attempts to toggle the product status and the product is in an invalid state for deactivation (e.g., pending orders), the system displays an error message and prevents the action.

6A:
` `- If the Admin attempts to delete the product, the system prompts for confirmation. If the product is linked to ongoing orders or vendor contracts, the system displays a warning and blocks the deletion.

6B:
` `- If the Admin selects Reorder but the product is out of stock with all vendors, the system notifies the Admin and suggests possible alternatives or future restocking dates.
