# **Use Case: Manage Shipment Delivery for a Rider**
## **Use Case Description:**
This use case describes the process where a rider selects a specific shipment to deliver and performs actions such as viewing customer details, verifying orders, collecting payment (via cash or QR code), and completing the order.
## **Trigger Point:**
The rider selects a shipment from the list of available shipments in the runsheet.
## **Actor:**
Rider
## **Preconditions:**
\- The rider has logged into the Rider App.

\- The runsheet and its associated shipments are already assigned to the rider.

\- The shipment details, including customer and order information, are available in the system.
## **Postconditions:**
\- The order is marked as delivered in the system.

\- The collected payment is recorded in the app.

\- The runsheet is updated with the completed order.
## **Normal Flow:**
1. Rider Selects Shipment: The rider selects a specific shipment from the 'All Shipment' list.

 2. Display Customer Details: The system displays the customer's details, including:
- Name, Address, Pincode, City, State, Phone Number.
- The system provides a 'Call' button to allow the rider to contact the customer if needed.

3. View Item List: The rider views the list of items in the shipment, which includes:
- Order ID, Products, Quantity, Price, and the Amount to be Collected.

4. Conform or Cancel Order:
- Confirm Order: Proceed with delivery.
- Cancel Order: Stop the delivery process.

5. Verify Order: Upon confirming the order, the system prompts the rider to click an image of the order for verification.

6. Collect Payment: The system displays the 'Collect Payment' screen, offering two options:
1. Collect Cash:
 - The rider clicks the 'Collect Cash' button.
 - A pop-up appears showing 'Collecting Cash: [XXX Amount].'
 - After receiving the cash, the rider clicks 'Complete Order.'
 - A confirmation pop-up states, 'The amount has been collected.'
2. QR Code Payment:
- The rider selects QR Code generation.
- The system displays a QR Code valid for 120 seconds.
- The rider collects the online payment and confirms once the payment is received.

8. Complete Order: The system updates the status of the order to 'Delivered.' The runsheet is updated, and the rider is redirected to the shipment list.
## **Alternative Flow:**
- Cancel Order: If the rider selects 'Cancel Order,' the system updates the order as 'Cancelled.' The runsheet is updated with the order status.

- QR Code Expiry: If the QR Code expires before payment is received, the system generates a new QR Code for the rider.

- Incomplete Payment: If the payment is not completed (cash or online), the rider can retry the collection process.
