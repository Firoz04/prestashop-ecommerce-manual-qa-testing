# PrestaShop E-commerce Manual QA Testing

A comprehensive **Manual Software Testing project** performed on the **PrestaShop Demo e-commerce platform**. This project demonstrates a complete QA workflow covering requirement analysis, test case design, test execution, defect reporting, UI testing, API validation, and end-to-end testing.

## 🌐 Application Under Test

[**PrestaShop Demo**](https://demo.prestashop.com/#/en/front)

- Application Type: E-commerce Web Application
- Testing Approach: Manual Testing
## 🎯 Project Objective

The objective of this project is to validate the functionality, usability, reliability, and overall quality of the PrestaShop e-commerce application through a structured manual QA process.

The project follows a practical QA workflow from **requirement analysis to test execution, defect reporting, and final testing analysis**.

## 📋 Project Overview

The project is divided into five major sections:

**Q1 – Manual Testing of Customer Login (Sign In) Module**

A complete manual testing cycle was performed for the Customer Login functionality.

Activities included:

- Test Case Design
- Test Execution
- Defect Identification
- Defect Reporting
- Evidence Collection
- Test Summary
  
**Q2 – Requirement Analysis**

Requirement clarification questions were prepared from a QA Engineer's perspective.

The analysis focuses on:

- Search requirements
- Filter requirements
- Sort requirements
- User experience

Questions are prioritized from **High to Low**.

**Q3 – Test Case Design**

Detailed manual test cases were designed for:

- Search
- Filter
- Sort
- Cart
- Checkout

Each test case includes relevant QA attributes such as:

- Test Case ID
- Test Scenario
- Priority
- Preconditions
- Test Data
- Test Steps
- Expected Result

**Q4 – Test Execution & Defect Reporting**

The designed test cases were executed against the application.

Testing activities included:

- Test Case Execution
- Actual Result Documentation
- Pass/Fail Status
- Defect Identification
- Severity & Priority Assignment
- Defect Reporting
- Defect Evidence Collection

**Q5 – End-to-End Testing (UI + API + Analysis)**

A complete happy-path e-commerce journey was tested:

```text
Search Product
      ↓
Apply Price Filter
      ↓
Apply Category Filter
      ↓
Sort Low → High
      ↓
Add 2 Products to Cart
      ↓
Proceed to Checkout
```
The end-to-end flow includes:

- UI Testing
- API Testing using **Postman**
- Defect Analysis
- Evidence Collection

## 📁 Repository Structure

```text
prestashop-ecommerce-manual-qa-testing/
│
├── 01_Customer_Login_Module/
│   ├── Customer Login (Sign In)_Test Case Design.xlsx 
│   ├── Customer Login (Sign In)Test_Case_Execution.xlsx
│   ├── Defect Report.docx
│   ├── Defect Report.pdf
│   └── Defect/
│
├── 02_Requirement_Analysis/
│   └── Requirement_Analysis.pdf
│
├── 03_Test_Case_Design/
│   └── Search_Filter_Sort_Cart_Checkout_Test_Case_Design.xlsx
│
├── 04_Test_Execution_and_Defect_Reporting/
│   ├── Test_Case_Execution_Report.xlsx
│   ├── Defect_Report.docx
│   ├── Defect_Report.pdf
│   └── Defect_Evidence/
│
├── 05_End_to_End_Testing/
│   ├── UI_Test_&_API_Test_Report.docx
│   ├── UI_Test_&_API_Test_Report.pdf
│   ├── Postman_Collection.json
│   └── Evidence/
│
├── Manual QA Assessment.pdf
└── README.md
```
## 👤 Author

Md. Firoz Hasan  
GitHub: [Firoz04](https://github.com/Firoz04)
