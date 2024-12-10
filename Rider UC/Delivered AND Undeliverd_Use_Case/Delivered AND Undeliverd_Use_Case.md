# **Use Case for Rider App: Delivery and Undelivery Orders**
## **Use Case Title: View and Manage Delivered and Undelivered Orders**
### **Use Case Description**
This use case describes the functionality provided to the Rider to view Delivered and Undelivered Orders via the Rider App. Riders can view details of delivered orders, and for undelivered orders, they can attempt to resolve the issues and reattempt delivery by using the provided Reattempt button.
### **Actor**
RIDER
### **Trigger Point**
The Rider selects either the Delivered Orders or Undelivered Orders option from the Runsheet section of the app.
### **Preconditions**
1\. The Rider must be logged in to the Rider App.

2\. Orders must be assigned to the Rider in the system.

3\. The app must have an active internet connection.

4\. The Rider has access to the Runsheet feature in the app.
### **Postconditions**
1\. The Rider views detailed lists of Delivered and Undelivered Orders.

2\. If the Rider uses the Reattempt button on an undelivered order, the system processes the delivery reattempt and updates the order's status.
### **Normal Flow**
1\. The Rider navigates to the Runsheet in the app.

2\. The Rider selects Delivered Orders:

- The system displays a list of all delivered orders with details like:

- Customer Name

- Address

- Payment Information (e.g., ₹2980)

- Number of Items

3\. The Rider selects Undelivered Orders:

- The system displays a list of undelivered orders with details like:

- Customer Name

- Address

- Payment Type (COD or Prepaid)

- Number of Items

- Reason for Non-Delivery

4\. For undelivered orders:

- The Rider clicks the Reattempt button.

- The system processes the reattempt request and redirects the Rider to the delivery module for reattempting the order.
### **Alternative Flow**
1\. If the Rider's app loses connectivity, the system displays an error message and restricts actions like viewing orders or initiating reattempts.

2\. If the Rider clicks the Reattempt button for an undelivered order with incomplete details:

- The system prompts the Rider to fill in the missing delivery details or contact the customer support team.

3\. If the Reattempt action fails (e.g., backend error):

- The system displays a failure notification and suggests retrying after some time.
