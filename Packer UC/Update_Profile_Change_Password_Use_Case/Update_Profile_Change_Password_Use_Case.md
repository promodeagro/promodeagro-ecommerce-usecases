# **Use Case: Update Profile and Change Password**
## **Use Case Description:**
The packer can update their profile details, such as username, email, and password, through the profile update feature. The process begins by clicking the 'Edit' button, which allows the packer to change their password. Upon submitting the updated details, the system validates the information and saves the changes.
## **Trigger Point:**
When the packer clicks on the 'Edit' button to update their profile or change their password.
## **Actor:**
Packer
## **Preconditions:**
\- The packer must be logged into the system.

\- The profile details page is accessible to the packer.

\- The system must have existing user information stored.
## **Postconditions:**
\- The updated profile information is saved in the system.

\- The password is updated successfully, and the packer can log in using the new password.

\- A confirmation message is displayed to the packer indicating that the changes were saved successfully.
## **Normal Flow:**
\- The packer logs into the system and navigates to the 'Profile Details' page.

\- The packer clicks the 'Edit' button.

\- The system displays editable fields for username, email, and password.

\- The packer updates the necessary details:

\-    - For password change: The packer enters the current password and the new password.

\- The packer clicks the 'Change Password' button to save the updates.

\- The system validates the entered details:

\-    - Ensures the current password matches the existing password.

\-    - Checks that the new password meets complexity requirements.

\- If validation succeeds, the system saves the updated details.

\- A confirmation message is displayed: 'Profile updated successfully.'

\- The packer is redirected to the updated 'Profile Details' page.
## **Alternative Flow:**
\- If the current password entered is incorrect, the system displays an error message: 'Incorrect current password. Please try again.'

\- If the new password does not meet the requirements, the system displays a validation message: 'Password must meet the complexity requirements.'

\- The packer can re-enter the details and attempt to save them again.
