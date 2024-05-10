# Web Application Login and Registration Test Plan

## Introduction

This document provides a comprehensive outline of the test scenarios for both the login and registration functionalities of the web application. It ensures that these processes are secure, efficient, and user-friendly.

## Test Cases with Testing Steps

### Login Functionality

#### TC1.7: Valid Login

**Objective**: Ensure users can log in with correct credentials.

- **Steps**:
  1. Go to the login page.
  2. Enter valid username and password.
  3. Click the login button.
- **Expected Result**: User is redirected to their dashboard.

#### TC1.10: Incorrect Password

**Objective**: Verify the system responds correctly to an incorrect password.

- **Steps**:
  1. Go to the login page.
  2. Enter valid username and an incorrect password.
  3. Click the login button.
- **Expected Result**: Error message stating incorrect password is displayed.

### Registration Functionality

#### TC1.1: Valid Registration

**Objective**: Ensure the system allows for the registration of new users with valid details.

- **Steps**:
  1. Go to the registration page.
  2. Enter valid username, email, and password.
  3. Submit the registration form.
- **Expected Result**: New user account is created, and confirmation is shown.

#### TC1.6: Duplicate Email

**Objective**: Confirm the system blocks registration attempts using an email already registered.

- **Steps**:
  1. Go to the registration page.
  2. Enter a username, an already registered email, and password.
  3. Submit the registration form.
- **Expected Result**: Error message stating email already in use is displayed.
