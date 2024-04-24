# QA Design Portfolio: Test Case Documentation

## Project Overview

**Project:** Mobile Application Testing (iOS & Android)

### Platform Support
The application is compatible with the following OS versions:
- **iOS:** Version 11 and higher
- **Android:** Version 5 and higher

### Design and Orientation
The application is available in portrait mode only on smartphones.

### Offline Management
The app does not support an offline mode. An error message is displayed if there is no connection at the startup of the app.

## Exercise

Prepare a comprehensive list of test cases to cover the scenarios, based on the provided information.

## User Stories

### [US 1.1] Sign In Form

**As a user,** I want to log into the application using my phone number and password.

#### Prerequisites
- The user has already registered an account within the application.

#### Description
The user inputs their phone number (including country code) and password to gain access to the application.

**Action Buttons:**
- **Log in:** Verifies the user's credentials and, if valid, navigates to the home screen. Displays an error message otherwise.
- **Forgotten Password:** Initiates the password retrieval process.

#### Acceptance Criteria
- The login screen allows the user to input their phone number and password.
- Submission is only possible with both the phone number and password fields filled.
- The phone number field accepts only numbers.
- The password must be at least 8 characters long.
- Upon clicking "Login":
  - With valid credentials: User is logged in and presented with the dashboard.
  - With invalid credentials: An error message is shown, and the login screen persists.
- Connection errors and other necessary error messages are displayed appropriately.

## Test Case List

- [TC 1.1.1] Sign in - Valid Login
Verify successful login with correct phone number and password.
- [TC 1.1.2] Sign in - Phone Number Field Empty
Check for error when the phone number field is left empty.
- [TC 1.1.3] Sign in - Password Field Empty
Check for error when the password field is left empty.
- [TC 1.1.4] Sign in - Incorrect Password
Validate the error message with an incorrect password that meets the character length
requirement.
- [TC 1.1.5] Sign in - Password Too Short
Ensure an error message is shown for a password shorter than 8 characters.
- [TC 1.1.6] Sign in - Invalid Phone Number
Confirm an error message for entering a phone number in an incorrect format.
- [TC 1.1.7] Sign in - Invalid Country Code
Verify that a validation error appears when a non-numeric country code is entered.
- [TC 1.1.8] Sign in - Login Without Internet
Confirm that the correct error message appears when attempting to log in without internet
access.
- [TC 1.1.9] Sign in - Forgotten Password Function
Test the initiation and user flow of the 'Forgotten Password' recovery process.
- [TC 1.1.10] Sign in - Field Input Validation
Enter various invalid inputs in both fields (e.g., special characters, incorrect digit counts) to
verify that each invalid input triggers the appropriate error message.
- [TC 1.1.11] Sign in - Orientation Lock
Rotate the device to landscape mode to confirm that the app remains in portrait orientation.
- [TC 1.1.12] Sign in - UI/UX Consistency Across Devices
Verify that the login screen's UI elements are consistent and fully functional across different
devices with varying screen sizes.
- [TC 1.1.13] Sign in - Handling 503 Service Unavailable Error
Verify that the application appropriately handles and displays a message when a 503 Service
Unavailable error occurs during the login process. The application should display a user-friendly
error message indicating that the service is temporarily unavailable, rather than a generic error
message or no response at all.

## Device Selection for Testing

**High-End Devices:**
- iPhone 13/14 Pro (iOS 15/16)
- Samsung Galaxy S22 (Android 12)

**Mid-Range Devices:**
- iPhone SE (2020) with the latest supported iOS version
- Samsung Galaxy A52 (Android 11)
- Google Pixel 5a (Android 11)

**Older Devices:**
- iPhone 6S (last compatible with iOS 15)
- Samsung Galaxy S7 (Android 8.0)

The selection spans across high-performance hardware to older models to ensure compatibility and smooth operation across a spectrum of devices.