# User Management Screen

This document is a user specification outline for the user management screen below:

![alt text](h.png)

This screen is used by administrators to manage the users of the application.

<!-- Requirements -->
## Requirements 

The user management screen should allow administrators to perform the following tasks:

  <ol>
    <li>
     View a list of all users
      <ul>
        <li>Users can be viewed and sorted based on: ID, User Name, Email, or Enabled functionality</li>
      </ul>
            <ul>
        <li>Hide disabled users</li>
      </ul>
    </li><br/>
  <li>
  Create new user
  <ul>
  <li> Fill the user's information: username, display name, phone number, user email, user role</li>
  </ul>
    <ul> 
  <li> Enable or disable user</li>
  </ul> <br/>
  
   <li>
  Assign roles to user using Dropdown menu
  <ul>
  <li>Assign Guest</li>
  </ul>
    <ul>
  <li>Assign Admin</li>
  </ul>
    <ul>
  <li>Assign SuperAdmin</li>
  </ul> <br/>
  
 <li>
  Save user
  <ul>
  <li>Save the user's data in the system's database</li>
  </ul>

  
<!-- UI Components -->
## UI Components

The user management screen should contain the following UI components:
<ol>
    <li>
    User List
    
* The User List displays a table of all users, showing their ID, username, email address, and whether the user is enabled or not in separate columns.
* If user is enabled, the value of the Enabled box is "True"
* Each colum can be filtered by the administrators.
    
<br/>

<li>
Create/Edit User Form ( When administrators click New User Button, the form pops up)
    
The Create/Edit User Form should contain the following fields:
 * Input type text for Username 
 * Input type text for Display Name 
 * Input type number for Phone 
 * Input type text for Email 
 * Checkbox titled "Enabled" for enabling users
 * Dropdown menu for User Roles

  One User Role may be assigned to each user.
  
 The User Roles are:
  <ul>
  <li>Guest</li>
  </ul>
    <ul>
  <li>Admin</li>
  </ul>
    <ul>
  <li>SuperAdmin</li>
  </ul><br/>
  
<li>
Hide Disabled User checkbox. When clicked, disabled users are hidden for the users list.

<li>
Save User button. When clicked, a user's data is saved.
  
  
<!-- Page Behavior-->
## Page Behavior 

### Inital Display - User List 
When the page loads, the user list should display all users in the system. Administrators can click on the hide disabled user checkbox in order to view only the enabled users in the system. Administrators can click the Create new user button, a form should be displayed to fill in the new user's information.

### Create New User Form
When the new user form is displayed, the administrators can now fill in the form fileds with the user's information. The administrator may enable the user by clicking on the "Enable" checkbox. Additionally, the administrators may save the user created in the system by clicking the "Save User" button.




 
  
  
  
  
  
  
  
  
  
  
  
  

   
 

