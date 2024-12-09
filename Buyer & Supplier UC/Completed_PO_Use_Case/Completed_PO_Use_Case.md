# **Use Case: Viewing and Managing Completed Purchase Orders**
## **Use Case Description**
This use case explains how a Buyer interacts with the 'Completed P.O.' section to view the details of completed purchase orders, check payment information, review item lists, and sort completed orders by date.
## **Trigger Point**
The Buyer navigates to the 'Completed P.O.' section in the application and interacts with the available options.
## **Actors**
1\. Buyer

2\. Supplier
## **Pre-Conditions**
1\. The Buyer is logged into the system.

2\. Completed Purchase Orders exist in the system.

3\. The 'Sort by' dropdown and action buttons (Payment Details, Item List) are functional.
## **Post-Conditions**
1\. The selected P.O. details, payment information, and item lists are displayed.

2\. The Buyer may access payment history and review the purchased/not-available items.

3\. The system updates and logs any viewed or sorted actions for records.
## **Normal Flow**
1\. Buyer Views Completed Purchase Orders

\- The Buyer selects the 'Completed P.O.' section.
\- The system displays a summary of completed purchase orders, including total counts.

2\. Sorting Completed P.O.

\- The Buyer clicks the 'Sort by' dropdown and selects either 'Latest Completed P.O.' or 'Old P.O.'
\- The system sorts and updates the list based on the selected criteria.

3\. Viewing P.O. Details

\- The Buyer selects a specific completed P.O. and clicks 'View Details.'
\- The system displays the following details:
  - Delivery Date
  - Ship To
  - Payment Term
  - Completed P.O. Status
  - Amount Received
  - Notes

4\. Checking Payment Details

\- The Buyer clicks the 'Payment Details' button within the P.O. details.
\- The system shows:
- Subtotal
- Shipping Charges
- Loading Charges
- Total Amount
- Payment Made
- Amount Due
\- If required, the Buyer clicks the 'Payment History' button to review all past payments for this P.O.

5\. Reviewing Item List

\- The Buyer clicks the 'Item List' button to see:
- Purchased Items (name and quantity).
- Items marked as 'Not Available' (name and quantity).
## **Alternative Flow**
Sorting Error:

\- If the system encounters an error while sorting:
- It displays an error message, and the Buyer can retry sorting or refresh the list.

Empty Completed P.O. List:

\- If no completed orders are available, the system displays a message: 'No Completed Purchase Orders found.'

Incomplete Payment Details:

\- If payment information is incomplete or not updated:
- The system notifies the Buyer with 'Payment details not available for this order.'

Item List Inconsistency:

\- If certain items are missing from the database or cannot be fetched:
`  `- The system highlights such items with a 'Data not available' message.
