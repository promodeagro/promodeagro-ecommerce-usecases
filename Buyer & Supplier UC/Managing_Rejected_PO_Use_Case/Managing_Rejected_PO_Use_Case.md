# **Use Case: Managing Rejected Purchase Orders**
## **Use Case Description:**
This use case enables Buyers and Suppliers to manage rejected purchase orders effectively. Buyers can view, sort, and reconfirm rejected purchase orders.
## **Trigger Point:**
When a buyer accesses the Rejected P.O. section in the procurement system.
## **Actor(s):**
1\. Primary Actor: Buyer

2\. Secondary Actor: Supplier (not directly interacting in this flow but involved post-confirmation).
## **Pre-Conditions:**
1\. Buyer must be logged into the procurement system.

2\. Rejected purchase orders should exist in the system.

3\. The buyer should have the necessary permissions to view and manage rejected purchase orders.
## **Post-Conditions:**
1\. The status of the purchase order changes to Confirmed P.O. upon reconfirmation.

2\. Purchase order details are updated in the system and accessible to both buyer and supplier.
## **Normal Flow:**
1\. The Buyer navigates to the Rejected P.O. section under Purchase Orders.

2\. The system displays a summary of purchase orders categorized as Pending, Confirmed, Rejected, and Completed, along with the total count.

3\. In the Rejected P.O. section, the system displays:

- `   `- P.O. Number
- `   `- Delivery Date
- `   `- Ship To
- `   `- Payment Term

4\. The Buyer clicks the Sort By dropdown to select a sorting option:

- `   `- Latest Purchase Order
- `   `- Old Purchase Order

`   `The list updates based on the chosen option.

5\. The Buyer clicks View Details on a specific rejected purchase order.

6\. The system displays:

- `   `- Delivery Date
- `   `- Ship To
- `   `- Payment Term
- `   `- Note
- `   `- Item List (Item Name and Quantity).

7\. The Buyer clicks the Re-Confirm button.

8\. The system:

- `   `- Updates the P.O. status to Confirmed P.O.
- `   `- Notifies the Supplier about the updated status.
- `   `- Reflects the updated P.O. in the Confirmed P.O. section.
## **Alternative Flow:**
Sorting Failure:

1. 1. If sorting does not work due to a system error, the Buyer:
- `   `- Refreshes the page.
- `   `- Attempts sorting again.
1. 2. If the issue persists, the Buyer contacts technical support.

Reconfirmation Error:

1. 1. If the Buyer clicks Re-Confirm and an error occurs:
- `   `- The system displays an error message indicating the failure to update the status.
- `   `- The Buyer retries or contacts support.

Empty Rejected P.O. List:

1. 1. If no purchase orders are rejected, the system displays a message:
- `   `- 'No Rejected Purchase Orders Available.'
