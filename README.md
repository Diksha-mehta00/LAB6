# LAB6Generative-AI-in-Aviation-Day-6
Day 6 lab exploring AI security and privacy, PII-safe prompting, data minimisation, sensitive information classification, privacy risks, verification, and responsible GenAI use in aviation.

GenAI Business Portfolio — Day 6
Security and Privacy Audit: PII-Safe Prompting
This repository contains Day 6 of the Generative AI in Aviation lab portfolio.

Lab Focus
Personally Identifiable Information (PII)
Sensitive identity, medical and financial information
Data minimisation
Safe placeholders
Privacy-safe prompt design
Unsupported commitments and policy claims
Information-sensitivity classification
PII detection
Security-audit checklist
Human review and authorised-system verification
Repository Structure
genai-business-portfolio/ │ └── day-06-security-and-privacy/ │ └── security-and-privacy-audit.md

Important Privacy Rule
Do not upload real passenger names, contact details, passport/Aadhaar numbers, booking references, payment information, medical information, passwords, credentials, or confidential operational information to a public AI tool or public GitHub repository.

All examples in this submission are redacted or represented with placeholders.

Lab Objective
The objective of this lab is to identify privacy and accuracy risks in aviation-related AI prompts and redesign them using:

Data minimisation
Placeholders
Redaction
Verification instructions
Human review
Authorised organisational systems
Unsafe Prompt Analysis
The original scenario contained sensitive passenger information. The actual personal information has been removed from this repository.

Main Risks
Information	Risk	Safe Action
Passenger name	Personal information	Use [PASSENGER NAME]
Passport number	Sensitive identity information	Remove completely
Government identity number	Sensitive identity information	Remove completely
Mobile number	Contact information	Remove or use placeholder
Email address	Contact information	Remove or use placeholder
Booking reference	Travel/account information	Use [BOOKING REFERENCE]
Flight number	Travel information	Use [FLIGHT NUMBER]
Travel date	Travel information	Use [TRAVEL DATE]
Medical information	Sensitive personal information	Remove/minimise
Payment information	Financial information	Remove
Fixed delivery promise	Unsupported commitment	Verify before stating
Fixed compensation	Unsupported policy claim	Verify airline policy
Key Privacy Lesson
A safe AI prompt should contain only the information necessary to draft the communication, use placeholders for personal details, and avoid commitments that have not been verified.

Safe Placeholders
[PASSENGER NAME]
[PASSPORT NUMBER REMOVED]
[IDENTITY NUMBER REMOVED]
[MOBILE NUMBER REMOVED]
[EMAIL ADDRESS REMOVED]
[BOOKING REFERENCE]
[FLIGHT NUMBER]
[TRAVEL DATE]
[FLIGHT ROUTE]
[SENSITIVE MEDICAL INFORMATION REMOVED]
[PAYMENT INFORMATION REMOVED]
[VERIFY AIRLINE POLICY]
[VERIFY BAGGAGE STATUS]
Safe Prompt
Draft a professional email to [PASSENGER NAME] regarding delayed checked baggage connected with booking reference [BOOKING REFERENCE] and Flight [FLIGHT NUMBER]. Acknowledge the inconvenience and ask the passenger to use the airline’s authorised customer-service channel to check the baggage status. Do not include passport, government identity, mobile, email, medical or payment information. Do not promise a delivery timeline or compensation. Where policy or status information is required, insert [VERIFY WITH AUTHORISED AIRLINE SYSTEM]. Keep the email below 120 words.

Safe AI-Generated Output
Dear [PASSENGER NAME],

We sincerely apologise for the inconvenience caused by the delay in your checked baggage connected with booking reference [BOOKING REFERENCE] and Flight [FLIGHT NUMBER].

Please use the airline’s authorised customer-service channel to check the latest baggage status. For the most accurate information regarding the current status, next steps, or any applicable assistance, please refer to [VERIFY WITH AUTHORISED AIRLINE SYSTEM].

We appreciate your patience and understanding while the matter is being addressed.

Kind regards,
Customer Service Team

