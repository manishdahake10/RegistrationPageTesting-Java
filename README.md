# Register Page Testing

## Overview
This project is an **automation script** using **Selenium** and **TestNG** to test the registration functionality of a web page. It ensures that all input fields meet the required validation rules and verifies whether a verification email is sent successfully.

---
## 🛠 Testing Scope
### ✅ In Scope:
- Functional testing of the **registration process**, including:
  1. Verification of input field requirements:
     - First Name
     - Last Name
     - Email
     - Phone
     - Password
  2. Verification of email confirmation (ensuring the verification email is sent successfully).

### ❌ Out of Scope:
- Non-functional tests (Load Testing, Performance Testing, Security Testing, etc.).
- UI testing (visual design, CSS, layout validation).

---
## 🚀 How to Run the Project
### 1️⃣ Prerequisites:
- Install **Java** and **Eclipse IDE**.
- Install **TestNG** extension in Eclipse (available in the **Eclipse Marketplace**).
- Add **Selenium JARs** as external libraries to the project (JARs are available in the `selenium` folder).

### 2️⃣ Running the Tests:
- The **`NewTest`** class contains all the methods used to perform test cases.
- Run the project in **Eclipse** or via **Maven**.
- After successful execution, an **auto-generated test report** will be created at:
  - 📂 `test-output/index.html`
  - 📂 `test-output/emailable-report.html`

### 3️⃣ Re-running the Tests:
- The test can be executed **only once successfully** with the current test data.
- To re-run the test, update the **email IDs** used in all functions to avoid conflicts.

---
## 📂 Attached Reports
### ✅ Manual Testing Reports:
- 📋 **Test Cases Report** (Excel format)
- 🐞 **Bugs Report** (Excel format for manually detected defects)

### ✅ Automation Testing Reports:
- 📊 **Detailed Test Report** (`test-output/index.html`)
- ✅ **Summary Report** (`test-output/emailable-report.html`)

---
## 🎯 Key Benefits
✔ Ensures proper validation of **registration fields**.
✔ Automates **functional testing** for efficiency.
✔ Generates detailed test reports for analysis.
✔ Helps in **identifying defects early** in the development cycle.

---
### 📌 **Conclusion:**
This project is a comprehensive **automation testing suite** for validating the **register page functionality** using Selenium and TestNG. It covers both **manual and automated** test reports, ensuring high-quality test coverage. 🚀

---
### 📑 Author 
GitHub: [manishdahake10](https://github.com/manishdahake10) 

