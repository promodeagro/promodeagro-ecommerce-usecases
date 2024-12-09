# **Use Case for Payment Overview in Procurement Dashboard**
## **Use Case Name:**
Payment Overview and Details Management
## **Actors:**
\- Buyer: Interacts with the payment overview to review, manage, and process payments.
\- Supplier: Provides the purchase order (P.O) and associated payment details.
## **Use Case Description:**
This use case describes how a Buyer interacts with the Payment Overview on the procurement dashboard to manage payments. The Buyer can view payment summaries (Pending Payments, Received Payments, Partial Payments, and P.O Issues). The Buyer may also view specific purchase order (P.O) details, payment breakdown, and item lists, edit item details, and handle payments.
## **Trigger Point:**
The Buyer selects the "Payment" option from the side menu on the Procurement Dashboard.
## **Preconditions:**
1\. The Buyer is logged into the Procurement system.
2\. The system has pre-existing payment records and purchase orders associated with the Buyer.
3\. The Buyer has access to view and manage payments.
## **Postconditions:**
1\. Payment or item details are updated in the system after successful confirmation.
2\. Purchase Order (P.O) records and payment statuses are updated as necessary.
3\. Any edited or deleted details reflect accurately in the procurement system.
## **Normal Flow:**
1\. The Buyer navigates to the Payment section from the side menu on the dashboard.
2\. The Payment Overview page displays four cards:
`   `- Pending Payments
`   `- Received Payments
`   `- Partial Payments
`   `- P.O Issues
3\. The Buyer clicks on the View Details button for a specific P.O under Pending Payments.
4\. The system displays detailed information, including:
`   `- Delivery Date
`   `- Ship to (location)
`   `- Payment Term
`   `- Completed P.O date
`   `- Amount Due
`   `- Notes
5\. The Buyer has two options:
`   `- Payment Details:
`     `- Displays breakdown: Subtotal, Shipping Charges, Loading Charges, Total, and Amount Due.
`   `- Item List:
`     `- Displays purchased and unavailable items.
`     `- Specific item details include:
`       `- Item Name
`       `- Category
`       `- Requested Quantity
`       `- Purchase Quantity
`       `- Purchasing Price (per kg)
`       `- Selling Price (per kg)
`       `- Total Purchasing Cost
6\. The Buyer selects an item to view more details or edits the details using the Edit option in the top-right corner.
7\. The Buyer can update item details or choose to delete them using the Delete option.
8\. Upon confirming updates:
`   `- The system saves the changes and reflects them in the respective records.
9\. If the Buyer proceeds with a payment:
`   `- The system processes the payment and updates the status in the Payment Overview and P.O records.
## **Alternative Flow:**
Flow A: Cancel Updates
1\. If the Buyer edits details but selects Cancel instead of confirming:
`   `- The system does not save the changes, and the details remain unchanged.

Flow B: View P.O Issues
1\. The Buyer clicks the P.O Issues card in the Payment Overview.
2\. The system displays a list of purchase orders with identified issues.
3\. The Buyer reviews the issue details and takes corrective action.

Flow C: Delete Details
1\. The Buyer selects the Delete option for an item.
2\. The system displays a confirmation pop-up:
`   `- If the Buyer confirms, the details are permanently deleted.
`   `- If the Buyer cancels, the deletion process is aborted.

Flow D: Partial Payment
1\. The Buyer selects a P.O with a pending partial payment.
2\. The system shows details of the outstanding amount.
3\. The Buyer initiates a partial payment.
4\. The system updates the payment status and adjusts the balance amount.
