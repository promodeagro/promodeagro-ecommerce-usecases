# **Use Case: Rider Menu and Account Management**
## **Use Case Description**
The Rider uses the menu to access various account features, such as "Amount Summary," "Profile Details," and "Notifications." These sections allow the Rider to track transaction history, view profile information, and stay updated with notifications for new runsheets.
## **Trigger Point**
The Rider clicks on the menu icon in the Rider App.
## **Actor**
Rider
## **Preconditions**
\- The Rider is logged into the Rider App.
\- The Rider has an active internet connection.
## **Postconditions**
\- The selected section (Amount Summary, Profile Details, or Notifications) is displayed.
\- Updates (if any) are loaded and shown to the Rider.
## **Normal Flow**
1\. The Rider accesses the menu screen by clicking the menu icon.
2\. The Rider selects one of the options:
`   `- Amount Summary: Displays transaction details.
`   `- Profile Details: Displays Rider profile information (e.g., Name, ID, Approval Status).
`   `- Notifications: Displays recent notifications (e.g., new runsheets).
## **Alternative Flow**
1\. Scenario 1:
`   `- If there is a network issue, the system displays an error message: "Unable to load data. Please check your internet connection."
`   `- The Rider is prompted to retry.

2\. Scenario 2:
`   `- If the Rider has no pending notifications, the app displays: "No new notifications."

3\. Scenario 3:
`   `- If the Rider selects "Amount Summary" but there are no transactions, the app displays: "No transactions found."
