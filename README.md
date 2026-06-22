# 🧪 HelloGrowth CRM QA Testing

Manual functional testing of the HelloGrowth CRM web application — a customer relationship management platform. This project covers end-to-end test case execution, bug reporting, and structured QA documentation across all major CRM modules.

---

## 📌 Project Overview

| Field              | Details                                      |
|--------------------|----------------------------------------------|
| **Tester**         | Priyanshu Negi                               |
| **Application**    | HelloGrowth CRM                              |
| **Test Type**      | Manual Functional Testing                    |
| **GitHub**         | [igpriyanshunegi/hellogrowth-crm-qa-testing](https://github.com/igpriyanshunegi/hellogrowth-crm-qa-testing) |

---

## 📊 Test Summary

| Metric           | Count |
|------------------|-------|
| Total Test Cases | 35    |
| Passed           | 28    |
| Failed           | 7     |
| Bugs Found       | 10    |

---

## 🧩 Modules Tested

- Signup & Registration
- Email Verification
- Login
- Dashboard
- Consent Form
- Leads (Add, Edit, Archive, Search)
- Accounts (Add, Edit, Archive, Delete, Search)
- Deals (Add, Edit, Delete, Validation)
- Activities (Add, Delete)
- Reports & Analytics (Charts, Filters, Export)
- Profile Settings
- Logout
- Mobile UI (Navbar, AI Button)

---

## 🐛 Bugs Found

| Bug ID  | Module                     | Description                                        | Severity |
|---------|----------------------------|----------------------------------------------------|----------|
| BUG001  | Signup                     | Google signup not working — PROJECT_NOT_FOUND error | High     |
| BUG002  | Registration               | Invalid phone number accepted without validation   | Medium   |
| BUG003  | Email Verification         | Redirected to Sign In page instead of dashboard    | Low      |
| BUG004  | Activities                 | Delete activity throws workspace loading error     | High     |
| BUG005  | Profile                    | No profile update option available                 | Medium   |
| BUG006  | Mobile UI                  | Hamburger icon misaligned below navbar             | Low      |
| BUG007  | Mobile UI                  | AI button overlaps screen in mobile view           | Medium   |
| BUG008  | Backend API                | Multiple 400 Bad Request API errors in console     | High     |
| BUG009  | Database Schema            | Missing tenant\_id column error in console         | High     |
| BUG010  | Security / Server Config   | Directory listing enabled on /assets/ — exposes internal static files | Medium |

---

## 📁 Project Structure

```
hellgrowth-crm-qa-testing/
│
├── HelloGrowth_CRM_QA.xlsx    # Full QA report (Test Cases + Bug Report)
└── README.md                  # Project documentation
```

---

## 📋 QA Documents Included

- ✅ **Test Cases Sheet** — 35 test cases with Module, Scenario, Steps, Expected Result, Actual Result, Status
- ✅ **Bug Report Sheet** — 10 bugs with description, reproduction steps, severity, and expected vs actual result

---

## 🔗 Connect

- **GitHub**   : [github.com/igpriyanshunegi](https://github.com/igpriyanshunegi)
- **LinkedIn** : [linkedin.com/in/igpriyanshunegi](https://www.linkedin.com/in/igpriyanshunegi)
- **Email**    : priyanshun898@gmail.com
