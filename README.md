![Version](https://img.shields.io/badge/Version-1.0-blue)  
![Author](https://img.shields.io/badge/Author-Trung_Huynh-green)  
![Docker](https://img.shields.io/badge/Docker-Latest-blue)  
![License](https://img.shields.io/badge/License-MIT-green)  
![Contributions](https://img.shields.io/badge/Contributions-Welcome-orange)  

# Web Application Security Analysis

Welcome to the **Web Application Security Analysis** repository! This project is dedicated to the research, simulation, and documentation of security vulnerabilities found in modern web applications, with a primary focus on the [OWASP Top 10](https://owasp.org/www-project-top-ten/) and other real-world threats.

---

## ✨ Overview
This repository aims to provide a structured, hands-on learning environment for:
- Security researchers and enthusiasts
- Web developers seeking secure coding practices
- SOC Analysts, Pentesters, and Red Teamers

Each topic includes practical examples, walkthroughs, and mitigation techniques to foster a deeper understanding of web security.

---

## 🔧 Vulnerability Categories

### OWASP Top 10 (2021)
- [A01 - Broken Access Control](docs/owasp/A01-broken-access-control.md)
- [A02 - Cryptographic Failures](docs/owasp/A02-cryptographic-failures.md)
- [A03 - Injection](docs/owasp/A03-injection.md)
- [A04 - Insecure Design](docs/owasp/A04-insecure-design.md)
- [A05 - Security Misconfiguration](docs/owasp/A05-security-misconfiguration.md)
- [A06 - Vulnerable and Outdated Components](docs/owasp/A06-vulnerable-components.md)
- [A07 - Identification and Authentication Failures](docs/owasp/A07-authentication-failures.md)
- [A08 - Software and Data Integrity Failures](docs/owasp/A08-software-integrity-failures.md)
- [A09 - Security Logging and Monitoring Failures](docs/owasp/A09-logging-monitoring-failures.md)
- [A10 - Server-Side Request Forgery (SSRF)](docs/owasp/A10-ssrf.md)

### Additional Vulnerabilities
- [Cross-Site Request Forgery (CSRF)](docs/others/csrf.md)
- [Clickjacking](docs/others/clickjacking.md)
- [Business Logic Flaws](docs/others/business-logic.md)
- [Open Redirects](docs/others/open-redirect.md)
- [CORS Misconfiguration](docs/others/cors.md)

---

## ⚙️ Tech Stack
- **Languages:** Python, JavaScript, HTML
- **Frameworks:** Flask, Express
- **Testing Tools:** Burp Suite, OWASP ZAP, Postman
- **Environments:** Docker, Linux
- **Reference Apps:** OWASP Juice Shop, DVWA, WebGoat

---

## 🌐 Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/huynhtrungcip/web-application.git
   ```
2. Navigate to the project directory:
   ```bash
   cd web-application
   ```
3. Follow individual documentation in the `docs/` folder for setup and demonstration of each vulnerability.

---

## 🔍 Resources
- [OWASP Official Website](https://owasp.org)
- [PortSwigger Web Security Academy](https://portswigger.net/web-security)
- [Hack The Box / TryHackMe Labs](https://tryhackme.com)

---

## ✍️ Contributing
We welcome all contributions! To contribute:
1. Fork the repo
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes
4. Open a Pull Request

Please review the [contributing guidelines](CONTRIBUTING.md) before submitting.

---

## 📄 License
This project is licensed under the [MIT License](LICENSE).

---

> ⚡ "Security is not a destination, it's a journey."
> 
> Empowering secure development through awareness and practice.

