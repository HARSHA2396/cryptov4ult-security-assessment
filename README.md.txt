# 🛡️ CryptoV4ult Security Assessment

**Author:** T. Harsha Vardhan  

This project is a comprehensive security assessment report conducted for **CryptoV4ult**, an international cryptocurrency platform with over 1 million users. The aim is to identify, analyze, and mitigate security vulnerabilities in its infrastructure, including the application, containers, and API layers.

---

## 📘 Overview

As the lead security engineer, I evaluated the current security posture of CryptoV4ult and proposed mitigation strategies to strengthen:

- Application development (through Secure SDLC)
- Login system vulnerabilities
- Container security using Trivy scans
- API security for 3rd-party integrations

---

## 🧱 Project Structure

- `docs/`: Project presentation and documentation files.
- `reports/`: Threat matrix, vulnerability listings, scan outputs.
- `screenshots/`: Screenshots of scans and tools used.
- `remediation/`: Documents with remediation strategies.
- `.gitignore`: Files/folders to exclude from the repo.

---

## 🔐 Key Highlights

### 🔄 Secure SDLC Integration
- Integrated a secure development process by restructuring tasks across SDLC phases.
- Advocated the shift from Waterfall to Agile with security focus.

### 🚪 Login System Vulnerabilities
Identified 3 common vulnerabilities:
1. **Brute-force susceptibility**
2. **Insecure password storage**
3. **Lack of MFA (Multi-Factor Authentication)**

With appropriate mitigations proposed.

### 📦 Container Security
- Performed vulnerability scans on containers using `Trivy`.
- Found issues related to `CVE-2014-6271`.
- Suggested patching and base image hardening.

### 🔌 API Security
Outlined potential vulnerabilities before API development:
1. **Excessive data exposure**
2. **Broken authentication**
3. **Lack of input validation**

Provided preventive strategies for secure API implementation.

---

## 🧰 Tools Used

- **Trivy** – Container vulnerability scanner
- **Threat Modeling Matrix**
- **Secure SDLC Framework**
- **Markdown** – Documentation
- **Git** & **GitHub** – Version Control

---

## 📸 Screenshots

Find all relevant screenshots under `outputs/`.

---

## 📄 How to Use

This repository is for educational and reference purposes. You can navigate through the folders to understand each phase of the assessment.

---

## 📬 Contact

If you have any questions, feel free to connect:

- 📧 Email: tagirisaharshavardhan@gmail.com

---

> 📝 *This project is part of my academic coursework for CBS-0202 and showcases practical application of cybersecurity techniques in real-world scenarios.*

