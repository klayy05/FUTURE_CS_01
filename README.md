# FUTURE_CS_01
## **Overview**
This repository contains the **Task 01 security assessment task** for my cybersecurity internship.

The objective of this task is to **conduct security testing ** on a sample web application, identify vulnerabities, and document the findings.

---

## **Objectives**
- **Set up and explore** a sample web application.
- **Perform basic vulnerability assessments** using:
  - **OWASP ZAP** (Automated security scanning)
- **Document security findings** and suggest areas of improvement.

---

## **Setup Instructions**
To set up the test environment and perform a security testing, follow these steps:

### **1️⃣ Download and Install docker**
```sh
https://www.docker.com/products/docker-desktop/
```

### **2️⃣ Verify installation on command prompt or powershell**
```sh
docker --version
```

### **3️⃣ Test Docker**
```sh
docker run hello-world
```

### **2️⃣ Install the Vulnerable Web App(OWASP Juice Shop)**
```sh
https://owasp.org/www-project-juice-shop/
```

### **3️⃣ Pull the official Juice Shop Docker image(on command prompt or powershell)**
```sh
docker pull bkimminich/juice-shop
```

### **4️⃣ Run the Juice Shop container**
```sh
docker run --rm -p 3000:3000 bkimminich/juice-shop
```

### **5️⃣ Access it in Your Browser**
Navigate to:
```
http://localhost:3000
```

---

## **Vulnerability Assessment Steps**
### ** Automated Security Scanning (OWASP ZAP)**
- Run OWASP ZAP and configure it as a proxy for your browser.
- Perform a full scan of the running application.
- Identify vulnerabilities like XSS, SQL Injection, and authentication flaws.

## **Expected Outcomes**
- A security assessment report outlining:
  - Identified vulnerabilities and their severity.
  - Suggested remediation steps.
  - Screenshots of successful exploitations (if applicable).

---

## **Dependencies & Requirements**
- **OWASP ZAP** (for automated security scanning)
- **SQLmap** (for SQL injection testing, optional)
- **Modern Web Browser** (Chrome/Firefox with Developer Tools)
- **Operating System Compatibility**: Works on Windows, Linux, macOS

---
