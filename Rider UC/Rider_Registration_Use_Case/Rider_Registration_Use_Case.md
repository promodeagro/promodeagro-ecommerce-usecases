# **Use Case Document for Rider Registration**
## **Use Case Name:**
Rider Registration
## **Use Case Description:**
This use case allows a new rider to register on the application by completing a 4-step verification process that involves entering personal details, bank details, uploading necessary documents, and reviewing the information for submission. Upon submission, the system displays the application status.
## **Actor:**
Rider
## **Trigger Point:**
The rider chooses to register on the platform by clicking the "Register" option on the login screen.
## **Preconditions:**
1. The rider has downloaded the application.

2. The rider has access to the required personal, bank, and document details.

3. A stable internet connection is available.
## **Postconditions:**
1. The rider's application status is updated to "Under Verification."

2. The rider receives confirmation of their application submission.
## **Normal Flow:**
1. Step 1: Personal Details

- The rider enters personal information, including:
- Full Name, Date of Birth, Mobile Number, Email ID.
- Address details: Address Line, Landmark, City, State, Pincode.
- Reference Contact: Relation, Mobile Number.
- Rider clicks "Next" to proceed.

2. Step 2: Bank Details

- The rider provides bank details:
- Select Bank, Account Number, Re-enter Account Number, IFSC Code.
- Rider clicks "Next" to proceed.

3. Step 3: Document Upload

- The rider uploads necessary documents:
- User Photo, Aadhaar (Front and Back), PAN Card, Driving License (Front and Back), Vehicle Image, RC Book (Front and Back).
- Rider clicks "Next" to proceed.

4. Step 4: Review and Submit

- The system displays all the entered information for review.
- The rider verifies the details and clicks "Submit."

5. Post Submission:

- The system confirms that the application has been submitted.
- Application status changes to: "Your application is under verification. We will update once it is verified."
## **Alternative Flow:**
1. If the rider provides invalid data at any step:

 - The system displays a validation error message (e.g., "Invalid Account Number" or "Invalid Document Format").
 - The rider must correct the information to proceed.

2. If the internet connection is lost during registration:

 - The system displays an error message: "Network connection lost. Please try again."
 - The rider retries after restoring the connection.

3. If required documents are not uploaded:

 - The system prompts: "Please upload all mandatory documents to proceed."
 - The rider uploads the missing documents to continue.

4. If the rider cancels registration at any step:

 - The system asks for confirmation before exiting.
 - No information is saved unless explicitly confirmed.
