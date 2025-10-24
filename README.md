# 🌍 Humanitarian Services API – SCIA Automation Testing

## 🎯 Objective
This project automates the testing of RESTful APIs for humanitarian and NGO operations using **SCIA (Smart Continuous Integration Automation)**.  
The goal is to ensure all API endpoints for **Volunteers**, **Donations**, **Disasters**, **Beneficiaries**, and **Resources** are validated for functionality, reliability, and performance.

---

## ⚙️ Key Modules & Endpoints
| Module | Endpoint | Method | Purpose |
|---------|-----------|--------|----------|
| Volunteer | `/api/volunteers` | GET, POST, PUT, DELETE | Manage volunteer records |
| Donations | `/api/donations` | GET, POST | Handle donations |
| Disaster | `/api/disaster` | GET, POST | Track disaster response |
| Beneficiary | `/api/beneficiary` | GET, POST | Manage beneficiaries |
| Resources | `/api/resources` | GET, PUT | Manage and allocate resources |

---

## 🧩 HTTP Types – SCIA Testing Focus

| HTTP Type | Description |
|------------|-------------|
| **GET** | Retrieves data from the server without modifying it. |
| **POST** | Creates new records or entries. |
| **PUT** | Updates an existing record completely. |
| **PATCH** | Partially updates specific fields in a record. |
| **DELETE** | Removes existing records permanently. |
| **OPTIONS** | Displays allowed methods for an endpoint. |
| **HEAD** | Returns header information without the body content. |

---

## 🚀 Automation Scope
- API functional testing for all modules  
- Regression and smoke testing in SCIA pipelines  
- Role-based access and security testing  
- Validation of response codes, schema, and performance  

---

## 🧠 Test Flow Example
1. `POST /api/volunteers` → Add volunteer → Expect `201 Created`  
2. `GET /api/volunteers` → Verify volunteer added → Expect `200 OK`  
3. `PUT /api/volunteers/{id}` → Update info → Expect `200 OK`  
4. `DELETE /api/volunteers/{id}` → Delete record → Expect `204 No Content`

---

## 🧪 Tools & Environment
- **Testing Tool:** SOAP UI / SCIA  
- **Automation Type:** RESTful API  
- **Format:** JSON  
- **Integration:** CI/CD Pipeline  

---

## 📁 Folder Structure
```
/SCIA-Automation/
│
├── TestCases/
│   ├── Volunteers_TestSuite.xml
│   ├── Donations_TestSuite.xml
│   └── Resources_TestSuite.xml
│
├── Data/
│   └── TestData.xlsx
│
├── Reports/
│   └── SCIA_TestReport.html
│
└── README.md
```

---

## 👥 Roles & Responsibilities
| Role | Responsibility |
|------|----------------|
| Admin | Manage all API modules and configurations |
| Volunteer Coordinator | Handles volunteer registration and updates |
| Donation Manager | Oversees donations and donor records |
| Disaster Coordinator | Manages disaster event data |
| Beneficiary Officer | Tracks beneficiaries and needs |
| Resource Manager | Updates and monitors resource allocations |
| Automation Tester | Creates, executes, and maintains SCIA test scripts |

---

## ✅ Expected Outcomes
- All API endpoints validated and documented  
- Automated test execution in SCIA pipelines  
- Real-time error reporting and regression checks  
- Improved reliability of NGO service APIs  

---

**Author:** Meenavalli Prasanna Kumar (Mass)  
**Project:** Humanitarian Services – SCIA Automation Test Suite  
**Tool:** SOAP UI / SCIA  
**Language:** JSON / XML  
