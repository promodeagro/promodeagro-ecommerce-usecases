# **Use Case: View Packed Order Details**
## **Use Case Description**
This use case describes the process of a packer viewing the details of a packed order from the packed orders list in the Packer App.
## **Trigger Point**
The packer needs to verify the details of a specific packed order.
## **Actors**
Primary Actor: Packer
## **Pre-Conditions**
1\. The packer is logged into the Packer App.

2\. The packed order list is displayed with updated data.

3\. The "View Details" button is functional and linked to the order details page.
## **Post-Conditions**
1\. The order details screen is displayed, showing all relevant information (e.g., customer name, order ID, payment method, item list, and cost details).

2\. The packer can view details to verify the order's accuracy.
## **Normal Flow**
1\. The packer accesses the "Packed Orders" tab in the app.

2\. The app displays a list of packed orders, including order IDs, customer names, and total items.

3\. The packer identifies the required order and clicks the "View Details" button associated with that order.

4\. The app navigates to the "Order Details" screen.

5\. The "Order Details" screen displays:

- `   `- Order ID
- `   `- Customer Name
- `   `- Payment Method
- `   `- Total Price
- `   `- Item List with item name, quantity, and price
- `   `- Cost Details including subtotal, shipping charges, and total amount
## **Alternative Flow**
Scenario: No Orders Found

1\. The packed orders list is empty.

2\. The app displays a message: "No packed orders available."


Scenario: System Error

1\. The packer clicks "View Details" but the system fails to retrieve the order details.

2\. The app displays an error message: "Unable to load order details. Please try again later."


Scenario: Incorrect Order Details

1\. After viewing the order details, the packer identifies missing or incorrect information.

2\. The packer flags the issue using a feedback mechanism or contacts the support team.
