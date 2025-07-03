# AutomationExercise.com – QA Validation Project

## 📌 Project Overview
This project presents a complete Quality Assurance (QA) validation of the eCommerce platform [AutomationExercise.com](https://automationexercise.com/). It covers **Functional Testing**, **API Testing**, **Performance Testing**, **Database Testing**, and **Automation using Selenium**.

---

## 📋 Traceability Matrix
- **Project Name:** AutomationExercise.com QA Validation  
- **Test Lead:** Nafis Ulfat  
- **Execution Time:** 3 Days  
- **Environment:** Web (Live Production Clone)  
- **Total Requirements:** 13 (REQ-001 to REQ-013)  
- **Test Types:** Functional, API, Performance, Database  

---

## ✅ Test Summary

### 🔹 Functional Test Cases
- **Total:** 26  
- **Coverage:** Registration, Login, Product Browsing, Cart, Checkout, Subscription, Contact Form, Scroll, Invoice, Navigation  
- **Result:** ✅ All Passed

### 🔹 API Test Cases
- **Total:** 14  
- **Endpoints Tested:**  
  `/api/productsList`, `/api/brandsList`, `/api/searchProduct`, `/api/verifyLogin`, `/api/createAccount`, etc.  
- **Methods:** GET, POST, PUT, DELETE  
- **Result:** ✅ All Passed  

### 🔹 Performance Test Cases
- **Total:** 10  
- **Tools Used:** Apache JMeter  
- **Types:** Load, Stress, Spike, Soak Tests  
- **Result:** 7 Passed, ❌ 3 Failed  
- **Bugs Identified:**
  - `BUG_001`: 503 error under load on product list
  - `BUG_002`: Login API >10s delay under spike load
  - `BUG_003`: 520/522 errors during account creation

### 🔹 Database Test Cases
- **Total:** 12  
- **Focus:** User registration, cart updates, order records, DB-API consistency  
- **SQL Queries:** Included  
- **Result:** ✅ All Passed

---

## 🤖 Selenium Automation (Python)
**Automated Scenarios:**
- User Registration  
- Valid & Invalid Login  
- Logout  
- Contact Us form  
- Product Details View  
- Subscription  
- Add to Cart  
- Place Order  
- Remove from Cart  
✅ *All Automated Tests Passed*

---

## 🐞 Bug Report Summary
- **Total Bugs:** 3  
- **Severity:** High (2), Medium (1)  
- **Status:** Open  
- **Priority:** High (1), Medium (2)

---

## 🛠️ Tools & Technologies
- Selenium (Python)
- Apache JMeter
- Postman
- phpMyAdmin
- Excel
- GitHub

---

## 📁 Project Files
- `Functional_TestCases.xlsx`
- `API_TestCases.xlsx`
- `Performance_TestCases.jmx`
- `DB_TestCases.sql`
- `Selenium_Scripts/`
- `Bug_Report.xlsx`
- `Traceability_Matrix.xlsx`

---

## 📌 Conclusion
This project demonstrates real-world QA validation workflow across different layers of a live eCommerce application. It includes both manual and automated testing strategies, bug tracking, and performance bottleneck detection to ensure product quality and reliability.

---

**🔗 Developed by:** Nafis Ulfat  
**📧 Contact:** [nafisulfat1@gmail.com]  
