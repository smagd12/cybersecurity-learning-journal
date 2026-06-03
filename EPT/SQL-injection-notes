# SQL Injection (SQLi) Notes

This file contains my notes on SQL Injection as part of my Ethical Hacking & Penetration Testing (EPT) studies and cybersecurity learning.

---

## What is SQL Injection?

SQL Injection is a web security vulnerability that occurs when an attacker is able to insert or "inject" malicious SQL code into an input field that is not properly secured.

This can allow attackers to:
- View sensitive data
- Modify database records
- Bypass authentication
- Delete data

---

## Why it Happens

SQL injection typically occurs when:
- User input is not properly validated
- Queries are dynamically built using string concatenation
- Parameterized queries are not used

---

## Example (Unsafe Query)

```sql
SELECT * FROM users WHERE username = 'admin' AND password = 'password';
```

If user input is inserted directly into the query, an attacker may be able to manipulate the SQL statement.

---

## Example Attack

Attacker Input:

```text
' OR '1'='1
```

This could change the query to:

```sql
SELECT * FROM users WHERE username = '' OR '1'='1' AND password = '';
```

This may allow login bypass because the condition is always true.

---

## Types of SQL Injection

### 1. In-Band SQL Injection
- The attacker receives results directly from the application.
- The most common form of SQL injection.

### 2. Blind SQL Injection
- Error messages are not displayed.
- The attacker infers information through true/false responses and application behaviour.

### 3. Error-Based SQL Injection
- Database error messages are used to reveal information about the system.

---

## Prevention Methods

### 1. Parameterized Queries (Best Practice)
- Separates user input from SQL commands.
- Prevents user input from being interpreted as executable SQL.

### 2. Input Validation
- Restricts expected input types and formats.
- Helps reduce malicious input.

### 3. Least Privilege Database Accounts
- Limits the damage that can occur if an attack succeeds.

### 4. Web Application Firewalls (WAF)
- Can help detect and block malicious requests.

---

## Why SQL Injection is Dangerous

SQL Injection can:
- Expose sensitive user data
- Lead to authentication bypass
- Allow modification or deletion of data
- Result in full database compromise

SQL Injection remains one of the most common web application vulnerabilities and is regularly featured in OWASP security guidance.

---

## What I Learned

- SQL Injection occurs when user input is not handled securely.
- Attackers can manipulate SQL queries to gain unauthorized access.
- Parameterized queries are the most effective defence against SQL Injection.
- Even simple input fields can become attack vectors if not properly secured.
