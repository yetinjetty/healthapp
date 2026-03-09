Sprint 1 Test Summary

Validation objective:

- To ensure that user requirement is reflected in the design.
- To ensure that user interface and layout is clear and intuitive.
- To verify that navigation flow and logical sequence is valid.
- To identify issues of design and gather feedback for improvement in Sprint 2.

Validation approach:

- Usability review
- Navigation flow review
- UI Layout review

Test participants:

| **Name** | **Role** | **User ID** |
| --- | --- | --- |
| Justin Tan Jiing Wen | Student | 1   |
| Tan Joon Boon | Student | 2   |
| Nikhil Purlackee | Student | 3   |

Test Scenario:

<div class="joplin-table-wrapper"><table><tbody><tr><th><p><strong>User ID</strong></p></th><th><p><strong>Task</strong></p></th><th><p><strong>Context</strong></p></th><th><p><strong>UI Flow</strong></p></th><th><p><strong>Issue</strong></p></th><th><p><strong>Results</strong></p></th><th><p><strong>Test Scenario</strong></p></th></tr><tr><td><p>1</p></td><td><p>Login</p></td><td><p>The user is given instructions to login without registering an account</p></td><td><ol><li>View login page</li><li>Enter account details</li><li>Press login button</li></ol></td><td><p>-</p></td><td><p>User cannot login without creating an account, notification pops up</p></td><td><p>User is given the task to view the login page, and try to login without creating an account, explaining what they can observe</p></td></tr><tr><td><p>1</p></td><td><p>Register account and login</p></td><td><p>The user is given instructions to register account and login</p></td><td><ol><li>View login page</li><li>Click on register account button</li><li>Fill in registration details</li><li>Click on Sign Up button</li></ol></td><td><p>-</p></td><td><p>User registers for a new account</p></td><td><p>User is given the task to register a new account, explaining their thought process throughout the registration process</p></td></tr><tr><td><p>2</p></td><td><p>Register account and login</p></td><td><p>The user is given instructions to login and register an account</p></td><td><ol><li>View login page</li><li>Click on register account button</li><li>Fill in registration details</li><li>Click on Sign Up button</li></ol></td><td><p>-</p></td><td><p>User registers for a new account</p></td><td><p>User is given the task to register a new account, explaining their thought process throughout the registration process</p></td></tr><tr><td><p>2</p></td><td><p>Reset password</p></td><td><p>The user is given instructions to reset account's password</p></td><td><ol><li>View login page</li><li>Click on Forgot Password button</li><li>Enter recovery email</li><li>Click on Send Recovery Email button</li><li>Enter New Password</li><li>Click on Reset Password button</li></ol></td><td><p>UI layout is slightly misleading, instead of account recovery it should be password recovery as the headline of the page</p></td><td><p>User is able to reset their password</p></td><td><p>User is given the task to reset their password for the account that was created, explaining their thought process throughout the process</p></td></tr><tr><td><p>3</p></td><td><p>Register account and login</p></td><td><p>The user is given instructions to login and register and account</p></td><td><ol><li>View login page</li><li>Click on register account button</li><li>Fill in registration details</li></ol><p>Click on Sign Up button</p></td><td><p>-</p></td><td><p>User registers for a new account</p></td><td><p>User is given the task to register a new account, explaining their thought process throughout the registration process</p></td></tr><tr><td><p>3</p></td><td><p>Navigate menu</p></td><td><p>The user is given instructions to navigate through the application menu</p></td><td><ol><li>View main dashboard page</li><li>Click on the menu bar button for each page</li><li>View all pages</li></ol></td><td><p>No return button, unable to proceed after clicking the "add new record" page</p></td><td><p>User is able to view the main dashboard page, click on the buttons, view the "add new record" page, but unable to return to the main dashboard to view the other page</p></td><td><p>User is given the task to view the main dashboard page, then click on any of the buttons located on the menu bar, view the "add new record" page, explaining their thought process throughout the process</p></td></tr></tbody></table></div>

Feedback:

| User ID | Task | Issues | Test Scenario | Suggested Improvement |
| --- | --- | --- | --- | --- |
| 1   | Login account | \-  | \-  | \-  |
| 1   | Register account | \-  | \-  | \-  |
| 2   | Register account and login | \-  | \-  | \-  |
| 2   | Reset password | UI slightly misleading | User is given the task to reset their password for the account that was created, explaining their thought process throughout the process | Change "Account Recovery" to "Password Recovery" |
| 3   | Register account and login | \-  | \-  | \-  |
| 3   | Navigate application menu | No return button, unable to view other pages | User is given the task to view the main dashboard page, then click on any of the buttons located on the menu bar, view the "add new record" page, explaining their thought process throughout the process | Add a return button |

Validation Scope:

- In scope
  - Usability - evaluate intuitive of UI
  - Navigation flow - evaluate logical structure of UI
  - UI elements - evaluate on screen layout and the consistency of UI elements
  - Labelling - evaluate on correctness of labels of UI elements
- Out of scope
  - Field input validation - user cannot input data in field in wireframe
  - Backend operation - no logical operations in wireframe
  - Performance review - no performance testing in wireframe
  - Functionality - no functionality in wireframe

Validation outcome:

| **Task** | **Observed outcome** | **Suggested Improvement** |
| --- | --- | --- |
| Login | User able to understand login page, recognize elements, explain functionality process | UI layout design could be improved, allow more login options |
| Register account | User able to understand register account page, recognize elements, explain functionality process | UI layout design could be improved, allow more registration options |
| Reset Password | User able to understand reset password page, recognize elements, explain functionality process | UI layout design could be improved, page headline could be more intuitive, from "Account Recovery" to "Password Recovery" |
| Menu navigation | User able to navigate through menu, recognize elements, explain functionality process | UI layout design could be improved, add a return button to return to the main dashboard for further navigation |
| Navigation flow | User able to conceptually follow flow of task sequence | Minor adjustment |
