# User Management Screen

This document is a user specification outline for the user management scree.
This document outlines the user interface specification for the user management screen. This screen is used by administrators to manage the users of the application.

![alt text](http://url/to/img.png)

<!-- Requirements -->

## Requirements 

The user management screen should allow administrators to perform the following tasks:

*	View a list of all users.
*	Create a new user.
*	Edit an existing user.
*	Delete a user.
* Search for users by name or email address.

UI Components
The user management screen should contain the following UI components:
User List
The user list should display a table of all users, showing their name, email address, and role. Each row should also have buttons for editing and deleting the user.
Create/Edit User Form
The create/edit user form should contain the following fields:
•	First name (required)
•	Last name (required)
•	Email address (required, unique)
•	Password (required)
•	Role (required)
Search Bar
The search bar should allow administrators to search for users by name or email address.
Page Behavior
User List
When the page loads, the user list should display all users in the system. Administrators can click on the edit button to edit a user or the delete button to delete a user. When an administrator clicks the edit button, the create/edit user form should be displayed with the selected user's information pre-populated.
Create/Edit User Form
When the create/edit user form is displayed, the administrator can enter the user's information into the form fields. The administrator must fill out all required fields before submitting the form. If the email address entered is not unique, an error message should be displayed, and the form should not be submitted. If the form is successfully submitted, the user list should be updated with the new user or the edited user's information.
Search Bar
The search bar should allow administrators to search for users by name or email address. As the administrator types into the search bar, the user list should update to show only the users that match the search criteria.
Initial Display
When the user management screen is first displayed, the user list should show all users in the system. The create/edit user form and search bar should be hidden.
