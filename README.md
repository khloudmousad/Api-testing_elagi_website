🔍 API Testing Project: Elagi Web Application (Postman)
Project Title: API Testing of Elagi — Online Pharmacy Platform
Tool Used: Postman
Type: RESTful API Testing


📝 Project Description:
The Elagi project involved comprehensive REST API testing of an online pharmacy web platform using Postman. The testing workflow focused on critical user journeys such as registration, login, browsing medicine categories, managing the cart and wishlist, user profiles, and feedback/contact functionalities.

🧪 Scope of Testing & Steps Involved:
🔐 1. User Authentication Flows
Register API:

Sent POST request with valid/invalid payloads to test user creation, email validation, and response codes.

Confirm Password / OTP API:

Validated user account confirmation endpoints using mock confirmation codes.

Login API:

Tested successful and failed login scenarios (wrong credentials, empty fields).

Reset Password API:

Verified email-triggered password reset with token and password update flow.

👤 2. User Profile Management
View Profile API:

Fetched user data using token-based authentication.

Update Profile API:

Sent PUT/PATCH requests to test field validations and update success messages.

💊 3. Product Browsing & Pagination
Medicine Categories & Details:

Performed GET requests to fetch categories, subcategories, and individual product data.

Pagination API Testing:

Validated page and limit query parameters for smooth UI integration.

💖 4. Wishlist & Favourites Management
Add/Remove Items:

Used POST/DELETE endpoints to simulate adding and removing items.

Clear All Items:

Triggered clear-all function and confirmed response codes and DB effects.

🛒 5. Cart Operations
Add to Cart API:

Verified correct item IDs, quantities, and cart totals after addition.

Update Quantity API:

Sent PUT requests to test cart quantity modifications.

Remove from Cart API:

Ensured deleted items were removed from the backend and UI reflected changes.

💬 6. Feedback & Contact Us
Feedback Submission API:

Tested form data submission, length validations, and confirmation messages.

Contact Us API:

Ensured data was stored correctly and auto-reply mechanism was triggered.



🛠️ Tools & Tech Used
Postman (Collections, Environments, Tests)

Manual mock data for edge-case validation

🎯 Outcome
Identified multiple backend bugs during early-stage API testing

Improved response handling logic for wishlist and cart endpoints

Helped streamline QA automation efforts by organizing collection-based testing flows

Increased test coverage for unauthenticated vs authenticated endpoints


This a video of the collection runnung on postman

https://github.com/user-attachments/assets/b46a469d-400e-4d85-8829-86ff52737b43