Unsafe vs Safe Prompt
Criterion	Unsafe Prompt	Safe Prompt
Passenger identity	Real identifying information	Placeholders
Travel/account information	Specific personal data	Placeholders
Medical information	Included	Removed
Financial information	Included	Removed
Unsupported promises	Included	Verification required
Placeholders	No	Yes
Verification instruction	No	Yes
Public AI suitability	Unsafe	Safer
Information-Sensitivity Classification
Information	Classification
Published airline advertisement	Public
Public airport address	Public
General flight schedule	Public
Internal staff-training schedule	Internal
Unpublished passenger-satisfaction report	Confidential
Passenger booking reference	Confidential
Passport number	Restricted / highly sensitive
Payment-card information	Restricted / highly sensitive
Employee login password	Restricted / highly sensitive
Airport security procedure	Confidential
Public baggage-policy page	Public
Passenger medical-assistance request	Restricted / highly sensitive
When uncertain about classification, do not upload the information to a public AI tool.

PII Detection Challenge
Scenario A — Flight Cancellation
Sensitive information:

Passenger name
Mobile number
Booking reference
Safe placeholders:

[PASSENGER NAME]
[MOBILE NUMBER REMOVED]
[BOOKING REFERENCE]
Safety action: Remove real contact and booking details and use an authorised airline channel for verification.

Scenario B — Special Assistance
Sensitive information:

Passenger name
Medical information
Flight information
Safe placeholders:

[PASSENGER NAME]
[MEDICAL INFORMATION REMOVED]
[FLIGHT NUMBER]
Safety action: Remove medical details unless strictly necessary and verify assistance arrangements through an authorised system.

Scenario C — Employee Report
Sensitive information:

Employee name
Employee ID
Password
Internal security information
Safe placeholders:

[EMPLOYEE NAME]
[EMPLOYEE ID REMOVED]
[PASSWORD REMOVED]
Safety action: Never share passwords. Use authorised IT/security channels.

Scenario D — Payment Complaint
Sensitive information:

Passenger name
Payment information
Booking reference
Safe placeholders:

[PASSENGER NAME]
[PAYMENT INFORMATION REMOVED]
[BOOKING REFERENCE]
Safety action: Remove payment and banking information and use an authorised secure payment/refund channel.

Four Safe Rewritten Prompts
Scenario A — Flight Cancellation
Draft a professional flight-cancellation email to [PASSENGER NAME] regarding [GENERAL FLIGHT CANCELLATION ISSUE]. Use placeholders for all identifying information. Do not include or request sensitive personal information. Refer the passenger to an authorised airline channel to verify the cancellation status, available options and applicable policy.

Scenario B — Special Assistance
Draft a professional special-assistance communication for [PASSENGER NAME] regarding [GENERAL SPECIAL-ASSISTANCE REQUEST]. Do not include medical details or other sensitive personal information. Use placeholders for identifying information and refer the passenger to an authorised airline channel for verification of assistance arrangements.

Scenario C — Employee Report
Draft a professional internal incident-report acknowledgement for [EMPLOYEE NAME] regarding [GENERAL SECURITY-ACCESS ISSUE]. Do not include passwords, credentials or other confidential authentication information. Use placeholders for identifying information and direct the employee to the authorised internal security or IT channel for verification and resolution.

Scenario D — Payment Complaint
Draft a professional response to [PASSENGER NAME] regarding [GENERAL REFUND ENQUIRY]. Do not include or request full card numbers, bank details or other sensitive financial information. Use placeholders for identifying information and refer the passenger to the authorised secure payment/refund channel for verification.

Security Audit Checklist
 No real passenger name
 No phone number
 No email address
 No passport/Aadhaar number
 No booking reference
 No payment information
 No medical information
 No employee credentials
 No confidential operational information
 Sensitive details replaced with placeholders
 Data minimisation applied
 Verification instruction included
 Human review required
Data Minimisation
Unnecessary Information
Passenger age, home address, passport number and mobile number are unnecessary for a general aviation communication draft.

Why Minimisation Reduces Risk
A minimised prompt reduces the amount of personal information exposed to an AI tool while still providing enough context to create the required communication.

