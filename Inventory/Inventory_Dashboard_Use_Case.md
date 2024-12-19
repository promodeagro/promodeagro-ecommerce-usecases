# ﻿Use Case: Inventory Dashboard in Inventory Management Application
# **Use Case Description:**
This use case describes the scenario where the Admin accesses the inventory dashboard of an inventory management web application. The dashboard provides an overview of inventory statistics, such as total items, stock levels, inventory value, and recent orders. It also presents graphical representations of Purchase & Sales Stock, Transactions, and Order Types with filter options for specific time periods and data types.
# **Trigger Point:**
The Admin selects the Dashboard option from the inventory management application menu or logs into the application.
# **Actor:**
Admin
# **Pre-Conditions:**
1. The Admin is logged into the system.
2. The inventory data, including purchase, sales, and order transactions, is up-to-date.
3. Graphical representations and summary statistics are pre-configured and functional.
# **Post-Conditions:**
1. The Admin successfully views the dashboard, including an overview of inventory statistics, filtered data, and visualizations of inventory activities.
2. The Admin can take actions like adding new items, adjusting filters, or using the calendar to navigate specific dates.
# **Normal Flow:**
1. Admin logs into the system and navigates to the Dashboard section.
2. The system displays key metrics at the top:
 - Total Items in Inventory
 - Total Quantity On Hand
 - Total Inventory Value
 - Recent Orders
3. The system shows graphs for:
 - Purchase & Sales Stock with filter options: Today, Weekly, Monthly, Yearly.
 - Transactions with time of day filters: Morning, Afternoon, Evening, Night.
 - Order Type filters: UPI, Cash, Card.
4. The Admin can interact with the filter buttons for each graph, selecting desired timeframes or data categories.
5. The Admin can click the Calendar to filter data by a specific date.
6. The Admin can select Add Item to add a new product to the inventory.
7. The dashboard updates based on the applied filters and selections, providing the Admin with detailed insights.
# **Alternative Flow:**
A1: No Inventory Data Available
 - If there is no inventory data, the system displays a message such as 'No Data Available' or renders blank charts.

A2: Filter Returns No Results
 - If a specific filter (e.g., Transactions for 'Morning' or Order Type 'UPI') has no matching data, the graph shows 'No Data Available' for that filter.

A3: Adding a New Item
 - When the Admin clicks the Add Item button, the system navigates to the product addition interface, allowing the Admin to add a new item to the inventory.
