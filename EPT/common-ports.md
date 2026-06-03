# Common Network Ports

This file contains commonly used network ports and their associated services. Understanding these is important for networking, security analysis, and penetration testing.

---

## Common Ports Overview

### Port 20 / 21 - FTP (File Transfer Protocol)
- Used for transferring files between systems
- Port 21 = control connection
- Port 20 = data transfer
- Often insecure if not using FTPS

---

### Port 22 - SSH (Secure Shell)
- Used for secure remote login to systems
- Commonly used for remote administration
- Encrypted communication

---

### Port 25 - SMTP (Simple Mail Transfer Protocol)
- Used for sending emails
- Can be abused for spam if not secured

---

### Port 53 - DNS (Domain Name System)
- Translates domain names into IP addresses
- Essential for internet browsing

---

### Port 80 - HTTP (Hypertext Transfer Protocol)
- Used for web traffic
- Not encrypted (insecure)

---

### Port 443 - HTTPS (HTTP Secure)
- Secure version of HTTP
- Uses TLS/SSL encryption
- Protects data in transit

---

### Port 110 - POP3 (Post Office Protocol)
- Used for receiving emails
- Downloads emails to local device

---

### Port 143 - IMAP (Internet Message Access Protocol)
- Used for accessing emails on a server
- Keeps emails synced across devices

---

### Port 3389 - RDP (Remote Desktop Protocol)
- Used for remote desktop access
- High-risk if exposed to the internet

---

## Why These Matter

- Helps identify services running on a system
- Important for reconnaissance and scanning
- Useful in vulnerability assessments
- Common targets during attacks

---

## What I Learned

- Different services run on specific ports
- Some ports are more commonly targeted by attackers
- Understanding ports helps in network security analysis