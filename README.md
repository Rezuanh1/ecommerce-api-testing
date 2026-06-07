# ShopZen E-Commerce — REST API Testing Project

**Tester:** Md Rezuan Hussain | SQA Engineer  
**Tool:** Postman  
**API Used:** JSONPlaceholder (https://jsonplaceholder.typicode.com)  
**Date:** June 2026  

---

## 📋 Project Overview

This project contains a complete REST API test suite for the ShopZen E-Commerce platform. A total of 13 API endpoints were tested using Postman covering Users, Posts (Products), Cart, and Orders modules. Each request includes pm.test() assertions for status codes, response time, and JSON field validation.

---

## 📁 Files in this Repository

| File | Description |
|------|-------------|
| `ShopZen_E-Commerce_API_Test_Suite_postman_collection.json` | Import this file in Postman to run all tests |
| `ShopZen_API_Test_Cases.xlsx` | Complete test cases with assertions and results |
| `ShopZen_API_Test_Report.pdf` | Full API test report |
| `screenshots/` | Test result screenshots from Postman |

---

## 📊 Test Results Summary

| Metric | Value |
|--------|-------|
| Total Endpoints Tested | 13 |
| Passed | 13 |
| Failed | 0 |
| Pass Rate | 100% |
| Methods Covered | GET, POST, PUT, PATCH, DELETE |

---

## 🧪 Modules Tested

| Module | Endpoints | Methods |
|--------|-----------|---------|
| Users | 7 | GET, POST, PUT, PATCH, DELETE |
| Posts (Products/Cart) | 6 | GET, POST, PUT, PATCH, DELETE |

---

## ✅ Assertions Used

- HTTP Status Code validation
- Response time under 2000ms
- JSON field existence check
- Array not empty check
- Field value match

---

## 🚀 How to Import in Postman

1. Open Postman
2. Click **Import**
3. Select `ShopZen_E-Commerce_API_Test_Suite_postman_collection.json`
4. Collection will appear as **ShopZen E-Commerce API Test Suite**
5. Click any request and hit **Send**

---

*Prepared by: Md Rezuan Hussain*
