# **Use Case: View Profile and Notifications**
## **Use Case Description:**
This use case describes how a Buyer or Supplier accesses their profile information and views notifications related to purchase orders, payments, and other activities in the Procurement system.
## **Trigger Point:**
The Buyer or Supplier selects the "Profile" option to view their personal details or the "Notifications" option from the dashboard to check recent updates.
## **Actors:**
Buyer
Supplier
## **Preconditions:**
1 . The Buyer or Supplier is logged into the system.
2. Profile details such as name, email, and mobile number are already saved in the system.
3. Notifications related to purchase orders, payments, or other updates are available in the system.
## **Postconditions:**
1. The Buyer or Supplier views their profile details and verifies them.
2. Notifications are displayed with details like order status, payment confirmation, and item delivery updates.
3. Notifications are marked as read if interacted with or dismissed.
## **Normal Flow:**
### **1. View Profile:**
1. The Buyer or Supplier selects the "Profile" option from the dashboard.
2. The system displays the user's details, including:
- User Name
- Email
- Mobile Number
3. The Buyer or Supplier confirms the details and clicks "Continue" to return to the dashboard.
### **2. View Notifications:**
1. The Buyer or Supplier selects the "Notifications" option from the dashboard.
2. The system displays a list of notifications categorized by their status:
- Blue Notification: Indicates a new purchase order (e.g., "You have received a new purchase order [PO-00001].").
- Red Notification: Indicates rejected orders (e.g., "You have rejected the purchase order [PO-00002].").
- Green Notifications: Indicate successful actions, such as payment received or items delivered.
3. The Buyer or Supplier reviews the notification details.
4. Notifications can be dismissed by clicking the close ("X") button.
## **Alternative Flows:**
### **1. No Profile Data Available:**
1. If the system does not retrieve profile data:
- An error message is displayed: "Profile details are unavailable at this time. Please try again later."
- The Buyer or Supplier is redirected back to the dashboard.
### **2. No Notifications Found:**
1. If there are no notifications available:
- A message is displayed: "No notifications to display."
- The Buyer or Supplier can return to the dashboard.
### **3. Dismiss Notifications:**
1. If the Buyer or Supplier clicks the close ("X") button on any notification:
- The notification is removed from the list.
- The system updates the status of the notification as dismissed.
