# **Use Case: Purchase Order Management**
## **Use Case Description:**
This use case details how a Buyer and Supplier interact with the purchase order summary to view, sort, and manage purchase orders (P.O.). Buyers can sort orders, view detailed information, and decide to confirm or reject a purchase order.
## **Trigger Point:**
The Buyer navigates to the 'Purchase Order Summary' page from the dashboard.
## **Actor(s):**
\- Buyer

\- Supplier
## **Pre-conditions:**
1\. The Buyer and Supplier are logged into the system.

2\. There are purchase orders (Pending, Confirmed, Rejected, Completed) available in the system.
## **Post-conditions:**
1\. The purchase order status is updated based on the Buyer’s selection (Confirmed or Rejected).

2\. Changes are reflected in the Purchase Order Summary dashboard.
## **Normal Flow:**
1\. The Buyer navigates to the 'Purchase Order Summary' page.

2\. The system displays four cards showing the count of:

- Pending P.O

- Confirmed P.O

- Rejected P.O

- Completed P.O

3\. The Buyer clicks the 'Sort by' dropdown to sort purchase orders by:

- Latest P.O

- Oldest P.O

4\. The Buyer selects a 'Pending P.O' and clicks 'View Details.'

5\. The system displays purchase order details including:

- Delivery Date

- Ship To

- Payment Term

- Note

- Item List (Name and Quantity).

6\. The Buyer sees two options:

- Confirm Purchase Order

- Reject Purchase Order.

7\. If the Buyer selects Confirm Purchase Order, the system updates the P.O status to Confirmed.

8\. If the Buyer selects Reject Purchase Order, the system updates the P.O status to Rejected.
## **Alternative Flow:**
Scenario: No Purchase Orders Found

1\. The Buyer navigates to the 'Purchase Order Summary' page.

2\. The system displays a message: 'No purchase orders available.'

Scenario: Buyer Cancels Action

1\. The Buyer clicks 'View Details' of a purchase order.

2\. The Buyer decides not to confirm or reject and returns to the previous page without making changes.
