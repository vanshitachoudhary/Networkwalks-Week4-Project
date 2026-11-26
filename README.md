# 🔐 Networkwalks – Week 4 Cybersecurity Project

### Local Lab Security Assessment | Reconnaissance | PDF Encryption | Database Security

---

## 📌 Project Overview

This repository documents my Week 4 Cybersecurity Internship project with **Networkwalks**.

The project focuses on practical security assessment activities performed in an isolated local OWASP Juice Shop environment using Kali Linux and various cybersecurity tools.

The assessment covers reconnaissance, PDF encryption verification, database security analysis, and professional security reporting.

## 🎯 Project Objectives

- Perform basic reconnaissance and service observation.
- Inspect HTTP responses and application endpoints.
- Understand and verify PDF encryption using AES-256.
- Analyze synthetic employee and shareholder records.
- Identify and remediate insecure local database file permissions.
- Prepare a structured security assessment report.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Kali Linux | Security testing environment |
| Docker | Local lab deployment |
| OWASP Juice Shop | Practice application |
| Nmap | Port scanning |
| cURL | HTTP and API inspection |
| Firefox | Web application assessment |
| qpdf | PDF encryption and verification |
| SQLite | Database creation and analysis |
| Python ReportLab | Synthetic PDF generation |

## 📂 Project Structure

```text
Networkwalks-Week4-Project/
│
├── M1-Reconnaissance/
│   ├── findings.txt
│   └── screenshots/
│
├── M2-PDF-Audit/
│   ├── findings.txt
│   └── screenshots/
│
├── M3-Data-Assessment/
│   ├── findings.txt
│   └── screenshots/
│
├── M4-Final-Report/
│   └── Networkwalks_Week4_Local_Lab_Final_Report.pdf
│
└── README.md
```

## 🔍 Project Modules

### M1 – Reconnaissance

**Activities performed:**
- Local Docker environment setup.
- Port scanning using Nmap.
- HTTP response inspection using cURL.
- robots.txt inspection.
- Product search API observation.
- Login and registration page inspection.
- Password guidance observation.

**Result:** Initial reconnaissance and application observations were documented.

### M2 – PDF Encryption Audit

**Activities performed:**
- Generated three synthetic PDF documents.
- Checked their initial encryption status.
- Applied AES-256 encryption using qpdf.
- Verified password protection.
- Reviewed PDF permission settings.

**Result:** AES-256 encryption was successfully applied and verified on all three synthetic PDF documents.

### M3 – Employee & Shareholder Data Security Audit

**Activities performed:**
- Created a local SQLite database with fictional records.
- Performed employee salary analysis.
- Reviewed synthetic shareholder records.
- Checked database file permissions.
- Restricted permissions using `chmod 600`.

**Result:** Database analysis was completed and file permissions were hardened from `644` to `600`.

### M4 – Final Security Assessment Report

A professional report was prepared containing:

- Executive Summary
- Scope and Methodology
- M1, M2 and M3 Findings
- Risk Assessment
- Security Recommendations
- Limitations and Conclusion

## 🛡️ Key Security Observations

- Application information was observed through HTTP responses and API requests.
- Password composition guidance was displayed on the registration page.
- AES-256 encryption was demonstrated on synthetic PDF files.
- Initial database permissions allowed broader local read access.
- Database permissions were restricted to owner-only access.

## 📋 Recommendations

- Follow the principle of least privilege.
- Enforce strong password policies.
- Protect sensitive files with appropriate encryption.
- Restrict database and backup permissions.
- Maintain access logs and perform regular security reviews.

## ⚠️ Disclaimer

This project was performed in an isolated local practice environment using OWASP Juice Shop.

All PDF documents and employee/shareholder records used in testing were synthetic training data.

No real patient records, confidential hospital documents, employee salaries, or shareholder information were accessed.

This repository documents local lab exercises and does not claim verified exploitation of the live Mediroza Hospital website.

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Basic reconnaissance techniques.
- Web application and API observation.
- PDF encryption and verification.
- SQLite database analysis.
- Linux file permissions and security hardening.
- Technical documentation and professional reporting.

---

**Project:** Networkwalks Week 4 Cybersecurity Internship  
**Focus:** Practical Security Assessment  
**Environment:** Kali Linux | Docker | OWASP Juice Shop

*Learning by doing. Securing by understanding.* 🔐
