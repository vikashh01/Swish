# 🧪 Swish Mobile App

---

## 📌 Project Details

| Item         | Description             |
|--------------|--------------------------|
| **Project Name** | Swish                     |
| **Created By**   | Vikash Kumar Bharti       |
| **Created Date** | 10-Apr-2025               |
| **Device Used**  | Redmi Note 5 Pro          |

---

## 📘 1. Introduction

This test plan defines the strategy, scope, and resources for testing **Swish**, a fast and efficient e-commerce mobile application. Swish offers features like:

- OTP-based login
- Product search
- Live location-based ordering
- Real-time order tracking
- Multiple payment options

The goal is to ensure a **smooth, secure, and reliable shopping experience** through comprehensive testing of all key functionalities.

---

## 🎯 2. Objectives

- Ensure all functional and non-functional requirements are met  
- Identify and fix bugs before app release  
- Validate app performance, usability, and compatibility  
- Confirm integration with payment gateways, messaging systems, and GPS services  

---

## 📦 3. Scope

### ✅ In Scope:
- Mobile number-based sign-up with OTP (SMS/WhatsApp)  
- Product browsing and cart operations  
- Add/manage delivery address  
- Payment methods (Google Pay, Payphone, Cash on Delivery, Wallet)  
- Offers, coupons, and rewards  
- Real-time order tracking (delivery under 10 mins)  
- User profile management and logout  
- Help & Support access  

### ❌ Out of Scope:
- Backend database testing  
- Performance/load testing on server infrastructure  

---

## 🔍 4. Testable Features

- User Authentication (Sign Up, OTP Verification)  
- Product Search, Selection, and Cart Functionality  
- Add Address with GPS/manual input  
- Payment and Rewards System  
- Live Order Tracking  
- Order History and Repeat Order  
- Gift a Swish (Referral Feature)  
- Help/Support & Profile Management  

---

## 🧪 5. Testing Approach

- Manual Testing: Functional, UI/UX, Integration, Usability  
- Black-box Testing for most scenarios  
- Regression Testing after each build  
- Smoke & Sanity Testing for every release  

---

## 👥 6. Roles and Responsibilities

| Role            | Responsibility                                       |
|------------------|------------------------------------------------------|
| **QA Lead**      | Create test plan, strategy, assign tasks             |
| **QA Engineers** | Create/execute test cases, log & retest bugs         |
| **Developers**   | Fix reported bugs and perform unit testing           |
| **Product Manager** | Review features and approve test coverage        |

---

## 📅 7. Test Schedule

| Phase              | Timeline                     |
|--------------------|------------------------------|
| Test Planning      | 10-April-2025 to 11-April-2025 |
| Test Case Creation | 10-April-2025 to 11-April-2025 |
| Test Execution     | 10-April-2025 to 11-April-2025 |
| Bug Fix & Retest   | 10-April-2025 to 11-April-2025 |


---

## 📄 8. Test Deliverables

- ✅ Test Plan Document  
- ✅ Mind Map  
- ✅ Test Scenarios  
- ✅ Test Cases (Google Sheets)  
- ✅ Test Data  
- ✅ Bug Reports (Jira or Bug Sheet)  
- ✅ Test Summary Report  

---

## 🚦 9. Entry & Exit Criteria

### Entry Criteria:
- All features implemented and stable build available  
- Test environment ready  
- Test cases reviewed and approved  

### Exit Criteria:
- All major/critical defects resolved  
- 95%+ test cases passed  
- QA sign-off obtained  

---

## 🛠️ 10. Tools Used

- **Test Case Management**: Google Sheets / Excel  
- **Bug Tracking**: Jira / Google Sheets  
- **Communication**: Slack / WhatsApp / Email  
- **Documentation**: Google Docs  
- **Devices**: Android (Manual Testing)  

---

## ⚠️ 11. Risks and Mitigation

| Risk                          | Mitigation Strategy                                |
|-------------------------------|----------------------------------------------------|
| Delayed build delivery        | Add buffer time in schedule                        |
| OTP delivery delay (SMS/WA)   | Use test numbers or mocks                         |
| Device compatibility issues   | Test on different devices/screen sizes            |
| Payment gateway failure       | Use sandbox/test mode for transactions            |
| Crashes/blockers during test  | Immediate reporting with hotfix priority          |

---

📌 *This document is maintained by Vikash Kumar Bharti for Swish QA Process.*
