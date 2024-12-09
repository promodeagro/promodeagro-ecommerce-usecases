# **Use Case: Rider Runsheet Management**
## **Use Case Description:**
The Rider interacts with the application to view available runsheets, accept a specific runsheet, and manage the associated orders. The runsheet contains details of pending, delivered, and undelivered shipments. The Rider can search for shipments and view details such as payment type (COD or prepaid).
## **Trigger Point:**
The Rider logs into the app and navigates to the "Home" page, which displays available runsheets.
## **Actor:**
Rider
## **Pre-conditions:**
1\. The Rider must have a valid login to access the app.

2\. Runsheets are assigned to the Rider and available in the system.

3\. The system should have order details, including shipment status (Pending, Delivered, Undelivered) and payment type (COD or Prepaid).
## **Post-conditions:**
1\. The selected runsheet is accepted and assigned to the Rider.

2\. Order statuses can be updated based on Rider's actions (Delivered/Undelivered).

3\. Shipment details remain accessible for further management.
## **Normal Flow:**
1\. The Rider logs into the app and navigates to the "Home" page.

2\. The app displays available runsheets with information such as:

`   `- Number of orders (Pending, Delivered, Undelivered)

`   `- Total cash to be collected (if applicable).

3\. The Rider selects and accepts a runsheet by tapping "Accept Runsheet."

4\. The app navigates to the selected runsheet details, displaying:

`   `- Order statuses (Pending, Delivered, Undelivered).

`   `- Shipment details, including customer name, address, payment type (COD/Prepaid), and payment amount.

`   `- A search bar for finding specific shipments.

5\. The Rider updates the status of orders as they are delivered or marked undelivered.

6\. The app updates the order status in real time.
## **Alternative Flow:**
1\. If the Rider rejects a runsheet:

`   `- The app redirects back to the "Home" page, leaving the runsheet unassigned.

2\. If the Rider attempts to accept a runsheet but the system encounters a technical error:

`   `- The system shows an error message (e.g., "Unable to process request, please try again").

`   `- The Rider can retry or contact support.

3\. If no shipments match the Rider's search query:

`   `- The app displays a message like "No results found."
