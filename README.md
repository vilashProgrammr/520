# Materials Login and Registration


## Task1
- 1.) Implement a custom validator in Angular for checking passwords to haveatleast one uppercase, one lowercase, one digit, one symbol and should be between 7 - 12 characters in length.
- 2.) Only on login, allow users to redirect to Users page. Implement Angular authguard to have a role check to make sure only authenticated users are accessing Users page else redirect to Access Denied Page.
- 3.) Implement Pagination logic for users listing page.

## Task2
- 1.) Create a User Registration form which allows users to register new account.
Use the same below API which is used for Login. Please refer the documentation: https://reqres.in/
- 2.) The Registration form should have below form fields:-
  - i.) Email
  - ii.) Full Name
  - iii.) Password
  - iv.) Confirm Password.
- 3.) Prevent form submission if below validation rules are not satisfied:-
  - i.) Email should be valid.
  - ii.) Full Name should have atleast 5 characters and should not start with a number or symbols.
  - iii.) Password should have atleast one uppercase, one lowercase, one digit, one symbol and should be between 7 - 12 characters in length.
  - iv.) Confirm Password value should be the same as Password field value. Create a custom angular validator to check the mentioned condition.
- 4.) Show suitable alert messages on form submission status.
