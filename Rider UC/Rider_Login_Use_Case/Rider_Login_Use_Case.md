# **Use Case: Rider Login Using OTP**
Actor: Rider

Description: This use case allows a rider to log in to the application by entering their registered mobile number, receiving an OTP, and verifying it.
## **Trigger Point:**
The rider opens the application and enters their registered mobile number to log in.
## **Pre-Conditions:**
1\. The rider has a valid account with a registered mobile number in the system.

2\. The rider's mobile device has an active internet connection.

3\. The system is configured to send OTPs via SMS or other services.
## **Post-Conditions:**
1\. Successful Login: The rider is redirected to their dashboard.

2\. Failed Login: The rider is prompted with an appropriate error message and remains on the login screen.
## **Normal Flow:**
1\. The rider launches the application.

2\. The login screen is displayed.

3\. The rider enters their registered mobile number in the input field.

4\. The rider clicks the 'Sign In' button.

5\. The system validates the mobile number and sends a six-digit OTP to the rider’s registered number.

6\. The OTP Verification screen is displayed.

7\. The rider enters the OTP in the provided fields.

8\. The rider clicks the 'Verify OTP' button.

9\. The system verifies the OTP:

`   `- If valid, the rider is logged in and redirected to the home screen.

`   `- If invalid, an error message is displayed, and the rider can re-enter the OTP or request a resend.
## **Alternative Flow:**
OTP Resend Flow:

1\. If the rider does not receive the OTP within the expected time, they can click on the 'Resend OTP' link.

2\. The system generates and sends a new OTP to the registered mobile number.

3\. The rider enters the new OTP and follows the normal flow from step 8.
