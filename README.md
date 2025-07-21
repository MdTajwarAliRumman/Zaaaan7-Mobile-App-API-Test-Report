# Zaaaan7-Mobile-App-API-Test-Report

<h1 align="center">🧪 API Automation Reports</h1>
<p align="center">
  <b>Postman + Newman + HTML Extra Reporter</b><br/>
  <i>Automated API test results with clear insights</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Postman-API-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/Newman-Automation-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square" />
</p>

---

## 📌 Project Summary

Zaaaan7 Project is a service-based mobile application that connects users with Helpers/Workers who provide various types of services based on the users’ needs. The platform features two types of users: service seekers and service providers (Helpers). Helpers can belong to different categories, such as assistants, electricians, plumbers, or mounting specialists.
Both users and Helpers set their locations to either request or offer services within their area. The platform also includes a messaging feature that allows seamless communication between users and Helpers. Additionally, users can leave reviews and ratings for Helpers to recognize their outstanding work and help others make informed decisions.. This repository documents the **API testing results** of the `Zaaaan7` API, executed using **Postman collections** and automated via **Newman CLI**.

---
## 📊 API Test Summary

| Endpoint             | Method | Test Status |
|----------------------|--------|-------------|
| `/register`          | POST   | ✅ Passed    |
| `/login`             | POST   | ✅ Passed    |
| `/verify-otp`        | POST   | ✅ Passed    |
| `/change-password`   | PUT    | ✅ Passed    |
| `/user/profile`      | POST    | ✅ Passed    |
| `/address`      | POST    | ✅ Passed    |
| `/address`  | DEL    | ❌ Failed    |
| `/task`      | POST    | ✅ Passed    |
| `/message`      | POST    | ✅ Passed    |
| `/notification`      | POST    | ✅ Passed    |
| `/reviews`      | POST    | ✅ Passed    |

_**Total Assertions:**_ 
✅ _Passed: 224_ &nbsp;&nbsp;&nbsp;&nbsp;❌ _Failed: 2_


---
## 📊 Live Report Preview

👉 **[View Full Test Report](https://github.com/MdTajwarAliRumman/Zaaaan7-Mobile-App-API-Test-Report/blob/main/Project_Zaaaan7_API_Test_Report_Tajwar.html)**

<img width="1073" height="952" alt="Image" src="https://github.com/user-attachments/assets/b477d2f6-51cd-4cd3-98ca-b9a6b61ee247" />
<img width="1077" height="820" alt="Image" src="https://github.com/user-attachments/assets/bc2f20f8-51d3-4afe-99ef-56354647b7b8" />
<img width="1076" height="420" alt="Image" src="https://github.com/user-attachments/assets/dd7c6dd4-952b-447f-8c24-ec84d0115a92" />




🕒 _Last generated: **July 19, 2025**_  

---

## ⚙️ Tech Stack

| Tool     | Purpose                       |
|----------|-------------------------------|
| Postman  | API requests & test scripting |
| Newman   | CLI-based test runner         |
| htmlextra | Stylish HTML report generator |
| Figma | Template design of the App (Private) |
| APK | Zaaaan7 mobile App different versions (Private)|

---

## 🚀 Quick Start

### 🔧 Install Dependencies

```bash
npm install -g newman newman-reporter-htmlextra

