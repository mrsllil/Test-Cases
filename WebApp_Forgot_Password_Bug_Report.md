# WebApp Forgot Password Bug Report

## Bug Report:

#### [Forgot Password] Button Redirects to 404 Error Page

### Description

Users attempting to reset their passwords are redirected to a "404 Not Found" error page instead of the password reset form when they click on the password reset link in their email.

### Steps to Reproduce

1. Navigate to the login page of the web application.
2. Click on 'Forgot Password'.
3. Enter a registered email and submit.
4. Access the email account and click on the password reset link provided in the email.

### Expected Result

The user should be redirected to a page where they can enter a new password.

### Actual Result

The user is redirected to a "404 Not Found" error page.

### Environment

- Browser: Chrome v100.0
- Operating System: Windows 10

### Severity

High - prevents users from resetting their passwords, which is critical for user access and security.

### Priority

Urgent - needs immediate attention to restore functionality for users trying to reset their passwords.
