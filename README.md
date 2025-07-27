# 🧪 LouisH2 – Postman API Testing Collection

``Automated API testing with Postman & Newman including detailed HTML report``

This repository showcases API testing for the **LouisH2** project using **Postman** and **Newman**. It includes dynamic test scenarios, error handling, and a detailed HTML report generated using the `htmlextra` reporter.

---

## 📦 Project Contents

| File Name                            | Description                                                        |
|-------------------------------------|--------------------------------------------------------------------|
| `louish2 Final.postman_collection.json`    | Postman collection with all API endpoints tested                   |
| `newman-report.html`                | Newman HTML report (144 assertions, 1 failure, 0 skipped)          |

---

## 🧰 Tools & Technologies

- [Postman](https://www.postman.com/) – For API request scripting and testing
- [Newman](https://www.npmjs.com/package/newman) – CLI tool to run Postman collections
- [htmlextra Reporter](https://github.com/DannyDainton/newman-reporter-htmlextra) – Custom HTML reports

---

## 🚀 How to Run the Tests

### 1. Install Newman & Reporter Globally

```bash
npm install -g newman newman-reporter-htmlextra
```
### 2. Run the Collection

```bash
newman run louish2 Final.postman_collection.json -r htmlextra --reporter-htmlextra-export newman_report.html
```
---
## ✅ Test Coverage Highlights

- 🔐 **Auth (3 requests)**  
  - `register`  
  - `check otp`  
  - `login`

- 🧾 **Post Management (6 requests)**  
  - `store`  
  - `store_2`  
  - `get`  
  - `update`  
  - `edit`  
  - `delete`

- 🌟 **Review Module (2 requests)**  
  - `store`  
  - `my all tools review`

- 🖥️ **Frontend Tools Display (5 requests)**  
  - `popular tools`  
  - `per tools`  
  - `search`  
  - `all location`  
  - `all category`

- 💬 **Chats (2 requests)**  
  - `send message`  
  - `get all message`

- 📅 **Booking (2 requests)**  
  - `store`  
  - `get all booking`

- 💼 **Account (2 requests)**  
  - `create account`  
  - `withdraw request`

- 💰 **Earnings (1 request)**  
  - `my rent`

- 📊 **Dashboard (1 request)**  
  - `total data`

- 🙍‍♂️ **Profile Management (5 requests)**  
  - `get all information`  
  - `update information`  
  - `change password`  
  - `profile picture`  
  - `delete account`
 ---
## 📊 Sample Report Screenshot

![Test Report Screenshot](https://raw.githubusercontent.com/abdurtutul/louihh2_API-testing/main/screenshots/Screenshot%202025-07-27%20124313.png)


