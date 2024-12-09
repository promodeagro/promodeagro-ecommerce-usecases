# **Use Case: View P.O Issues Details**
## **Use Case Description:**
This use case describes the process by which a Buyer or Supplier views details of a specific Purchase Order (P.O) listed under the P.O Issues section. The Buyer can view information such as missing items, purchased items, and payment details.
## **Trigger Point:**
The Buyer selects the "P.O Issues" option from the dashboard and clicks the "View Details" button for a specific P.O.
## **Actors:**
Buyer
Supplier
## **Preconditions:**
1. The Buyer or Supplier is logged into the system.
2. There are P.O Issues listed under the P.O Issues section.
3. The relevant P.O data, including missing items, payment details, and item details, is available in the system.
## **Postconditions:**
1. The Buyer views all details related to the selected P.O, including missing items, payment details, and item list.
2. The system updates the issue status if any changes or actions are taken on the P.O.
## **Normal Flow:**
1. The Buyer navigates to the P.O Issues section from the dashboard.
2. The Buyer identifies a specific P.O with issues and clicks the View Details button.
3. A pop-up appears displaying a message: "Two items are missing" along with P.O details, including:
- Delivery Date
- Ship to
- Payment Term
- Completed P.O
- Received Amount
- Note
4. The Buyer views the details of the missing items, categorized under:
- Missing Items
- Purchased Items
- Not Available Items
5. The Buyer clicks the Payment button to view the payment details, including:
- Subtotal
- Shipping Charges
- Loading Charges
- Total Amount
- Payment Made
- Amount Due
6. If the Buyer wishes to see the payment history, they click the Payment History button.
7. The Buyer clicks the Item List button to view details of all items, including:
- Missing Item Names
- Missing Item Quantities
- Purchased Items
- Not Available Items
## **Alternative Flow:**
### **Alternative Flow 1: Missing Data Issue**
1. If the system cannot retrieve all the details for the selected P.O:
- The system displays an error message: "Details are unavailable at this time. Please try again later."
- The Buyer is redirected back to the P.O Issues screen.
### **Alternative Flow 2: No Missing Items Found**
1. If the selected P.O does not have missing items, the pop-up displays a message: "All items delivered successfully."
2. The Buyer can still view payment details and the item list as usual.
