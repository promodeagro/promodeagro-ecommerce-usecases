# **Use Case: Update Profile and Change Password**
## **Use Case Description:**
The packer can update their profile details, such as username, email, and password, through the profile update feature. The process begins by clicking the 'Edit' button, which allows the packer to change their password. Upon submitting the updated details, the system validates the information and saves the changes.
## **Trigger Point:**
When the packer clicks on the 'Edit' button to update their profile or change their password.
## **Actor:**
Packer
## **Preconditions:**
1. The packer must be logged into the system.

2. The profile details page is accessible to the packer.

3. The system must have existing user information stored.
## **Postconditions:**
1. The updated profile information is saved in the system.

2. The password is updated successfully, and the packer can log in using the new password.

3. A confirmation message is displayed to the packer indicating that the changes were saved successfully.
## **Normal Flow:**
1. The packer logs into the system and navigates to the 'Profile Details' page.

2. The packer clicks the 'Edit' button.

3. The system displays editable fields for username, email, and password.

4. The packer updates the necessary details:
- For password change: The packer enters the current password and the new password.
- The packer clicks the 'Change Password' button to save the updates.

5. The system validates the entered details:
- Ensures the current password matches the existing password.
- Checks that the new password meets complexity requirements.

6. If validation succeeds, the system saves the updated details.

7. A confirmation message is displayed: 'Profile updated successfully.'

8. The packer is redirected to the updated 'Profile Details' page.
## **Alternative Flow:**
1. If the current password entered is incorrect, the system displays an error message: 'Incorrect current password. Please try again.'

2. If the new password does not meet the requirements, the system displays a validation message: 'Password must meet the complexity requirements.'

3. The packer can re-enter the details and attempt to save them again.
