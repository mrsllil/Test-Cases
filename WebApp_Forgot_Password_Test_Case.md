# WebApp Forgot Password Test Case

## Introduction

This test case aims to verify the functionality of the "Forgot Password" feature in the web application to ensure users can recover their passwords successfully.

## Test Case:

TC1.13.1 Forgot Password - Valid Email Submission

### Objective

Verify that a user can request a password reset link successfully using a registered email.

### Preconditions

- The user must have a previously registered email address with the system.
- The user is on the login page of the web application.

### Test Steps

1. Open a web browser and navigate to the web application's login page.
2. Click on the "Forgot Password" link.
3. Enter a valid registered email address in the designated field.
4. Click the submit button to send the password reset request.
5. Access the email account and look for the password reset email.
6. Verify that the email contains a password reset link and instructions on how to reset the password.

### Expected Results

- The user is redirected to a password reset page after submitting the email.
- The system sends a password reset email to the provided address within 5 minutes.
- The password reset email contains a valid link and clear instructions.

### Post-Conditions

- The user should be able to reset their password and regain access to their account.
