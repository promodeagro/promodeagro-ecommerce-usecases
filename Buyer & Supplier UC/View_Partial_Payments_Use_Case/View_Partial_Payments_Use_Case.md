# **Use Case: View Partial Payments Details**
## **Use Case Description:**
This use case describes the process where the buyer or supplier views the details of a specific P.O. listed under partial payments. The system displays information related to the payment, item list, and payment history.
## **Actors:**
Buyer & Supplier
## **Preconditions:**
1. The user (buyer/supplier) must be logged into the system.
2. There must be at least one P.O. listed under partial payments.
## **Trigger Point:**
The actor selects the "Partial Payments" section from the payment overview and clicks the "View Details" option for a specific P.O.
## **Postconditions:**
1. The system displays the details of the selected P.O., including payment details, item list, and payment history.
2. Any updates or changes made to the items or payment details are saved and reflected in the system.
## **Normal Flow:**
1. The actor navigates to the payment overview page and selects the "Partial Payments" card.
2. The system displays a list of P.O.s under partial payments.
3. The actor selects a specific P.O. by clicking the "View Details" option.
4. The system displays the P.O. details, including:
- Delivery Date
- Ship To
- Payment Terms
- Completed P.O. Date
- Amount Due
- Notes
5. The actor views the payment details by clicking the "Payment" button, which includes:
- Subtotal
- Shipping Charges
- Loading Charges
- Total
- Payment Made
- Amount Due
6. If the actor wishes to view the payment history, they click the "Payment History" button.
7. The actor can view the item list by clicking the "Item List" button, which includes:
- Purchased items
- Items not available
8. The actor completes their review and exits the page.
## **Alternative Flow:**
### **A1: Payment History Access**
1. If the actor wants to see the payment history, they click the "Payment History" button directly from the P.O. details page.
2. The system displays a detailed list of past payments for the selected P.O.
### **A2: Item Details**
1. From the item list, the actor can select a specific item to view detailed information, including:
- Item Name
- Category
- Requested Quantity
- Purchased Quantity
- Purchasing Price (per unit)
- Selling Price (per unit)
- Total Purchasing Cost
### **A3: Exit Without Action**
1. If the actor decides not to make any changes, they can exit the details page without performing any further actions.
