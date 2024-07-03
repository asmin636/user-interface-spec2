# user-interface-spec2

UI Components
User List
Table: Displays users with the following columns:
User ID
Name
Email
Enabled Status

Checkbox: A checkbox labeled "Hide Disabled Users" to filter the user list.
Button: A button labeled "New User" to open the add user page.


Add New User Page
Form Fields:
Username (Text Input)
Display Name (Text Input)
Phone (Text Input)
Email (Text Input)
User Roles (Dropdown with options: Guest, Admin, SuperAdmin)
Enabled (Checkbox)
Button: A button labeled "Save User" to save the new user details.

Initial State
When the page loads:

Display the user list 
Show the "New User" button.
"Hide Disabled Users" checkbox is checked.

Component Behaviors
User List
Sorting: Clicking on column headers sorts the user list by that column.
Checkbox: Checking "Hide Disabled Users" filters the list to only show enabled users.
New User Button: Clicking the "New User" button navigates to the add new user page.

Add New User Page
Form Fields: Users can input their details into the respective fields.
Username: Required field for the username.
Display Name: Required field for the display name.
Phone: Optional field for the phone number.
Email: Required field for the email address.
User Roles: Dropdown to select the role (Guest, Admin, SuperAdmin).
Enabled: Checkbox to set the user's enabled status.
Save User Button: Validates inputs and saves the new user to the list. Redirects back to the user list on successful submission.
