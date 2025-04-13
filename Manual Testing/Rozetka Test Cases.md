## ✅ Test Cases

This section includes manual test cases for different functionalities on the [Rozetka](https://rozetka.com.ua/) website.

---

### 📝 Test Case 1: Registration with Valid Number

| Field            | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| **ID**           | 1                                                                           |
| **Name**         | Registration with valid number on Login form                                |
| **Description**  | Registration using a valid phone number: `+380683582944`                    |
| **Preconditions**| User is not logged in                                                       |
| **Steps**        | 1. Go to [https://rozetka.com.ua](https://rozetka.com.ua)  <br> 2. Click on "Personal Cabinet" icon  <br> 3. Select "Login with phone number" option  <br> 4. Enter `+380683582944` into the phone field  <br> 5. Click "Login" |
| **Expected Result** | User receives verification code and is successfully logged in            |
| **Actual Result**   | User receives verification code and is successfully logged in            |
| **Status**       | ✅ Passed                                                                    |

---

### 📝 Test Case 2: Go to Comparison from Main Page

| Field            | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| **ID**           | 2                                                                           |
| **Name**         | Go to comparison from main page                                             |
| **Description**  | Attempt to open the Comparison page from the main page as a guest user      |
| **Preconditions**| 1. User is not logged in  <br> 2. User is on the main page                  |
| **Steps**        | 1. Go to [https://rozetka.com.ua](https://rozetka.com.ua)  <br> 2. Click on the "Comparison" icon in the header |
| **Expected Result** | User is redirected to the Comparison page with empty state or message    |
| **Actual Result**   | No redirection occurs                                                     |
| **Status**       | ❌ Failed                                                                    |

---

### 📝 Test Case 3: Add Product to Cart as Guest

| Field            | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| **ID**           | 3                                                                           |
| **Name**         | Add product to cart as guest                                                |
| **Description**  | Adding a product to the cart without user authorization                     |
| **Preconditions**| User is not logged in                                                       |
| **Steps**        | 1. Go to [https://rozetka.com.ua](https://rozetka.com.ua)  <br> 2. Find product "iPhone 16" on the main page or via search  <br> 3. Click the "Cart" icon on the product card  <br> 4. Click on the "Cart" icon in the header to open the cart |
| **Expected Result** | The cart opens, and the added product is visible                         |
| **Actual Result**   | The cart opens, and the added product is visible                         |
| **Status**       | ✅ Passed                                                                    |
