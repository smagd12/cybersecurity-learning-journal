# Web Security

This file contains notes on common web security concepts, vulnerabilities, and security controls learned through my Ethical Penetration Testing (EPT) studies and practical labs.

---

## What is Web Security?

Web security focuses on protecting websites, web applications, and web services from cyber threats and unauthorized access.

Common goals include:
- Protecting sensitive data
- Preventing unauthorized access
- Maintaining confidentiality, integrity, and availability (CIA)

---

## HTTP vs HTTPS

### HTTP
- Hypertext Transfer Protocol
- Transfers data in plain text
- Data can be intercepted or modified

### HTTPS
- HTTP Secure
- Uses TLS/SSL encryption
- Protects data in transit
- Provides confidentiality and integrity

---

## Authentication vs Authorization

### Authentication
Verifies who a user is.

Examples:
- Passwords
- Multi-Factor Authentication (MFA)
- Biometrics

### Authorization
Determines what a user is allowed to access after authentication.

Example:
- An administrator can access management tools
- A standard user cannot

---

## Sessions and Cookies

Web applications use sessions to keep users logged in.

Cookies may contain:
- Session identifiers
- User preferences
- Authentication information

If session cookies are stolen, attackers may be able to impersonate users.

---

## SQL Injection (SQLi)

SQL Injection occurs when user input is improperly handled and malicious SQL commands are executed by the database.

Potential impacts:
- Data theft
- Authentication bypass
- Database compromise

### Prevention
- Parameterized queries
- Input validation
- Least privilege database accounts

---

## Cross-Site Scripting (XSS)

XSS occurs when attackers inject malicious scripts into a web application.

Potential impacts:
- Session cookie theft
- User impersonation
- Malicious actions performed on behalf of users

### Prevention
- Input validation
- Output encoding
- Content Security Policy (CSP)

---

## File Upload Vulnerabilities

Improperly secured file uploads can allow attackers to:

- Upload malware
- Host malicious files
- Execute malicious code
- Deliver attacks to other users

### Prevention
- Restrict file types
- Validate file contents
- Store uploads securely
- Scan uploads for malware

---

## Multi-Factor Authentication (MFA)

MFA provides additional security by requiring multiple authentication factors.

Examples:
- Password + mobile app approval
- Password + one-time code

### Common MFA Bypass Techniques
- MFA fatigue attacks
- Session hijacking
- Adversary-in-the-Middle (AiTM) phishing

---

## What I Learned

- Web applications are a common target for attackers.
- Authentication and authorization serve different purposes.
- HTTPS helps protect data in transit.
- Vulnerabilities such as SQL Injection and XSS can lead to serious compromises.
- Secure coding practices significantly reduce web security risks.