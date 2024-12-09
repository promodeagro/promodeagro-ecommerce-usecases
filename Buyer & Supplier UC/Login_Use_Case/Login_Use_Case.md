# **Use Case for Login Module**
## **Use Case Title: Login and Password Recovery Module**
### **Use Case Description**
This use case defines the process where Buyers or Suppliers log in to the application using their email and password. It also describes the password recovery process when a Buyer/Supplier forgets their password.
### **Actors**
\- Buyer

\- Supplier
### **Trigger Point**
The Buyer/Supplier opens the application and navigates to the login module.
### **Preconditions**
1\. The Buyer/Supplier has a registered account with a valid email and password.

2\. The application is accessible and functioning correctly.
### **Postconditions**
1\. On successful login: The Buyer/Supplier is directed to the dashboard.

2\. On password reset: The Buyer/Supplier creates a new password, and the system redirects them to the login page for authentication.
### **Normal Flow (Login)**
1\. The Buyer/Supplier enters their registered Email and Password in the respective fields.

2\. The Buyer/Supplier clicks the Login button.

3\. The system validates the credentials:

`   `- If valid, the system grants access to the Buyer/Supplier's dashboard.
### **Alternative Flow (Forgot Password)**
1\. The Buyer/Supplier clicks on the Forgot Password button.

2\. The system prompts the Buyer/Supplier to enter their registered email.

3\. The Buyer/Supplier enters their email and submits the request.

4\. The system sends a 6-digit OTP to the Buyer/Supplier's email.

5\. The Buyer/Supplier enters the OTP in the application.

`   `- If the OTP is valid, the system prompts the Buyer/Supplier to create a new password.

6\. The Buyer/Supplier enters a new password and confirms it.

7\. The system updates the password successfully.

8\. The system redirects the Buyer/Supplier to the login page.

