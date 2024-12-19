# ﻿Use Case: Managing Inventory Adjustments
# **Use Case Description:**
The Admin needs to adjust inventory levels to reflect the correct stock count based on various reasons such as procurement, correction, or damage. The system provides an interface where adjustments can be created and updated with item details, reasons, and location information.
# **Trigger Point:**
When the Admin notices discrepancies in inventory levels or needs to make corrections for any reason, such as damage, correction, or procurement.
# **Actor:**
Admin
# **Preconditions:**
- The Admin is logged into the Inventory Management system.
- Inventory items are already populated in the system.
- Admin has appropriate permissions to make adjustments to inventory.
# **Postconditions:**
- The inventory is updated based on the adjustment made.
- Adjustments are logged with a reason, date, and item details for auditing.
- The stock count reflects the updated quantities for all affected items.
# **Normal Flow:**
1. Admin accesses the Inventory Adjustment screen from the main dashboard.
2. The Admin clicks on the 'New Adjustment' button (as seen in the first image).
3. The system displays a new screen for creating adjustments (as seen in the second image).
4. The Admin enters the following details:
- Adjustment Number (Auto-generated, e.g., SA-001).
- Location (Admin selects from options such as Cold Storage, Atmakur, Atmakur-2).
- Reason for adjustment (Options: Procure, Correction, Damage).
- Description (Optional text explaining the adjustment).
5. In the Item Details section, the Admin clicks on 'Add Items' to choose the items that need adjustment.
6. A pop-up appears (as seen in the third image), where the Admin can:
  - Search for items using the search bar.
  - Filter items by category (e.g., Futies, Vegetables, Leafy Vegetables, Dairy).
  - Select items from the displayed table which shows Item Code, Item Name, Stock on Hand, Purchasing Price, MSP.
7. After selecting items, the Admin enters the Adjustment Quantity for each item and modifies prices (if necessary).
8. The Admin clicks on the 'Save' button to confirm the adjustment.
9. The system saves the adjustment and updates the inventory accordingly.
# **Alternative Flow (No items to adjust):**
1. If no items are found in the inventory adjustment screen, the Admin receives a 'No adjustments found' message (as seen in the first image).
2. The Admin can still click on 'Create adjustment' to manually enter an adjustment and proceed as per the normal flow.
# **Alternative Flow (Adjustment Canceled):**
1. If the Admin chooses not to proceed with the adjustment, they click the 'Cancel' button on the adjustment screen.
2. The system discards the entered data, and no changes are made to the inventory.

