# User Management Screen UI Specification
## Requirements

The User Management Screen is a web-based user interface that allows authorized users to manage users of the application. The following requirements have been identified for this screen:

The user should be able to view a list of all users currently registered in the application.
The user should be able to add a new user to the application.
The user should be able to edit the details of an existing user.
The user should be able to disable or enable a user account.
The user should be able to hide disabled users from the list of users.
The user should be able to save changes made to a user account.

## User Interface Components

The following UI components are required for the User Management Screen:

- **New User** button: Clicking this button should display a form to add a new user to the application.

- **Hide Disabled User** checkbox: Checking this checkbox should hide disabled users from the list of users.

- **Save User** button: Clicking this button should save changes made to a user account.

- **User** table: A table that displays a list of all users registered in the application. Each row of the table should display the following information for a user:

  - **ID**: A unique identifier for the user.

  - **User Name**: The username of the user.

  - **Email**: The email address of the user.

  - **Enabled**: A checkbox that indicates whether the user account is enabled or disabled.

  - **Edit button**: Clicking this button should display a form to edit the details of the user.

The form for adding or editing a user should include the following fields:

- **Username**: A field for entering the username of the user.

- **Display Name**: A field for entering the display name of the user.

- **Phone**: A field for entering the phone number of the user.

- **Email**: A field for entering the email address of the user.

- **User Roles**: A dropdown list of user roles that the user can be assigned to.

- **Enabled** checkbox: A checkbox that indicates whether the user account is enabled or disabled.

## User Interface Behavior

When the User Management Screen is first loaded, the table of users should be displayed with all users visible, and the Hide Disabled User checkbox should be unchecked by default.

Clicking the New User button should display a form to add a new user to the application. The user should be required to fill out all fields in the form, and should not be allowed to submit the form until all required fields are filled out.

Clicking the Edit button in a user row should display a form to edit the details of the user. The form should be pre-populated with the current details of the user, and the user should be able to make changes to any of the fields.

Clicking the Save User button should save changes made to a user account. If a new user is being added, the user account should be created with the details entered in the form.

Checking the Hide Disabled User checkbox should hide disabled users from the list of users. Unchecking the checkbox should display all users again.

## Initial View

The initial view of the User Management Screen should display the table of users with all users visible, the Hide Disabled User checkbox unchecked, and the New User button visible. The table should display the ID, User Name, Email, Enabled checkbox, and Edit button for each user.

The form for adding a new user should be hidden initially, and should only be displayed when the user clicks the New User button.