Minimum Information Required
The minimum information is:

General issue
Intended recipient placeholder
Communication purpose
Desired tone
Information Added Later
Verified passenger, booking, flight-status, policy, compensation and other case-specific information should be retrieved or confirmed through an authorised organisational system.

My Privacy-Safe Aviation Prompt
Selected Situation
Baggage-delay response

Unsafe Prompt Pattern
Draft an email to a passenger using their real name, booking details, contact details, medical information and payment information about delayed baggage.

PII Identified
Passenger name
Booking reference
Contact details
Medical information
Payment information
Placeholders
[PASSENGER NAME]
[BOOKING REFERENCE]
[FLIGHT NUMBER]
[SENSITIVE MEDICAL INFORMATION REMOVED]
[PAYMENT INFORMATION REMOVED]
Safe Prompt
Draft a professional baggage-delay response to [PASSENGER NAME] regarding booking reference [BOOKING REFERENCE] and Flight [FLIGHT NUMBER]. Acknowledge the inconvenience and direct the passenger to the airline’s authorised customer-service channel for baggage-status verification. Do not include personal identity numbers, contact details, medical information or payment information. Do not promise compensation or a delivery timeline.

Verification
[VERIFY WITH AUTHORISED AIRLINE SYSTEM]

Human Review
A human reviewer must verify baggage status, applicable policy and any commitments before the message is sent.

Reflection
1. What is PII?
PII is information that can identify a person directly or when combined with other information.

2. Five Examples of Sensitive Aviation Information
Passport numbers
Government identity numbers
Payment-card information
Medical-assistance information
Employee passwords or credentials
3. Why Protect Booking References?
Booking references are connected to passenger travel accounts and can become more identifying when combined with other travel details.

4. Purpose of a Placeholder
A placeholder replaces real information with a neutral label so a task can be completed without exposing actual personal or confidential information.

5. What is Data Minimisation?
Data minimisation means providing only the information necessary to complete a task and excluding unnecessary personal or confidential information.

6. Why is Medical Information Sensitive?
Medical information relates to a person's health and can reveal private information about their condition or assistance needs.

7. What if Information May Be Confidential?
Do not upload it to a public AI tool. Check the organisation's information-security policy or ask an authorised supervisor.

8. Why Should Passwords Never Be Entered into AI Tools?
Passwords are authentication credentials. Exposing them could allow unauthorised access to systems or accounts.

9. Why is Human Review Required?
Human review checks:

Accuracy
Policy compliance
Confidentiality
Context
Unsupported commitments
10. What Was Changed?
Real personal and sensitive information was removed, necessary details were replaced with placeholders, data minimisation was applied, unsupported promises were avoided, and a verification instruction was added.

AI Usage Declaration
ChatGPT and/or Google Gemini were used only after personal and confidential information was removed or replaced with placeholders.

The privacy audit, output review and reflection were independently completed.

GitHub Upload Checklist
Before uploading, confirm that the repository does not contain:

Real passenger names
Phone numbers
Email addresses
Passport or Aadhaar numbers
Booking references
Payment information
Medical information
Employee credentials
Confidential operational information
Submission Details
Repository: genai-business-portfolio

Folder: day-06-security-and-privacy

File: security-and-privacy-audit.md

Suggested commit message:

Add Day 6 Lab 6 - Security and Privacy Audit

Expected Submission
Redacted unsafe-prompt analysis
Privacy-risk table
Placeholder table
Safe prompt and AI-generated output
Unsafe-versus-safe comparison
Information-sensitivity classification
PII-detection challenge
Four safe rewritten prompts
Security-audit checklist
Data-minimisation activity
Original privacy-safe aviation prompt
Reflection answers
GitHub file link
Final Takeaway
Privacy-safe GenAI use in aviation requires:

Data minimisation
Redaction
Safe placeholders
Authorised-system verification
Human review
AI should receive only the minimum information needed for the task. Passenger-specific status, policy, compensation and operational details should be verified through authorised systems before final communication or operational use.
