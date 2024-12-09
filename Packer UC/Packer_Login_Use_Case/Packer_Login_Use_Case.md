# **Use Case: Packer Application Login and Password Recovery**
## **Use Case Description**
This use case outlines the steps a Packer takes to log in to the Packer application. If the Packer forgets the password, the use case describes how the Packer can recover it by requesting an OTP, verifying it, setting a new password, and logging in again.
## **Trigger Point**
The Packer launches the Packer application and navigates to the login page.
## **Actor**
Packer
## **Pre-conditions**
1\. The application is installed and accessible.

2\. The Packer has valid credentials registered in the system.

3\. Internet connectivity is available.
## **Post-conditions**
1\. The Packer successfully logs into the application.

2\. If the password is forgotten, the Packer resets it and gains access to the login page.
## **Normal Flow**
1\. Login Page Access:

\- The Packer launches the application and accesses the login page.

\- The login page displays fields for entering email and password.

2\. Entering Credentials:

\- The Packer enters their email and password.

\- The Packer clicks the Login button.

3\. Successful Login:

\- The system validates the entered credentials.

\- If valid, the system grants access to the application dashboard.
## **Alternative Flow (Forgot Password)**
1\. Forgot Password Initiation:

\- The Packer clicks the Forgot Password link on the login page.

\- The system navigates to the 'Forgot Your Password' page.

2\. Email Entry:

\- The Packer enters their registered email address.

\- The Packer clicks the Send OTP button.

3\. OTP Verification:

\- The system sends a One-Time Password (OTP) to the Packer's email.

\- The Packer enters the received OTP.

\- The system verifies the OTP.

4\. Password Reset:

\- Upon successful OTP verification, the system navigates to the 'Create New Password' page.

\- The Packer enters and confirms a new password.

\- The Packer clicks the Create Password button.

5\. Redirect to Login:

\- The system saves the new password.

\- The Packer is redirected to the login page.

6\. Login with New Password:

\- The Packer logs in using the new password.
