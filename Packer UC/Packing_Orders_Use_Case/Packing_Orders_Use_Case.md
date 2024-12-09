## **Use Case Name:**
Packing Orders via Packer Application
## **Actor:**
Packer 
## **Description:**
The use case describes how the packer interacts with the application to view unpacked orders, start the packing process, confirm the packing by taking a picture, and move the order to the 'Packed Orders' section.
## **Trigger Point:**
The packer clicks on the 'Start Order' button for a specific unpacked order on the home screen.
## **Preconditions:**
1\. The packer must be logged into the application.

2\. The system must display unpacked and packed orders on the home screen.

3\. There must be at least one unpacked order available in the system.
## **Postconditions:**
1\. The selected order is moved from the 'Unpacked Orders' section to the 'Packed Orders' section.

2\. The system captures the image of the packed order and updates the order status as 'Packed.'

3\. The application updates the count of unpacked and packed orders.
## **Normal Flow:**
1\. Home Screen Display: The packer logs into the application, and the home screen displays the counts of 'Unpacked Orders' and 'Packed Orders' along with the list of unpacked orders.

2\. Start Order: The packer selects an order by clicking the 'Start Order' button for a particular unpacked order.

3\. Order Details View: The system displays the details of the selected order, including:

`   `- Customer name.

`   `- Payment details.

`   `- Item list with quantities and prices.

`   `- Total cost details.

4\. Pack Order: The packer clicks on the 'Pack Order' button after verifying the order details.

5\. Take Picture of Packed Order:

`   `- The system prompts the packer to take a picture of the packed order using the device's camera.

`   `- The packer captures the image and submits it.

6\. Update Order Status: The system updates the order status as 'Packed' and moves it to the 'Packed Orders' section.

7\. Update Home Screen:

`   `- The count of unpacked orders is decremented.

`   `- The count of packed orders is incremented.

`   `- The order disappears from the unpacked orders list.
## **Alternative Flow:**
Scenario 1: No Camera Access

1\. The packer clicks the 'Pack Order' button, but the device camera fails to open or is inaccessible.

2\. The system displays an error message, 'Unable to access the camera. Please try again.'

3\. The packer resolves the issue and repeats the packing process.

Scenario 2: Incorrect Order Packing

1\. The packer realizes there is an issue with the order (e.g., missing items) before taking a picture.

2\. The packer clicks a 'Back' button to return to the order details screen.

3\. The packer corrects the issue, re-verifies the order, and resumes the packing process.
