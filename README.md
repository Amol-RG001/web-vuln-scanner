## 🛡️ Website Vulnerability Scanner (OWASP Top 10)

This Python-based tool scans a target website for common security vulnerabilities based on the OWASP Top 10 list and generates a comprehensive PDF report.

## ✅ Features

- 🔍 Scans the target URL for:
  - A01: Broken Access Control
  - A02: Cryptographic Failures
  - A03: Injection (SQL, CMD, etc.)
  - A04: Insecure Design (Basic XSS Scan)
  - A05: Security Misconfiguration (Headers Check)
  - A06: Vulnerable & Outdated Components
  - A07: Identification & Authentication Failures
  - A08: Software & Data Integrity Failures
  - A09: Logging & Monitoring Failures
  - A10: SSRF (Server-Side Request Forgery)
- 📄 Generates a PDF report in `/reports/` folder with results
- 🧪 Modular code structure for each OWASP category
- 🧼 Unicode-safe PDF output

---

## 🚀 How to Run

### 1. Clone the Repository

```bash

git clone https://github.com/Amol-RG001/web-vuln-scanner.git
cd website-vulnerability-scanner
```
### 2. Project Structure
```bash

website_vulnerability_scanner/
├── scanner.py
├── modules/
│   ├── a01_broken_access_control.py
│   ├── a02_crypto_failures.py
│   ├── a03_sql_injection_scanner.py
│   ├── a04_xss_scanner.py
│   ├── a05_common_headers_check.py
│   ├── a06_component_version_checker.py
│   ├── a07_auth_failures.py
│   ├── a08_data_integrity_check.py
│   ├── a09_logging_monitoring_check.py
│   └── a10_ssrf_scanner.py
├── utils/
│   └── report_generator.py
├── reports/
│   └── (Generated PDFs)
└── requirements.txt
```

## 📦 Dependencies
- #### requests
- #### fpdf
- #### argparse (Standard Library)
- #### textwrap (Standard Library)


## 📜 License
- MIT License. Free to use for personal or commercial purposes.