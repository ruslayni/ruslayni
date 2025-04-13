# 🐞 Bug Reports: Rozetka

## ❗ Bug #1: No Redirection When Clicking "Comparison" as Guest

| Field             | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| **ID**            | 1                                                                    |
| **Title**         | No redirection when guest user clicks "Comparison" icon                     |
| **Environment**   | Windows 11, Google Chrome v123.0                                            |
| **Preconditions** | User is **not logged in**, user is on [Rozetka main page](https://rozetka.com.ua) |
| **Steps to Reproduce** | 1. Open main page <br> 2. Click on the "Comparison" icon in the header |
| **Expected Result** | User is redirected to "Comparison" page with a proper empty state message |
| **Actual Result**   | Nothing happens; user stays on the main page                              |
| **Severity**      | Major                                                                      |
| **Priority**        | Normal                                                                |
| **Attachments**   |                              |
| **Status**        | New                                                   |
---

## ❗ Bug #2: Phone Number Field Accepts More Than 10 Digits Visually

| Field             | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| **ID**            | 2                                                                     |
| **Title**         | Phone number input allows typing more than 10 digits visually               |
| **Environment**   | Windows 11, Chrome v123.0                                                   |
| **Preconditions** | Open login form with phone input                                            |
| **Steps to Reproduce** | 1. Go to login form <br> 2. Try entering a phone number like `+3809999999999` |
| **Expected Result** | Input field should block further input after 10 digits                    |
| **Actual Result**   | Visually allows typing more than 10 digits, though it may not submit      |
| **Severity**      | Trivial                                                                         |
| **Priority**        | Low                                                               |
| **Note**          | May be limited during form submission, but misleading for user input        |
| **Status**        | New                                                     |
---