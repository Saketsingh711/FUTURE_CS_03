# API Security Risk Analysis - Future Interns Task 3

## 📌 Project Overview
This repository contains a professional security audit of a public API, conducted as part of my **Cyber Security Internship at Future Interns**. The assessment focuses on identifying vulnerabilities within the **JSONPlaceholder API** using the **OWASP API Security Top 10 (2023)** framework.

## 🎯 Objective
The primary goal was to act as a Security Consultant to:
* Analyze public API endpoints for logic and configuration flaws.
* Identify security risks such as Mass Assignment and Excessive Data Exposure.
* Provide business impact analysis and technical remediation steps for identified risks.

## 🛠️ Toolset
* **Target API:** [JSONPlaceholder](https://jsonplaceholder.typicode.com) [cite: 1]
* **API Testing:** **Postman** (Request construction, Header analysis, Response inspection) [cite: 2]
* **Reconnaissance:** **Browser DevTools** (Documentation and Route mapping) [cite: 2]
* **Framework:** **OWASP API Security Top 10** [cite: 3]

## 🔍 Key Findings Summary
| Risk Level | Vulnerability | OWASP Category |
| :--- | :--- | :--- |
| 🔴 **High** | **Mass Assignment** | API6:2023 |
| 🟡 **Medium** | **Excessive Data Exposure** | API3:2023 |
| 🟡 **Medium** | **Lack of Rate Limiting** | API4:2023 |
| 🔵 **Low** | **Security Misconfiguration** | API7:2023 |

## 📁 Repository Contents
* **`API Report Analysis.pdf`**: The full technical report including executive summary and remediation roadmap.
* **`/evidence`**: A gallery of Postman screenshots proving the successful identification of vulnerabilities.

## 👤 Author
**Saket Singh**
