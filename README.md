# DVWA SQL Injection (Low Security) - Internship Task 3

## Objective
Demonstrate an SQL Injection attack on DVWA (low security).

## Steps Performed
1. Installed and configured DVWA
2. Set security level to **low**
3. Used payload: `' OR '1'='1` on the vulnerable login page
4. Extracted user data from the database

## SQL Injection Payload Used
```sql
' OR '1'='1
Screenshots
See /screenshots folder for proof of concept.

Tools Used
DVWA

Browser (for testing)

Burp Suite (optional for request interception)
