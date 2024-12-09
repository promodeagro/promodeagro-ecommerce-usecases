# **Use Case Document**
## **Use Case Name: Confirmed Purchase Order Management**

## **Use Case Description**
This use case explains how the buyer manages confirmed purchase orders by sorting them, viewing detailed order information, and updating purchase statuses for items in the list.
## **Trigger Point**
The use case is triggered when the buyer navigates to the Confirmed P.O section on the Purchase Order Summary screen and selects a specific confirmed purchase order to manage.
## **Actors**
• Buyer
• Supplier
## **Preconditions**
1\. The buyer must be logged into the system.
2\. There should be confirmed purchase orders available in the system.
## **Postconditions**
1\. The system updates the purchase status for each item in the confirmed purchase order.
2\. If items are purchased, they are displayed in the Purchased tab.
3\. If items are not available, they are displayed in the Not Available tab.
## **Normal Flow**
1. The buyer navigates to the Confirmed P.O section from the Purchase Order Summary.
2. The buyer can sort the orders by Latest P.O or Oldest P.O using the dropdown.
3. The buyer selects a confirmed purchase order and clicks the View Details button.
4. The system displays the order details, including:
- Delivery date
- Ship to location
- Payment term
- Notes
- Item List (Name, Quantity)- Cost Details (Subtotal, Shipping Charges, Loading Charges, Total Amount)
5. The buyer selects an item from the list to open the Item Details Page, which displays:
- Item name
- Requested quantity
- Add details section:
- Purchased Quantity
      - Purchasing Price (per kg)
      - Selling Price (per kg)
      - Total Purchasing Cost
6.The buyer enters the required details for the item and clicks the Save button to continue to the next item.
7. If an item is unavailable, the buyer clicks the Not Available button.
8. The system updates the status of purchased items in the Purchased tab and unavailable items in the Not Available tab.
## **Alternative Flow**
For Items Marked as Not Available:
1. Steps 1 to 5 are the same as the normal flow.
2. When an item is unavailable, the buyer selects the Not Available button directly.
3. The system records the item as unavailable and updates the Not Available tab.
4. The buyer continues to manage the next item in the list.
