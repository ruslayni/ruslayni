## 📋 Check List: Login Functionality

This checklist covers login functionality tests for the [Rozetka](https://rozetka.com.ua/) platform.

### 🔐 Login form

| Name                                      | Status | Test Info + Comments                                         |
|-------------------------------------------|--------|--------------------------------------------------------------|
| Login with valid phone number             | Passed | num: +380683582944                                           |
| Receiving pass-code after typing number   | Passed | Code input appears after number input                        |
| Login with invalid phone number           | Passed | num: +3809999999999 (input is limited to 10 digits)         |
| Login with short phone number             | Passed | num: +38068 (error is shown)                                 |
| Show error when typing invalid number     | Passed | num: +380702029321 (validation triggered)                    |
| Login with valid email                    | Passed | email: ruslan.efimkin.school@gmail.com                       |
| Login with invalid email (wrong format)   | Passed | email: test@@gmail (error is shown)                          |
| Show error when typing invalid email      | Passed | email: testgmail.com (validation triggered)                  |
