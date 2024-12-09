# **Use Case: Dashboard and Side Navigation**
## **Use Case Description:**
The use case covers the functionalities of the dashboard and the side navigation bar. The dashboard provides an overview of purchase orders (pending, confirmed, rejected, completed) and payment status (amount to receive, received amount, partial payments, and P.O issues). The side navigation bar offers access to sections like Purchase Orders, Payments, Profile, Notifications, and Logout.
## **Trigger Point:**
The Buyer or Supplier logs into the application and accesses the dashboard or side navigation.
## **Actor:**
Buyer and Supplier.
## **Pre-Conditions:**
1\. The Buyer or Supplier is successfully logged into the application.

2\. The system has data related to purchase orders and payment summaries.
## **Post-Conditions:**
1\. The Buyer or Supplier can view detailed statistics of purchase orders and payments.

2\. Navigation to specific sections like Purchase Orders, Payments, and Profile is enabled.
## **Normal Flow:**
1. The Buyer or Supplier logs into the application.
2. The system displays the Dashboard as the default view.
3. The Buyer or Supplier views the Purchase Order Overview, which includes:
 - Pending Purchase Orders.
 - Confirmed Purchase Orders.
 - Rejected Purchase Orders.
 - Completed Purchase Orders.
4. The Buyer or Supplier views the Payment Overview, which includes:
 - Amount to Receive.
 - Received Amount.
 - Partial Payments.
 - P.O Issues.
5. The Buyer or Supplier clicks on the Side Navigation Menu (hamburger icon).
6. The system opens the side navigation bar, displaying options:
 - Dashboard.
 - Purchase Order.
 - Payments.
 - Profile.
 - Notifications (with notification count).
 - Logout.
7. The Buyer or Supplier selects an option to navigate to the respective section.
## **Alternative Flow:**
Forgot Password Flow:

1. The Buyer or Supplier clicks the 'Forgot Password' option on the login screen (if unable to log in).
2. The system prompts the user to enter their registered email.
3. The system sends a 6-digit OTP to the entered email.
4. The Buyer or Supplier enters the OTP to verify.
5. The system prompts for a new password and confirms the password.
6. Upon successful password creation, the system redirects to the login screen.
