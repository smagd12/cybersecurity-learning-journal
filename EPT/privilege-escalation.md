# Privilege Escalation

This file contains notes on privilege escalation and why it is important in cybersecurity.

---

## What is Privilege Escalation?

Privilege escalation occurs when a user or attacker gains access to permissions beyond those originally assigned to them.

This is often used by attackers after initial access has been obtained.

---

## Why is it Dangerous?

Privilege escalation can allow attackers to:

- Access sensitive information
- Install malware
- Modify system settings
- Create new user accounts
- Gain full administrative control

---

## Types of Privilege Escalation

### Vertical Privilege Escalation

Occurs when a user gains higher-level permissions.

Example:
- Standard user → Administrator

---

### Horizontal Privilege Escalation

Occurs when a user gains access to another user's resources at the same privilege level.

Example:
- User A accessing User B's account

---

## Common Causes

- Misconfigured permissions
- Weak access controls
- Unpatched vulnerabilities
- Excessive user privileges

---

## Least Privilege

The principle of least privilege states that users should only have the minimum permissions required to perform their tasks.

Benefits:
- Reduces attack surface
- Limits damage from compromise
- Improves security

---

## Linux Example

The sudo command allows authorized users to perform administrative actions without logging in as the root user.

Example:

sudo apt update

---

## What I Learned

- Privilege escalation is a common attacker objective.
- Excessive permissions increase security risk.
- Least privilege helps reduce the impact of attacks.
- Proper access control is an important security defence.