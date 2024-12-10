
# Use Case: Notifications and Alerts for Rider

## Use Case Description
The application provides a notifications and alerts screen for the Rider. This screen shows updates such as the receipt of new Runsheets.

## Trigger Point
The Rider receives a notification in the Rider App when a new Runsheet is assigned.

## Actors
- **Primary Actor:** Rider

## Pre-Conditions
1. The Rider must be logged into the application.
2. The Rider should have a stable internet connection to receive notifications.

## Post-Conditions
1. Notifications are displayed on the screen.
2. The Rider can acknowledge and view details of each Runsheet notification.

## Normal Flow
1. The system sends a notification to the Rider about a new Runsheet.
2. The Rider navigates to the Notifications and Alerts screen.
3. The screen displays the list of notifications, including the Runsheet numbers and timestamps.
4. The Rider views the details of the notification.

## Alternative Flow
1. **No Internet Connection:**  
   - If the Rider’s device is not connected to the internet, the notification is not delivered immediately.
   - The system will send the notification once the device is reconnected to the internet.

2. **Acknowledgment:**  
   - The Rider can dismiss a notification by clicking on the close (X) button next to it.
